# FinFlex Benchmark (Modified)

Modified FinFlex benchmark files derived from the ICCAD 2024 CAD Contest placement benchmark.

## Contents

- `ASAP7/LEF/modified` — Modified ASAP7 LEF technology and cell library files
- `ASAP7/LIB/modified` — Modified ASAP7 Liberty timing library files
- `ICCAD24_Benchmark/modified` — Modified benchmark designs at 60% utilization

## Benchmark Designs

| Design | Description |
|--------|-------------|
| aes_256 | AES-256 crypto core |
| ariane136 | RISC-V Ariane core |
| mempool_tile_wrap | MemPool tile wrapper |
| NV_NVDLA_partition_m | NVDLA partition (medium) |
| NV_NVDLA_partition_p | NVDLA partition (large) |
| hidden1–hidden5 | Hidden contest benchmarks |

Each design directory includes:

- `{design}_modified.def` — placement DEF
- `{design}_modified.v` — gate-level netlist
