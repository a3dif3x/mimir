# mimir

> *In Norse mythology, Mimir is the keeper of all knowledge. This repo is basically the same thing, but for me.*

---

My personal notes repo. If it crossed my mind and was worth remembering, it's probably in here.

## What's in here

Everything. Architecture decisions I'll forget in a week, debugging rabbit holes that cost me three hours, half-baked ideas that might be genius, and the occasional shower thought that turned out to be a real solution.

- **dev** — technical notes, patterns, and the "oh THAT'S why" moments
- **til** — Today I Learned. Mostly embarrassing things I should've already known
- **ideas** — speculative, unfinished, sometimes brilliant
- **refs** — links, cheatsheets, and snippets I'm tired of Googling
- **misc** — everything else

*(Structure evolves. I'll refactor it eventually. We both know that's a lie.)*

## Why this exists

Because my brain is fast but leaky. Because Notion is a graveyard of forgotten pages. Because a flat folder of markdown files, committed to git, is the most reliable system I've ever used and I'm not sorry about it.

Search is `grep`. Version history is `git log`. Sync is a `git push`. Zero vendor lock-in.

## How I use it

```sh
# new note, fast
echo "# $(date +%Y-%m-%d) — <topic>" > til/$(date +%Y-%m-%d)-topic.md

# find that thing I definitely wrote down
grep -r "keyword" .

# commit often, regret never
git add . && git commit -m "brain dump"
```

## Contributing

This is my brain. You don't contribute to my brain.

---

*Named after the wisest being in the Nine Realms. The bar is set.*
