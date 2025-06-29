Client: Martin Erhart, SiFive <martin.erhart@sifive.com>

CIRCT recently introduced an open software stack for hardware design,
which SiFive has used to build and ship production RISC-V chips.
Understanding how hardware designs are optimised and translated to a
physical layout is difficult due to the overwhelming amount of data. In
this project, you will build a visual data analytics tool that helps
hardware compiler engineers analyse the lowering process in detail. We
propose to connect the open-source CIRCT (circt.llvm.org) EDA stack with
the recently released Google Model Explorer
(https://github.com/google-ai-edge/model-explorer) and augment the
product with CIRCT-specific interactive analyses, as well as
bi-directional analysis-transformations that allow to visualise and
influence the compilation process. If successful, your tool will make a
complex compilation process visually accessible to a broad community.