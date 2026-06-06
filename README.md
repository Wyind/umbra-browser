# Umbra Browser

Browse without compromise. Umbra is a privacy-focused browser built on the latest Firefox engine. Hardened by default, extended with powerful privacy tools, and designed to respect your digital sovereignty.

**[Website](https://umbra-browser.org) | [Documentation](https://umbra-browser.org/pages/docs.html) | [Downloads](https://umbra-browser.org/pages/downloads.html)**

## Why Umbra?

* **Privacy Hardened:** Maximum privacy settings, fingerprinting resistance (RFP), HTTPS-only mode, query stripping, and strict content blocking enabled by default.
* **Pre-loaded Extensions:** uBlock Origin, AdNauseam, and TrackMeNot come pre-installed and ready.
* **Fast & Secure:** Built on the latest Firefox ESR with additional security hardening including strict certificate pinning, CRLite, TLS 1.3 optimizations, and jemalloc memory allocator.
* **Low Overhead:** Disk cache disabled, session restore privacy-level max, autoplay blocked, and speculation/prefetching turned off.
* **Clean Onboarding:** A welcoming first-run experience that explains your privacy tools without getting in your way. No ads, no sponsored content, no telemetry.

## Getting Started

Pre-built binaries for Linux, macOS, and Windows will be available on the [Downloads page](https://umbra-browser.org/pages/downloads.html) once the first public release is ready.

For detailed guides, configuration instructions, and FAQs, please visit the [Umbra Documentation](https://umbra-browser.org/pages/docs.html).

## Building from Source

You can build Umbra directly from the source repository.

### Prerequisites
* Rust
* clang
* Python 3
* A bootstrapped Firefox build environment

*Note: Building from source requires approximately 40 GB of disk space and 16 GB of RAM.*

### Build Instructions

1. Clone the repository:
   ```bash
   git clone [https://github.com/Wyind/umbra-browser.git](https://github.com/Wyind/umbra-browser.git)
   cd umbra-browser/source
