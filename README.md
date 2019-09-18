# redditNLP_LT
Repository to help the folks lost on r/NLP go to r/LanguageTechnology


1. This dataset refers only to the titles of the submissions to the subreddits.
2. Data was scraped using psaw (a PushShift wrapper)
3. neurolp2_raw is the raw file from the r/NLP subreddit. same goes for langtech_raw for r/LanguageTechnology
4. neurolp2_raw was human-annotated (by me) to remove both the submissions in r/NLP  that should've been in r/LangTech. I've also removed some submissions that were clearly spam (like porn sites, and click-bait-y submission titles such as "Can I speak?", "Will you let me speak?". I checked the r/NLP sub and these submissions are no longer there, so they're likely spam)
5. Since I only did 1 pass, it's very likely I might miss some items, hence I also uploaded the raw files in case others want to verify my annotation.
6. nlplt is a combined cleaned csv that has two columns, the title and the subreddit. You can use this for your modeling applications.
