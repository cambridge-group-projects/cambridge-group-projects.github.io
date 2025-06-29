Client: [MathWorks](MathWorks "wikilink")

Contact: Milos Puzovic Milos.Puzovic@mathworks.co.uk

## modified proposal

### [Unlocking the graphics power of the Raspberry Pi](Unlocking_the_graphics_power_of_the_Raspberry_Pi "wikilink")

The Raspberry Pi has become incredibly popular, and it's great for hobby
applications, but its appeal to children is reduced by the fact that
it's a little slow (for example, the Pi Edition of Minecraft doesn't
support mobile characters). However, most applications are using only a
fraction of its computational power. The good news is that the Raspberry
Pi's System-On-Chip BCM2835 has a hidden gem: a Graphics Processing Unit
(GPU) that can significantly improve performance of applications that
use large blocks of data. At the moment, the GPU on Raspberry Pi is
heavily underutilised. Your task is to enable applications written in
the MATLAB language to exploit the Raspberry Pi GPU. As a demonstration
of what can be achieved, it should be possible to implement high
performance game physics such as real time cloth dynamics on a human
character with moving clothes and hair (created using MATLAB Simulink
toolboxes). It's your choice whether this is a mobile character in a
sandbox game, a narrative cut-scene, or even an intelligent avatar such
as the Zoe talking head.

## added detail

Simulink has the built-in support for Raspberry Pi to build standalone
applications
(http://www.mathworks.com/hardware-support/raspberry-pi.html). This
support has enable access to various audio and video algorithms through
toolboxes such as DSP System Toolbox
(http://www.mathworks.com/products/dsp-system/) and Computer Vision
Toolbox (http://www.mathworks.com/products/computer-vision/).
Unfortunately, the code that is generated to run on the Raspberry Pi
only targets CPU and it does not make any use of GPU that is available
on the chip.

In order to be able to generate code that targets the GPU it would be
necessary to customize build process
(http://www.mathworks.com/help/rtw/ug/customizing-the-target-build-process-with-the-stf-make-rtw-hook-file.html).
Using the hooks provided by the Simulink Coder you would be able to
analyze the generated code and replace parts of the code with code that
can target VideoCore ISA
(https://github.com/hermanhermitage/videocoreiv/wiki/VideoCore-IV-Programmers-Manual).
There are various toolchains that can target VideoCore and students will
have an opportunity to evaluate them and decide which one would be the
best suitable for integration. The toolchains available are:

- vasm assembler (http://www.ibaug.de/vasm/vasm.tar.gz) and vcc compiler
  (http://www.ibaug.de/vbcc/vbcc_vc4.tar.gz)
- ACK compiler and toolchain
  (http://tack.hg.sourceforge.net:8000/hgroot/tack/tack)
- LLVM port (EXPERIMENTAL) - <https://github.com/phire/llvm>

To demonstrate the performance improvement the students would start with
one of simpler algorithms that can be found in image processing or
computer vision that are already implemented and available in Simulink.
Once they have demonstrated the improvement one part of the group could
implement an application in Simulink that adds real physics to the
gaming application such as cloth motion.

## original proposal

Raspberry Pi, the credit-card size computer, has unleashed an army of
children, hobbyists and professionals who have toyed with the computer
to make many interesting uses for it, from monitoring weather outside of
a shed to replacing old satellite navigation systems in the car. As many
more people are joining this new wave they will want to have access to
faster hardware. The good news is that Raspberry Piís System-On-Chip
BCM2835 has a secret gem in the form of a Graphics Processing Unit
(GPU), which can significantly improve performance of applications that
use large blocks of data. At the moment, the GPU on Raspberry Pi is
heavily underutilised. Your task is to enable applications written in
the MATLAB language to exploit Raspberry Piís GPU in order to maximise
the performance of the application. At the end of the project, you will
be able to demonstrate how applications that rely on computer graphics
execute faster with your project, opening up new possibilities for users
of Raspberry Pi.

[Category:Raspberry Pi](Category:Raspberry_Pi "wikilink")