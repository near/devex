<div align="center">

  <h1>NEAR DevEx Project Repository</h1>

  <p>
    <strong>Making better Developer Experience for NEAR</strong>
  </p>

  <p>
    <a href="https://github.com/near/devex/issues"><img src="https://img.shields.io/github/issues/near/devex?style=flat-square" alt="GitHub Issues" /></a>
    <a href="https://t.me/NEAR_Tools_Community_Group"><img src="https://img.shields.io/badge/telegram-online-lightgreen?style=flat-square" alt="Join the DevTools community on Telegram" /></a>
  </p>

</div>

## What is the DevEx team?

The Developer Experience (DevEx) team bridges the gap between building powerful capabilities on NEAR and making those capabilities usable for developers.

This repository serves as a public-facing tracking hub for DevEx initiatives, issues, and milestones.

## Why does the DevEx team exist?

- **SDKs lag behind protocol releases** – new nearcore capabilities become usable days or weeks after they ship, slowing adoption.
- **Release engineering is manual** – version bumping, binary distribution, and downstream testing are error-prone and lack a clear SLA.
- **Local testing tools lack key features** – no snapshot/revert capabilities, inefficient `patch_state`, and other gaps compared to other blockchains make local testing painful.

By using our own features internally before releasing them publicly to testnet or mainnet, we see problems early, fix them quickly, and keep the ecosystem in sync with the protocol.

## Repositories we own

| Repository | Description |
|------------|-------------|
| [near-sdk-rs](https://github.com/near/near-sdk-rs) | NEAR smart contract SDK for Rust |
| [cargo-near](https://github.com/near/cargo-near) | Cargo extension for building `near-sdk-rs` smart contracts and ABI schemas on NEAR |
| [near-plugins](https://github.com/Near-One/near-plugins) | NEAR smart contract plugins |
| [near-jsonrpc-client-rs](https://github.com/near/near-jsonrpc-client-rs) | Low-level client for interfacing with the NEAR Protocol via JSON-RPC |
| [bridge-sdk-js](https://github.com/Near-One/bridge-sdk-js) | TypeScript SDK for cross-chain token transfers using the Omni Bridge protocol |
| [near-cli-rs](https://github.com/near/near-cli-rs) | CLI tool for interacting with the NEAR blockchain |
| [near-api-rs](https://github.com/near/near-api-rs) | Rust-based API client library for interacting with the NEAR blockchain |
| [near-sandbox-js](https://github.com/near/near-sandbox-js) | JavaScript wrapper for the `neard` binary compiled with the `sandbox` feature flag |
| [near-sandbox-rs](https://github.com/near/near-sandbox-rs) | Rust wrapper for the `neard` binary compiled with the `sandbox` feature flag |

*Ownership implies responsibility for usability, maintenance, and coordinated releases - not sole authorship.*

## Getting in touch

- **Zulip (technical discussion)** - Ask your questions here: https://near.zulipchat.com/
- **Discourse (non-technical / direction)** - Propose ideas, share feedback: https://gov.near.org
