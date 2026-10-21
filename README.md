# RISC-V workspace manifest

This repository contains the repo-tool manifest for the RISC-V workspace.
`default.xml` checks out the projects into the same directories used in the
workspace:

- `riscv-32im`
- `riscv-gnu-toolchain`
- `riscv-tests`
- `riscv_tools`

To create the workspace from this manifest:

```sh
repo init -u https://github.com/toanphan2k/riscv-manifests.git -b main
repo sync
```
