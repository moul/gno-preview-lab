# gno-preview-lab

A disposable snapshot of [gnolang/gno](https://github.com/gnolang/gno) used to
exercise the **gnoweb pull-request preview** CI end to end before it lands upstream
([gnolang/gno#6194](https://github.com/gnolang/gno/pull/6194)).

- Not a fork, and not a mirror: one squashed commit of `gnoweb-pr-preview`, so PR
  diffs and Pages deploys behave like the real thing without dragging the history.
- Every workflow except the four under test has been removed, so a test PR costs a
  preview build and nothing else.
- Preview site: <https://moul.github.io/gno-preview-lab/>

Delete this repo when the upstream PR is settled.
