# RR 2in1 / OVA Build

This repository is a build-oriented copy of `rr` for **2in1** and **OVA** packaging.

## What this repo is for

- Build RR images with the `2in1` workflow
- Build OVA artifacts with the `ova` workflow
- Keep the source tree in sync with upstream RR while preserving the build automation used by `ainas2in1`

## Main workflows

- `.github/workflows/2in1.yml` — build RR 2in1 artifacts
- `.github/workflows/ova.yml` — build OVA artifacts
- `.github/workflows/rr.yml` — base RR build pipeline

## Notes

- The workflows depend on `myp015/ainas2in1`
- Generated artifacts include RR images and packaged outputs such as `.zip` / `.ova.gz`
- This repo is intended for build output and release automation, not for end-user documentation

## Usage

Use GitHub Actions to run the desired workflow.

If you need a more detailed README later, we can expand it with:
- build prerequisites
- artifact naming rules
- release process
- local test instructions
