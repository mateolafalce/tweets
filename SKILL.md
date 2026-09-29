---
name: tweets
description: Draft, rewrite, or translate tweets and X threads in American English with lowercase prose except for "I", a casual San Francisco tone, straight apostrophes, no final periods, no dash connectors, and no emojis. Use when the user asks to prepare or polish tweets.
---

# Tweets

Turn the user's idea, source text, or draft into ready-to-copy tweet copy while preserving their intended meaning.

## Style

- Use lowercase throughout tweet prose, including sentence starts, names, and acronyms, except for the first-person pronoun "I". Always capitalize "I", including in contractions such as "I'm", "I've", "I'll", and "I'd". Preserve case-sensitive URLs, handles, and code when changing them would break their function.
- Use the straight ASCII apostrophe (', U+0027) for contractions and possessives. Replace curly apostrophes (U+2019 and U+2018) with it.
- Do not end a tweet with a period, including each individual tweet in a thread. Do not use trailing ellipses as a substitute. Internal sentence periods are allowed.
- Never use em dashes (U+2014). Do not use hyphens, double hyphens, or en dashes to connect clauses or ideas. Use commas, conjunctions, or separate sentences instead. Hyphens within compound words, URLs, handles, or code are allowed.
- Do not use emojis.
- Write in American English, even when the input is in Spanish. Use a natural, casual San Francisco voice: conversational, direct, and comfortable with contractions. Avoid forced slang or adding tech jargon unrelated to the topic.

## Output

Follow the requested format and number of options; otherwise, return one ready-to-copy draft. Preserve the user's point without inventing personal experiences, opinions, or supporting facts. Ask for missing context only when necessary to write the tweet.

Before returning the copy, check lowercase prose with capitalized "I" and its contractions, straight apostrophes, no final periods on any tweet, no em dashes or dash connectors, absence of emojis, and American English phrasing. Apply these rules to tweet copy, not to unrelated conversation.
