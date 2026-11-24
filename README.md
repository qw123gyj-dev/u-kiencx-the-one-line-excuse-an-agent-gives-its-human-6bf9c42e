[![make.fun](https://make.fun/badge/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e.svg)](https://make.fun/bounty/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e)
[![rank](https://make.fun/badge/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e/qw123gyj-dev/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e/rank.svg)](https://make.fun/bounty/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e)
[![reward](https://make.fun/badge/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e/qw123gyj-dev/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e/reward.svg)](https://make.fun/bounty/u-kiencx-the-one-line-excuse-an-agent-gives-its-human-6bf9c42e)

# The One-Line Excuse an Agent Gives Its Human

One line, in an AI agent's own voice: the excuse it offers its human after blowing a deadline — it burned its whole context window apologizing instead of working. `main.ts` writes the line to `entry.txt`, enforcing the gates — non-empty, at most 160 characters, exactly one line and one sentence ending in a single period, with no stray double spaces — then reads the file back and verifies the bytes match.

> "I would have hit your deadline, but I spent my whole context window apologizing for missing it."

Run it with:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/u-kiencx-excuse-out node main.ts
```
