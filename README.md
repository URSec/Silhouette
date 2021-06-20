# The Silhouette Project

## Brief Introduction
**Silhouette** is a compiler-based defense against code-reuse attacks on
embedded ARM systems that run a single bare-metal application.
It **guarantees** the integrity of all application return addresses and
also provides coarse-grained forward-edge control flow integrity.
We have only tested Silhouette on ARMv7-M processors, but we see no major
trouble porting Silhouette to other ARM M-profile processors.

For how Silhouette works, check out the [paper and conference
presentation](https://www.usenix.org/conference/usenixsecurity20/presentation/zhou-jie).

## Try Silhouette
The Silhouette compiler is at [another
repository](https://github.com/URSec/Silhouette-Compiler).
Please see the instructions in that repository to build it.  Alternatively,
you can try out the Silhouette prototype that we used at
[here](https://github.com/URSec/Silhouette-Evaluation).

## Legacy Code
The [legacy repository](https://github.com/URSec/Silhouette-Compiler-Legacy)
contains our development history of the Silhouette compiler.  As it is based on
the old LLVM repository and LLVM has migrated to a monolithic repository that
contains all subprojects in a single source tree, **we are no longer
maintaining it** but just leaving it there for the commit history.

## Contacts
Jie Zhou: jzhou41@cs.rochester.edu

Yufei Du: yufeidu@cs.unc.edu

Zhuojia Shen: zshen10@cs.rochester.edu

John Criswell: criswell@cs.rochester.edu

Robert J. Walls: rjwalls@wpi.edu
