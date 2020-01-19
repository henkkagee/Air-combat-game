
# Review form for project Air Combat 3
**Names of reviewers:**
Jussi


## 1. Overall design and functionality (0-6p)
  * 1.1: The implementation corresponds to the selected topic and
scope. The extent of project is large enough to accommodate work for
everyone (2p)
The requirements were very well fulfilled in this project. 2p
  * 1.2: The software structure is appropriate, clear and well
documented. e.g. class structure is justified, inheritance used where
appropriate, information hiding is implemented as appropriate. (2p)
The structure is well done but somewhat broad, the classes could be split into smaller 
pieces to make the code easier to read & expand. 1.5p
  * 1.3: Use of external libraries is justified and well documented. (2p)
Well done, 2p

Total 5.5p


## 2. Working practices (0-6p)
  * 2.1: Git is used appropriately (e.g., commits are logical and
frequent enough, commit logs are descriptive). (2 p)
Git is used appropriately. However, seems like not all the work were actually 
merged into the master/demo branch in the end. However, this is somewhat 
typical in applications that are in development. 2p
  * 2.2: Work is distributed and organised well. Everyone contributes
to the project and has a relevant role that matches his/her skills.
The distribution of roles is described well enough. (2p)
Work is distributed well and clearly. 2p
  * 2.3: Quality assurance is appropriate. Implementation is tested
comprehensively and those testing principles are well documented. (2p)
System testing, no unit tests/memory testing. 0.5p

Total 4.5p

## 3. Implementation aspects (0-8p)
  * 3.1: Building the software is easy and well documented. CMake or
such tool is highly recommended. (2p)
Building the software failed first, but then worked after the 
Box2D was compiled locally. There was no instructions for building the 
Box2D library itself. The makefile is very rudimentary. 1p
  * 3.2: Memory management is robust, well-organised and
coherent. E.g., smart pointers are used where appropriate or RO3/5 is
followed. The memory management practices should be documented. (2p)
No memory problems in the end :) 1.5p
  * 3.3: C++ standard library is used where appropriate. For example,
containers are used instead of own solutions where it makes sense. (2p)
STL Containers are used appropriately, but there is a lot C-style coding 
that can be found. 1.5p
  * 3.4: Implementation works robustly also in exceptional
situations. E.g., functions can survive invalid inputs and exception
handling is used where appropriate. (2p)
There is some exception handling found, but the program didn't give any error 
when it tried to load massively too large map (because of integer length difference 
in Win32 and Linux64). The size should also have some 
sort of sanity check, so this kind of massive errors would not happen in the 
future. However, this bug was fixed post-deadline. 1p

Total 5p

## 4. Project extensiveness (0-10p)
  * Project contains features beyond the minimal requirements: Most of
the projects list additional features which can be implemented for
more points. Teams can also suggest their own custom features, though
they have to be in the scope of the project and approved by the course
assistant who is overseeing the project. (0-10p)
The project has a state-of-art physics implemented with different planes 
and levels. There is also multiplayer mode implemented.

Total 5p

## 4. Project plan (0-3p)
All good.

Total 3p

### Grand total 24 points