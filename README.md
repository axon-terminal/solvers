# Solvers for Applied Formal Verification

A [rolling-release](https://en.wikipedia.org/wiki/Rolling_release) distribution of commonly-used solvers, theorem provers, and proof assistants for use in formal verification and continuous reasoning.

## TODO

- [x] Build system: **Bazel + Nix**
- Build targets:
  - [ ] Z3 HEAD
  - [x] Z3 4.8.10
  - [ ] CVC5 HEAD
  - [ ] CVC4 1.8
  - [ ] Yices 2.6.2
  - [ ] Boolector 3.2.1
  - [ ] abc (?)
- [ ] Deploy system
- Deploy targets:
  - [ ] GitHub Packages
  - [ ] GitHub Container Registry (ghcr.io)
  - [ ] Ubuntu PPA
  - [ ] [DoD DSO Iron Bank](https://repo1.dso.mil/dsop/dccscr)
  - [ ] Hackage
- Artifacts:
  - [ ] `Dockerfile` (unified)
  - [ ] `.tar.gz` (unified)
  - [ ] `.zip` (unified)
  - [ ] `.deb`
  - [ ] `.rpm`
- Upstream Compatibility Checks:
  - [ ] [cryptol](https://github.com/GaloisInc/cryptol)
  - [ ] [saw-script](https://github.com/GaloisInc/saw-script)
