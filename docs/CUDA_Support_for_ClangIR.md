Client: Bruno Cardoso Lopes, Meta <bruno.cardoso@gmail.com>

The Clang C++ compiler is currently getting support for a new SSA-based
high-level IR representation, offering extra frontend knowledge to the
compiler for better analysis and optimizations. This new ClangIR is
implemented on top of MLIR and is currently in heavy development. It is
mainly focused on CPU support (ARM64, x86_64) but still lacks GPU code
generation support. Recently, OpenCL was added to the set of C/C++
compiler extensions supported by ClangIR, but many extensions (HLSL,
CUDA, etc.) are still missing. In this project, you will add CUDA
support to ClangIR, enabling GPU support for highly thought-after
application workloads such as AI and computational science.