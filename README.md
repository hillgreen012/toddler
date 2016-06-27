# Toddler

## Breif history of Toddler

Toddler was originally a half-hobby and half-research project developed during summer and winter breaks when I was in college.
The original Toddler was designed for small-scale multi-processor IA32 systems.
The most outstanding feature was the practical lock-free techniques used for syncronization.
However, it was overly designed for both hardware-related and regular OS components.
Then it finally became unpractical to continue the development.
The final Toddler was able to create and run user processes and threads, as well as accepting keyboard inputs,
though a shell was not implemented or ported.

The new Toddler, on the other hand, is designed with a completely different goal.
Alghough it is still a hobby project, it aims to provide a fully usable microkernel and a complete OS environment for multiple architectures and platforms.
The lock-free idea has been abandoned since it created too much unnecessary complexity.


## Architecture

## Ports

|Architecture|Bits|Platform|Status|
|---|---|---|---|---|
|ia32|32|NetBurst-based PC|Active|
|ppc32|32|Mac Mini G4, PowerMac G4|Initial|
|armv7|32|Raspberry Pi 2|Initial|
|mips32|32|MIPS 32|Planned|
|sparcv8|32|SuperSPARC II|Planned|
|m68k|32|M68K|No Plan|
|amd64|64|Skylake-based PC|Planned|
|ppc64|64|PowerMac G5|Planned|
|armv8|64|Raspberry Pi 3|Planned|
|mips64|64|MIPS 64|Planned|
|sparcv9|64|Sun UltraSPARC II Workstation|Planned|
|riscv|64|RISC V|Planned|
|ia64|64|Itaium 2|No Plan|
|alpha|64|ES40|No Plan|
|hppa|64|HP RA-RISC|No Plan|
|s390|64|S390|No Plan|
