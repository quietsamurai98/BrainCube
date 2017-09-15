# BrainCube
BrainCube is an esoteric programming language based on manipulating pointers to a shared cube of memory.

#### Why call it BrainCube?
The whole BrainCube language is based upon two core ideas:
 * The user may only use pointers to manipulate memory.   
     - This idea was influenced by the **brain**f\*\*k language, hence the "Brain" part of **Brain**Cube.
 * Pointers can move through memory in three dimensions.
     - What does that even mean?
       + In traditional languages like C and C++, a pointer can only move through memory horizontally, as if it were a line.  
       + However, in BrainCube, a pointer is able to move through memory horizonally, vertically, and normally<sup>[1](#normally-definition)</sup>, as if it were a **cube**, hence the "Cube"  part of Brain**Cube**.  
<sub><sup><a name="normally-definition">1</a>: In this context, normally means "along the axis normal to the plane formed by the horizontal and vertical axes."</sub></sup>
#### Why aren't there any code examples?
Quick answer: I am still in the process of writing the language specification.

Long winded answer: The first language that I wrote, MindMeld, was only a very slight modification to brainf\*\*k that added a second pointer. I probably specced it in under 5 minutes, given how simple the modification was. However, dispite the simplicity of the language, I still made design choices I wasn't happy with further down the road.  
This time around, I am going to spend some time writing a detailed language specification, which will be available on [the wiki](https://github.com/quietsamurai98/BrainCube/wiki).
