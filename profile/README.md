# AMD ROCm™ Software

ROCm is AMD's open software stack of drivers, runtimes, compilers, libraries, and tools for GPU computing — spanning AI, HPC, and scientific computing on AMD Instinct™, Radeon™, Radeon™ PRO, and Ryzen™ AI hardware.
 
## Start here
 
- **New to ROCm** — install on [Linux](https://rocm.docs.amd.com/en/latest/install/rocm.html) or [Windows](https://rocm.docs.amd.com/projects/install-on-windows/en/latest/)
- **Running AI workloads** — [Install PyTorch](https://rocm.docs.amd.com/projects/ai-ecosystem/en/latest/frameworks/pytorch/install.html), [Install JAX](https://rocm.docs.amd.com/projects/ai-ecosystem/en/latest/frameworks/jax/install.html), or browse the [AI Ecosystem docs](https://rocm.docs.amd.com/projects/ai-ecosystem/en/latest/)
- **Writing GPU code** — [ROCm Examples](https://github.com/ROCm/rocm-examples) and the [HIP programming guide](https://rocm.docs.amd.com/projects/HIP/en/latest/)
- **Deploying at datacenter scale** — [Instinct systems and infrastructure docs](https://instinct.docs.amd.com/latest/)
- **Checking hardware support** — the [compatibility matrix](https://rocm.docs.amd.com/en/latest/compatibility/compatibility-matrix.html) for supported GPUs, operating systems, and ROCm versions
- **Tutorials and deep dives** — [ROCm Blogs](https://rocm.blogs.amd.com/), with hands-on articles on AI, HPC, and performance tuning
 
## Where the code lives
 
Most ROCm components have been consolidated into a small number of repositories. Start in these:
 
| Repository | What's in it |
|---|---|
| [ROCm/TheRock](https://github.com/ROCm/TheRock) | Unified CMake build platform for ROCm, with nightly ROCm/PyTorch/JAX builds and native Windows support |
| [ROCm/rocm-libraries](https://github.com/ROCm/rocm-libraries) | Math, AI, and communication libraries — rocBLAS, hipBLASLt, MIOpen, Composable Kernel, rocFFT, rocSPARSE, rocPRIM, and more |
| [ROCm/rocm-systems](https://github.com/ROCm/rocm-systems) | Runtimes and system software — HIP, CLR, ROCr Runtime, RCCL, rocprofiler-sdk, AMD SMI, RDC, rocDecode |
| [ROCm/llvm-project](https://github.com/ROCm/llvm-project) | AMD's LLVM-based compiler toolchain for GPU code generation |
| [ROCm/rocm-examples](https://github.com/ROCm/rocm-examples) | Worked examples, from HIP basics to full applications |
 
If a component you're looking for isn't in its own repository anymore, it has most likely moved into `rocm-libraries` or `rocm-systems` under `projects/`. The [ROCm Core SDK component list](https://rocm.docs.amd.com/en/latest/components/core.html) maps every component to its current home.
 
## Getting builds
 
- **Released packages** — [installation guide](https://rocm.docs.amd.com/en/latest/install/rocm.html); packages are hosted at [repo.amd.com](https://repo.amd.com/rocm/)
- **Nightly and preview builds** — see [TheRock releases](https://github.com/ROCm/TheRock/blob/main/RELEASES.md) for prebuilt ROCm, PyTorch, and JAX packages, including multi-architecture builds
- **Release notes and history** — [latest release](https://rocm.docs.amd.com/en/latest/about/release-notes.html), [all versions](https://rocm.docs.amd.com/en/latest/release/versions.html)
 
## Getting help and contributing
 
- **Questions and general discussion** — [TheRock Discussions](https://github.com/ROCm/TheRock/discussions)
- **Bugs and feature requests** — [TheRock issues](https://github.com/ROCm/TheRock/issues)
- **Contributing** — [TheRock contribution guide](https://github.com/ROCm/TheRock/blob/main/CONTRIBUTING.md)
- **Security** — report suspected vulnerabilities through [AMD Product Security](https://www.amd.com/en/resources/product-security.html), not through public issues
- **Licensing** — most components are MIT or Apache-2.0; see [ROCm licenses](https://rocm.docs.amd.com/en/latest/about/license.html)
 
