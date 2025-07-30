# `scribe`

Checks every Sunday at `00:00` UTC for the latest commit in [edwardloveall/scribe](https://git.sr.ht/~edwardloveall/scribe) and builds a GHCR image from it.

The built images are **only** tagged with the latest commit hash from [edwardloveall/scribe main commits](https://git.sr.ht/~edwardloveall/scribe/tree). like, `ghcr.io/dpi0/scribe:b092ba6dc1b3e0ddd43b7b3ca84f695695aaa949`
