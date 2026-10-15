# Arterio CAD native binaries

This public repository distributes prebuilt CAD command-line packages for Arterio. It does not contain the application source.

Each release contains an `@arterio/cad-native` package with Linux x64 (glibc 2.39 or later) and macOS ARM64 (macOS 11 or later) executables. The package selects the host binary without install scripts, Python, or a Rust toolchain.

Install a pinned release tarball with your Node package manager. Arterio applications declare the exact release URL in their package dependencies. No GitHub token or GitHub CLI is needed to download a public release.

The native CLI contains code ported from ezdxf 1.4.4 under the MIT license. The package includes the license and build manifests. Skia and ODA are separate dependencies.
