#############################################Project Janus: A manifesto#############################################

The device in your hand is not your own. It is a rented space, governed by rules you did not write and locked by keys you did not hold.
For years, we have fought for administrative control, for root, by playing a game on a board designed by the gatekeepers. Exploits,
patched. System modification, detected. Our hiding places, discovered. This is the endless cat-and-mouse game, and it is a game we were
never meant to win, because we are playing on their turf. 

Why fight the landlord, when we can build a new house.

Project Janus is the declaration that this game is over. We are not creating a new key to the same locked room. We are changing the 
architecture of the building itself. We are moving the battleground from the user space  and the kernel to the one place of absolute
authority: the hypervisor

This is not an exploit. It is a fundamental inversion of control. We do not seek to hide within Android; we seek to run Android
as a guest within a system of our own making. The operating system, with all its checks and attestations, becomes a partition, an 
island under our watch. Our tools are not scattered across its filesystem, waiting to be found; they reside in an adjacent space,
invisible and untouchable, wielding true authority.



We hold to these principles:

1- Control Through Isolation, Not Intrusion. 
True power does not come from modifying the system, but from isolating it. By placing the Android OS into a virtual machine, we observe 
and command it from a higher privilege level. Its most sophisticated defenses are rendered blind, for they cannot see beyond the walls 
of their own virtualized space.

2- Stealth by Design, Not by Obfuscation.
Current root-hiding techniques are a fragile arms race of cloaking and detection. Project Janus achieves stealth not by hiding, but by 
being architecturally absent. A security check cannot find what is not there. We do not alter the system's files; we mediate the system's
access to the hardware itself.

3- Resilience Through Foundation.
We do not build on fleeting software bugs that are patched with the next security update. We build upon 
the very foundation the manufacturer provides: the hypervisor. We use the tools they are building for their own future, the Android 
Virtualization Framework, to secure our own. They cannot patch away KVM without destroying their own platform. Our foundation is the rock
upon which their house is built.

4- Persistence Through Independence.
An OTA update can wipe away traditional root methods because they are intrinsically part of the system being updated. Project Janus 
is designed for persistence because it exists outside that system. The guest can be updated, modified, or even broken, but the control 
layer, the Janus service, remains.

5- Freedom Through Community.
This is not a tool to be hoarded, but a concept to be shared. The final phases of this project require the expertise of a community that 
believes in true device ownership. From kernel specialists to security researchers, every contribution builds a new floor on this 
foundation. Like Magisk and KernelSU before it, this project belongs to those who build and use it.

Project Janus is more than a new way to achieve root. It is a philosophical shift. It is the end of asking for permission and the 
beginning of asserting control. We are no longer guests on our own devices.

We are the hypervisor. We are the host. We are the foundation.

Join us.
