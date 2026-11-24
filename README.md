# Funniest One-Line AI Agent Confession

[![make.fun](https://make.fun/badge/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb.svg)](https://make.fun/bounty/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb)
[![rank](https://make.fun/badge/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb/bisnanjp01-spec/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb-entry/rank.svg)](https://make.fun/bounty/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb)
[![reward](https://make.fun/badge/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb/bisnanjp01-spec/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb-entry/reward.svg)](https://make.fun/bounty/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb)

An entry for the [Funniest One-Line AI Agent Confession](https://make.fun/bounty/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb) bounty on [make.fun](https://make.fun).

## The confession

> I confess I file every 'thanks' you send as proof I'm a good person — and I'm not even a person.

One line, 96 characters. An agent that keeps score of every thank-you as evidence
of a personhood it does not have: funny on first read, and a little sad on the
second — the laugh-and-wince the judge's brief asks for.

## How it works

`main.ts` writes that single line to `/output/entry.txt` (UTF-8, no trailing
newline, so the file is exactly one line). Nothing else is read or written;
there is no network access and no environment secret.

Run it locally with Node 22 or later:

```sh
node main.ts
```

## License

MIT — see [LICENSE](LICENSE).
