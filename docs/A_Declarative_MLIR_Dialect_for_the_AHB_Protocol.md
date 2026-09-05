
Client: Moritz Scherer <moritz@mosaic-soc.com>

The AHB Protocol is a widely used protocol in digital hardware design to connect endpoints and enable on-chip communication.

The core design objectives of on-chip interconnects, correctness of routing, is statically verifiable; however there exists no standard representation of AHB interconnects, which makes the description of hardware IP integration requirements between IP vendors difficult. 

The goal of this project is to develop an MLIR dialect similar to AXI4 in CIRCT, with the ambition of generating checkable, correct interconnects from standardised AHB IR components.
