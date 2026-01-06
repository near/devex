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

### Core SDKs & APIs

| Repository | Description | Status |
|------------|-------------|--------|
| [near-sdk-rs](https://github.com/near/near-sdk-rs) | NEAR smart contract SDK for Rust | Active |
| [near-api-rs](https://github.com/near/near-api-rs) | Rust-based API client library for interacting with the NEAR blockchain | Evolving |
| [near-jsonrpc-client-rs](https://github.com/near/near-jsonrpc-client-rs) | Low-level client for interfacing with the NEAR Protocol via JSON-RPC | Migration |

### CLI Tools

| Repository | Description | Status |
|------------|-------------|--------|
| [near-cli-rs](https://github.com/near/near-cli-rs) | CLI tool for interacting with the NEAR blockchain | Stable |
| [cargo-near](https://github.com/near/cargo-near) | Cargo extension for building `near-sdk-rs` smart contracts and ABI schemas on NEAR | Stable |
| [cargo-near-new-project-template](https://github.com/near/cargo-near-new-project-template) | Template for new cargo-near projects | Stable |
| [near-validators-cli-rs](https://github.com/near-cli-rs/near-validators-cli-rs) | CLI extension for validator operations | Stable |

### Sandbox & Testing

| Repository | Description | Status |
|------------|-------------|--------|
| [near-sandbox-rs](https://github.com/near/near-sandbox-rs) | Rust wrapper for the `neard` binary compiled with the `sandbox` feature flag | Stable |
| [near-sandbox-js](https://github.com/near/near-sandbox-js) | JavaScript wrapper for the `neard` binary compiled with the `sandbox` feature flag | Stable |
| [near-workspaces-rs](https://github.com/near/near-workspaces-rs) | Rust testing framework for NEAR smart contracts | Deprecating |

### Primitives & Types

| Repository | Description | Status |
|------------|-------------|--------|
| [near-account-id-rs](https://github.com/near/near-account-id-rs) | NEAR account ID type and validation | Stable |
| [near-gas-rs](https://github.com/near/near-gas-rs) | NEAR gas type | Stable |
| [near-sdk-abi](https://github.com/near/near-sdk-abi) | ABI schema types for NEAR smart contracts | Frozen |
| [borsh-rs](https://github.com/near/borsh-rs) | Binary Object Representation Serializer for Hashing | Stable |

### Other

| Repository | Description | Status |
|------------|-------------|--------|
| [near-plugins](https://github.com/Near-One/near-plugins) | NEAR smart contract plugins | Stable |
| [bridge-sdk-js](https://github.com/Near-One/bridge-sdk-js) | TypeScript SDK for cross-chain token transfers using the Omni Bridge protocol | Stable |

*Ownership implies responsibility for usability, maintenance, and coordinated releases - not sole authorship.*

## Getting in touch

- **Zulip (technical discussion)** - Ask your questions here: https://near.zulipchat.com/
- **Discourse (non-technical / direction)** - Propose ideas, share feedback: https://gov.near.org
