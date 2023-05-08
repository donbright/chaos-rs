# Chaos-RS - a port of James Gleick's CHAOS: The Software

This is a work-in-progress port of the free release of James Gleick's 
CHAOS, December 15, 1998. The original software was written by Josh 
Gordon, Rudy Rucker and John Walker for Autodesk, Inc. Rucker wrote most 
of the algorithm, except for the Fractal Landscapes algorithms, which 
are by John Walker. Gordon did the interface, and much of the 
implementation of the algorithm code.

The original program was written in consultation with James Gleick about 
his brilliant book, <a href="https://around.com/books/"> <i>Chaos: 
Making a New Science</i> </a>. This port is under a Gnu license, same as 
the original release.

The software was originally released by Autodesk, Inc., in 1991, and was 
placed in copyright to Autodesk at that time.  When the product went out 
of print in about 1992, Autodesk transferred intellectual property 
rights for the product to James Gleick.  Gleick agrees that the software 
can be freely released under a Gnu license.

The original code was DOS and assembly code, using Borland's legendary 
Turbo C and Turbo Assembler.

This port is written in Rust, for Linux.

# What's In Chaos-RS

CHAOS-RS has six modules.

MANDEL. A <i>Mandelbrot Set</i> program, incorporating: quadratic and 
cubic Julia sets, quadratic and cubic Mandelbrot sets, and a gnarly 
cubic connectedness map called the <a 
href="http://tinyurl.com/rudyfractals">Rudy set</a>.

MAGNETS. A <i>Pendulum and Magnets</i> program showing chaotic physical 
motion and fractal basins of attraction.

ATTRACT. A <i>Strange Attractors</i> program showing the Lorenz 
 Attractor, the Logistic Map, the Yorke Attractors, and the Henon 
 Attractors.

GAME. A <i>Barnsley Fractals</i> program showing Iterated Function 
 System fractals such as the famous fractal fern.

FORGE. A <i>Fractal Forgeries</i> program that shows clouds, maps, 
 mountain ranges, and planets based on random fractals.

TOY. A Toy Universes program that shows <i>cellular automata</i>.
