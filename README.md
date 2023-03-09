# system90

System90 is a (KISS, suckless) monitor terminal, booted on a tiny arduino as well as software for it, designed completely from the ground up, only with the goal to offer a truly good, selflessly designed computing tool for everyone to use, without any malicious features or characteristics (such as bloat, spyware, planned obsolescence, ads, DRM, intentional incompatibility, consumerist design, obscurity etc.).

It offer people an escape from the malicious technology (proprietary). It won't compete in computing power but it will win on the grounds of ethics and morals.

If we have a computer that's simple and cheap to manufacture, without any need of paying hardware and software license fees and without needing to comply with any conditions, anyone can start creating them and selling them for a price much cheaper than anything in the proprietary environment. We will make computing more accessible than ever, and we will make computers truly serve us all, not just their manufacturers.

## Objectives

- create a **simple ISA**, **instruction set architecture** (**NIA**):
  - 8bit, RISC, load-store register architecture
  - Uses Open or FreeBSD OS
  - simple, suckless, optimize for simplicity and low transistor count
  - should allow very simple hardware but also more powerful computers such as those we had in the 90s (so e.g. make it possible to address more memory if available)
  - create emulator in C, later rewrite in the project's languages to become independent
  - create a **CPU**, make logic-gate level description (for this create a simple logic-gate simulator), create the CPU emulator
  - create tests to be able to verify implementations
- specific language to be used: will make use of HolyC or Plancalculus.
    - TODO
  - simple **operating system**:
    - very simple, not a full-featured OS, just to eliminate some hardships of bare metal
    - no multitasking, no windowing systems, no users
    - allow easy loading of programs without resetting and reflashing and/or additional tools
    - abstract hardware
