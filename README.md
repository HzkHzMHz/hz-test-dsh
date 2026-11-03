# hz-test-dsh

A sandbox repository for testing [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness)
(DSH) — the plugin-based agent harness behind the `dsh` CLI and Web GUI.

## Purpose

The repository is used by [HzkHz](https://github.com/HzkHzMHz) to exercise a full
agent workflow in a low-risk project:

1. An issue describes the change to make.
2. The `hz-dsh` agent implements it on a ticket branch and opens a pull request.
3. The pull request is reviewed before it is merged.

## Contents

The repository currently holds this README only; there is no application code to
install, build or run.

## Trying the workflow

```sh
git clone https://github.com/HzkHzMHz/hz-test-dsh.git
cd hz-test-dsh
```

Open an issue and mention `@hz-dsh` to request a change. The agent works on a
branch named `agent/<ticket-name>` and links the resulting pull request back to
the issue.
