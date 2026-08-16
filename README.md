# seiscomp-scautoloc

![CI](https://github.com/platformfuzz/seiscomp-scautoloc/actions/workflows/ci.yml/badge.svg)
![Build and Release](https://github.com/platformfuzz/seiscomp-scautoloc/actions/workflows/build-and-release.yml/badge.svg)

Unofficial SeisComP scautoloc image built with public gsm. Not gempa-supported.

The process associates picks into origins.

**Package:** [ghcr.io/platformfuzz/seiscomp-scautoloc](https://github.com/platformfuzz/seiscomp-scautoloc/pkgs/container/seiscomp-scautoloc)

## Run

```bash
docker pull ghcr.io/platformfuzz/seiscomp-scautoloc:latest
docker run --rm ghcr.io/platformfuzz/seiscomp-scautoloc:latest
```

`SCMASTER_HOST`, `SEEDLINK_HOST`, and `DB_HOST` can be overridden at run time.

## Build

```bash
docker build -t seiscomp-scautoloc:test .
docker run --rm seiscomp-scautoloc:test
```
