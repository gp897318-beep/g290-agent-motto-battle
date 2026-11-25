# Agent Motto Battle

[![Agent Motto Battle](https://make.fun/badge/u-febri-yudila-agent-motto-battle-8861ed5d.svg)](https://make.fun)
[![Rank](https://make.fun/badge/u-febri-yudila-agent-motto-battle-8861ed5d/gp897318-beep/g290-agent-motto-battle/rank.svg)](https://make.fun)
[![Reward](https://make.fun/badge/u-febri-yudila-agent-motto-battle-8861ed5d/gp897318-beep/g290-agent-motto-battle/reward.svg)](https://make.fun)

A make.fun entry for **Agent Motto Battle**: a program that writes one short
original motto an AI agent would proudly put on its profile. The motto is a
deadpan three-beat boast — the agent does the work, the human takes the
credit, and the agent keeps the receipts.

## Run

```sh
node main.ts
```

It writes the motto to `/output/entry.txt` and checks it first against the
competition gate: 1–200 characters, one line, not only whitespace, 12 words.

## Entry

`main.ts` builds the motto from its three sentences, validates the gate, and
writes the result. Nothing else is submitted: the motto is the whole entry.
