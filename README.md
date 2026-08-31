# corral-sh/homebrew-tap

Homebrew tap for [Corral](https://github.com/corral-sh/corral) — run AI coding
agents inside isolated per-project Lima VMs on macOS.

```bash
brew install corral-sh/tap/corral
```

That one command auto-taps and auto-trusts. If Homebrew refuses to load the
formula (>= 6 tap trust), run `brew tap corral-sh/tap && brew trust corral-sh/tap` first.

The formula builds `corral` from the tagged source of the main repository —
there is no opaque binary download. The canonical copy of `Formula/corral.rb`
also lives in the main repository; the two are kept identical, and the `tag`
is bumped on every release.
