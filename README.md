# Matrix-Magiq Liquidity Pallet

## Overview

The Matrix-Magiq Liquidity Pallet provides a unified liquidity solution across the Matrix-Magiq ecosystem, including NRSH (Nourish Chain), ELXR (Elixir Chain), and IMRT (Immortality Chain). This pallet is designed with quantum-resistance at its core, ensuring financial operations remain secure in the post-quantum era.

## Key Features

- **Shared Liquidity Pool**: Unified pool for NRSH, ELXR, and IMRT tokens
- **Quantum-Resistant Financial Operations**: All operations implement multiple layers of quantum-resistant cryptography
- **Cross-Chain Atomic Swaps**: Secure token exchange across parachains
- **Comprehensive Error Correction**: Implements all three layers of Matrix-Magiq error correction
  - Classical error correction using Reed-Solomon codes
  - Bridge error correction for classical-quantum interfaces
  - Quantum error correction using Surface codes

## Integration

The Liquidity Pallet integrates with:

- NRSH (Nourish Chain): Providing liquidity for spirulina cultivation tracking
- ELXR (Elixir Chain): Enabling liquid markets for kombucha fermentation tracking
- IMRT (Immortality Chain): Core coordination and JAM (Justified Atomic Merkleization)

## Implementation

The pallet is implemented using Substrate's FRAME system and follows all Polkadot best practices for parachain development.

## Documentation

For detailed documentation, see the `/docs` directory:

- [Architecture Overview](./docs/ARCHITECTURE.md)
- [Integration Guide](./docs/INTEGRATION.md)
- [API Reference](./docs/API.md)

## Examples

Example implementations can be found in the `/examples` directory:

- [Basic Pool Setup](./examples/basic_pool.rs)
- [Cross-Chain Swap](./examples/cross_chain_swap.rs)
- [Quantum-Resistant Transaction](./examples/quantum_resistant_tx.rs)

## Testing

Run tests with:

```bash
cargo test
```

## License

GPL-3.0
