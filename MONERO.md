# Monero Repository

## Overview

This directory contains a fork of the official [Monero Project](https://github.com/monero-project/monero) - a private, secure, untraceable cryptocurrency.

**Repository:** [Commodore6416/monero](https://github.com/Commodore6416/monero)
**Forked From:** [monero-project/monero](https://github.com/monero-project/monero)
**Last Updated:** November 29, 2025

## About Monero

Monero is a privacy-focused cryptocurrency that provides:

- **Privacy:** Transactions are cryptographically obscured by default
- **Security:** Distributed peer-to-peer consensus network
- **Untraceability:** Ring signatures ensure transactions cannot be tied to individuals
- **Decentralization:** Anyone can run the software using consumer-grade hardware

## Repository Status

### Recent Updates

This fork has been synchronized with the latest upstream changes from the official Monero project. The update includes:

- Latest security patches and bug fixes
- Protocol improvements and optimizations
- Enhanced wallet functionality
- Updated documentation
- New Guix build system integration
- Improved network and P2P features
- RandomX mining algorithm updates

### Key Changes from Upstream Sync

The fork was updated from commit `8f48f4649` to `41ad5238a`, bringing in:

- 800+ file changes
- Enhanced cryptography implementations
- Blockchain database optimizations
- Improved daemon and RPC functionality
- Updated dependencies and build system
- New testing frameworks and tools

## Community Participation

As mentioned in your profile, you participated as a voter in Monero elections/governance. The Monero community operates through:

### Community Crowdfunding System (CCS)

The Monero CCS allows community members to propose and vote on funding for:
- Development work
- Research initiatives
- Community projects
- Infrastructure improvements

### Monero Research Lab

Open forum for research into:
- Cryptography protocols
- Privacy enhancements
- Fungibility improvements
- Network analysis

## Technical Details

### Core Components

- **Language:** C++ (primary)
- **Consensus:** Proof-of-Work (RandomX algorithm)
- **Block Time:** ~2 minutes
- **License:** BSD-3-Clause

### Key Directories

```
monero/
├── src/               # Core source code
├── contrib/           # Additional tools and utilities
├── external/          # External dependencies
├── tests/             # Test suite
└── utils/             # Utility scripts
```

## Development Resources

- **Official Site:** [getmonero.org](https://getmonero.org)
- **Documentation:** [docs.getmonero.org](https://docs.getmonero.org)
- **IRC:** #monero-dev on Libera Chat
- **Research Lab:** #monero-research-lab on Libera Chat

## Building Monero

### Prerequisites

- CMake 3.5 or higher
- GCC 7.1 or higher (or Clang 8 or higher)
- Boost 1.58 or higher
- OpenSSL
- libsodium
- libunbound
- libusb (for hardware wallet support)

### Quick Build

```bash
cd monero
make release
```

### Guix Builds

For reproducible builds:

```bash
./contrib/guix/guix-build
```

See `contrib/guix/INSTALL.md` for detailed Guix setup instructions.

## Contributing to Monero

The Monero project welcomes contributions:

1. **Code Contributions:** Submit pull requests to the master branch
2. **Testing:** Help test new features and releases
3. **Documentation:** Improve docs and translations
4. **Research:** Contribute to the Monero Research Lab
5. **Community Support:** Help others in IRC/Matrix channels

## Important Notes

### Pushing Updates

To push your local changes to your GitHub fork, you'll need to authenticate. From the monero directory:

```bash
cd monero
git push origin master
```

If using personal access tokens or SSH keys, ensure they're properly configured.

### Staying Updated

To keep your fork synchronized with upstream:

```bash
cd monero
git fetch upstream
git merge upstream/master
git push origin master
```

## Privacy and Security

Monero is designed for privacy-focused transactions. Key privacy features:

- **Stealth Addresses:** One-time addresses for each transaction
- **Ring Signatures:** Mixing transactions to obscure sender
- **RingCT:** Hiding transaction amounts
- **Kovri Integration:** I2P routing for network-level privacy

## Support the Project

The Monero project is 100% community-sponsored:

**Monero Donation Address:**
`888tNkZrPN6JsEgekjMnABU4TBzc2Dt29EPAvkRxbANsAnjyPbb3iQ1YBRk1UXcdRsiKc9dhwMVgN5S9cQUiyoogDavup3H`

## Additional Resources

- [Monero StackExchange](https://monero.stackexchange.com/)
- [Vulnerability Response Process](https://github.com/monero-project/meta/blob/master/VULNERABILITY_RESPONSE_PROCESS.md)
- [Monero Standards](https://github.com/monero-project/monero-standards)
- [Translation Platform](https://translate.getmonero.org/)

---

**Note:** This is a fork for learning, development, and community participation. All contributions should follow Monero's established development practices and be submitted to the upstream repository when appropriate.
