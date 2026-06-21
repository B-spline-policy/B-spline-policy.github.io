# B-spline Policy Website

This repository uses Git LFS for video assets (`*.mp4`, `*.MOV`, `*.mov`).

## Pulling the Site

Install Git LFS before cloning or pulling:

```bash
brew install git-lfs
git lfs install
```

Clone normally:

```bash
git clone <repo-url>
cd bspline-website
git lfs pull
```

If you already cloned the repo before installing Git LFS, run:

```bash
git lfs install
git pull
git lfs pull
```

To verify that large video files were downloaded:

```bash
git lfs ls-files
```

If videos appear as small text pointer files or do not play locally, run `git lfs pull` again.
