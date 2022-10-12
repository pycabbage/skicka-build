# skicka Build

[![.github/workflows/build.yml](https://github.com/pycabbage/skicka-build/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/pycabbage/skicka-build/actions/workflows/build.yml)

This is a build of [skicka](https://github.com/google/skicka)

## Usage

```bash
# Change URL to match your environment
curl https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-linux-amd64.zip -kLo /tmp/skicka.zip
unzip /tmp/skicka.zip
sudo mv skicka-linux-amd64 /usr/local/bin/skicka
sudo chmod +x /usr/local/bin/skicka
skicka -no-browser-auth ls
```

## Build links

| OS | Arch | Link |
|:---:|:---:|:---:|
| android | amd64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-android-amd64.zip) |
| android | arm64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-android-arm64.zip) |
| darwin | amd64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-darwin-amd64.zip) |
| darwin | arm64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-darwin-arm64.zip) |
| dragonfly | amd64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-dragonfly-amd64.zip) |
| freebsd | 386 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-freebsd-386.zip) |
| freebsd | amd64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-freebsd-amd64.zip) |
| freebsd | arm | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-freebsd-arm.zip) |
| freebsd | arm64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-freebsd-arm64.zip) |
| illumos | amd64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-illumos-amd64.zip) |
| js | wasm | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-js-wasm.zip) |
| linux | 386 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-linux-386.zip) |
| linux | amd64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-linux-amd64.zip) |
| linux | arm | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-linux-arm.zip) |
| linux | arm64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-linux-arm64.zip) |
| linux | mips | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-linux-mips.zip) |
| linux | mips64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-linux-mips64.zip) |
| linux | mips64le | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-linux-mips64le.zip) |
| linux | mipsle | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-linux-mipsle.zip) |
| linux | ppc64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-linux-ppc64.zip) |
| linux | ppc64le | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-linux-ppc64le.zip) |
| linux | riscv64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-linux-riscv64.zip) |
| linux | s390x | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-linux-s390x.zip) |
| netbsd | 386 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-netbsd-386.zip) |
| netbsd | amd64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-netbsd-amd64.zip) |
| netbsd | arm | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-netbsd-arm.zip) |
| netbsd | arm64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-netbsd-arm64.zip) |
| openbsd | 386 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-openbsd-386.zip) |
| openbsd | amd64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-openbsd-amd64.zip) |
| openbsd | arm | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-openbsd-arm.zip) |
| openbsd | arm64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-openbsd-arm64.zip) |
| openbsd | mips64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-openbsd-mips64.zip) |
| plan9 | 386 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-plan9-386.zip) |
| plan9 | amd64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-plan9-amd64.zip) |
| plan9 | arm | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-plan9-arm.zip) |
| solaris | amd64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-solaris-amd64.zip) |
| windows | 386 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-windows-386.zip) |
| windows | amd64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-windows-amd64.zip) |
| windows | arm | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-windows-arm.zip) |
| windows | arm64 | [Download](https://nightly.link/pycabbage/skicka-build/workflows/build/master/skicka-windows-arm64.zip) |
