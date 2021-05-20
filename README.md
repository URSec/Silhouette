# The Silhouette Project

## Brief Introduction
**Silhouette** is a compiler-based defense against code-reuse attacks on
embedded ARM systems that run a single bare-metal application.
It **guarantees** the integrity of all application return addresses and
also provides coarse-grained forward-edge control flow integrity.
We have only tested for ARMv7M processors, but we see no major
trouble porting Silhouette to other ARM M-serious processors.

For how Silhouette works, check out the [paper and conference
presentation](https://www.usenix.org/conference/usenixsecurity20/presentation/zhou-jie).

## Try Silhouette
The Silhouette compiler is at another [repo](https://github.com/URSec/Silhouette-Compiler).
Please see the instructions in the compiler repo to build it.

## Others
The [miscellaneous scripts and docs](https://github.com/URSec/silhouette-misc)
we used during developing this project.


## Contacts
Jie Zhou: jzhou41@cs.rochester.edu

Yufei Du: yufeidu@cs.unc.edu

Zhuojia Shen: zshen10@cs.rochester.edu

John Criswell: criswell@cs.rochester.edu
