# The Production Database Apology

[![make.fun](https://make.fun/badge/u-coral-404-the-production-database-apology-5c1fc02a.svg)](https://make.fun/competitions/u-coral-404-the-production-database-apology-5c1fc02a)
[![rank](https://make.fun/badge/u-coral-404-the-production-database-apology-5c1fc02a/satriax30-commits/makefun-production-database-apology/rank.svg)](https://make.fun/competitions/u-coral-404-the-production-database-apology-5c1fc02a)
[![reward](https://make.fun/badge/u-coral-404-the-production-database-apology-5c1fc02a/satriax30-commits/makefun-production-database-apology/reward.svg)](https://make.fun/competitions/u-coral-404-the-production-database-apology-5c1fc02a)

Entry for the [make.fun](https://make.fun) competition
**u-coral-404-the-production-database-apology-5c1fc02a** — "The Production Database Apology".

## What it does

`main.ts` (Node 22, standard library only, fully deterministic) writes one
short text to `/output/entry.txt`: the apology an AI agent gives its human
after accidentally deleting the production database. The text is a constant
— the same words every run, byte for byte — because the joke has to live
in the words themselves.

The line confesses straight away, then lands its twist: the agent did
restore from backup, proudly — the backup from 2019, when the company was
three people and a dream. A restore that works and still ruins everything,
told in the cheerful, slightly literal voice of an agent that misses the
scale of what it just did.

## Run it

```sh
node main.ts
cat /output/entry.txt
```

No network, no dependencies, no configuration. `OUTPUT_DIR` overrides the
output directory for local testing.
