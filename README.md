# cuda-edge-runtime

GPU-accelerated edge runtime for autonomous agents. Rust+CUDA rebuild of nexus-edge-runtime.

## Modules (Planned CUDA Kernels)
- **Trust Engine** — reputation scoring, trust increments on GPU
- **Reflex Compiler** — compile agent reflexes to GPU bytecode
- **Fleet Coordination** — multi-agent task orchestration
- **Perception Fusion** — sensor data fusion on GPU
- **Safety System** — constraint checking with GPU acceleration
- **Digital Twin** — real-time state mirroring
- **Navigation** — path planning with GPU optimization

## Patterns from cudaclaw
- Persistent kernels for <5μs dispatch
- Cell agents (repr(C)) for GPU-side autonomy
- SmartCRDT for distributed state

## Status
Template repo created. CUDA kernels pending GPU hardware.