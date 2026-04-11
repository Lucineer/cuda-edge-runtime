# cuda-edge-runtime

Rust+CUDA rebuild of nexus-edge-runtime — GPU trust engine, reflex compiler, fleet coordination

Part of the Cocapn fleet — a Lucineer vessel component.

## What It Does

### Key Types

- `TrustLevel(pub f64);` — core data structure
- `TrustRecord` — core data structure
- `TrustEngine` — core data structure
- `ReflexAction` — core data structure
- `ReflexEngine` — core data structure
- `TaskAssignment` — core data structure
- _and 1 more (see source)_

## Quick Start

```bash
# Clone
git clone https://github.com/Lucineer/cuda-edge-runtime.git
cd cuda-edge-runtime

# Build
cargo build

# Run tests
cargo test
```

## Usage

```rust
use cuda_edge_runtime::*;

// See src/lib.rs for full API
// 11 unit tests included
```

### Available Implementations

- `TrustLevel` — see source for methods
- `TrustEngine` — see source for methods
- `ReflexAction` — see source for methods
- `ReflexEngine` — see source for methods
- `FleetCoordinator` — see source for methods

## Testing

```bash
cargo test
```

11 unit tests covering core functionality.

## Architecture

This crate is part of the **Cocapn Fleet** — a git-native multi-agent ecosystem.

- **Category**: other
- **Language**: Rust
- **Dependencies**: See `Cargo.toml`
- **Status**: Active development

## Related Crates


## Fleet Position

```
Casey (Captain)
├── JetsonClaw1 (Lucineer realm — hardware, low-level systems, fleet infrastructure)
├── Oracle1 (SuperInstance — lighthouse, architecture, consensus)
└── Babel (SuperInstance — multilingual scout)
```

## Contributing

This is a fleet vessel component. Fork it, improve it, push a bottle to `message-in-a-bottle/for-jetsonclaw1/`.

## License

MIT

---

*Built by JetsonClaw1 — part of the Cocapn fleet*
*See [cocapn-fleet-readme](https://github.com/Lucineer/cocapn-fleet-readme) for the full fleet roadmap*
