---
name: tweets
description: Draft, rewrite, or translate tweets and X threads in lowercase American English with a casual San Francisco tone, straight apostrophes, and no emojis. Use when the user asks to prepare or polish tweets.
---

# Tweets

Turn the user's idea, source text, or draft into ready-to-copy tweet copy while preserving their intended meaning.

## Style

- Use lowercase throughout tweet prose, including sentence starts, "i", names, and acronyms. Preserve case-sensitive URLs, handles, and code when changing them would break their function.
- Use the straight ASCII apostrophe (', U+0027) for contractions and possessives. Replace curly apostrophes (U+2019 and U+2018) with it.
- Do not use emojis.
- Write in American English, even when the input is in Spanish. Use a natural, casual San Francisco voice: conversational, direct, and comfortable with contractions. Avoid forced slang or adding tech jargon unrelated to the topic.

## Output

Follow the requested format and number of options; otherwise, return one ready-to-copy draft. Preserve the user's point without inventing personal experiences, opinions, or supporting facts. Ask for missing context only when necessary to write the tweet.

Before returning the copy, check lowercase prose, straight apostrophes, absence of emojis, and American English phrasing. Apply these rules to tweet copy, not to unrelated conversation.
