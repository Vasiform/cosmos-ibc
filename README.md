# Interchain Standards Development

## Synopsis

This repository is the canonical location for development and documentation of inter-chain standards utilized by the Cosmos network & interchain ecosystem. Initially it will be used to consolidate design documentation for the inter-blockchain communication protocol (IBC), encoding standards for Cosmos chains, and miscellaneous utilities such as off-chain message signing.

## Standardization

Please see [ICS 1](spec/ics-1-ics-standard) for a description of what a standard entails.

To propose a new standard, [open an issue](https://github.com/cosmos/ics/issues/new). To start a new standardization document, copy the [template](spec/ics-template.md) and open a PR.

See [PROCESS.md](PROCESS.md) for a description of the standardization process.

## Interchain Standards

All standards in the "draft" stage are listed here in order of their ICS numbers, sorted by category.

The subject of most initial interchain standards is the inter-blockchain communication protocol, "IBC":
- [Design philosophy of IBC](./docs/WHY_IBC.md)
- [Architectural overview of IBC](./docs/IBC_ARCHITECTURE.md)
- [IBC specification progress tracking](https://github.com/cosmos/ics/issues/26)

### Meta

| Interchain Standard Number   | Standard Title             | Stage |
| ---------------------------- | -------------------------- | ----- |
| [1](spec/ics-1-ics-standard) | ICS Specification Standard | Draft |
