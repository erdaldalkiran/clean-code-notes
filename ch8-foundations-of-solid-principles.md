A source code smells if it is
* Rigid
* Fragile
* Immobile
* Viscous

and has needless complexity.

__Rigidity__ is the tendency of a system to be hard to change.
A system becomes rigid if it takes a long time do a build and a test. Also, if a
tiny force all system to a total rebuild.

A system is __fragile__ if a small change to a module causes other unrelated modules
misbehave.

A system is __immobile__ when its internal components cannot be easily extracted
and reused in new environments.

A system is __viscous__ when necessary operations like building and testing are
difficult to perform and take a long time to execute.

__Dependency Inversion__ is the key principle in OO design.
