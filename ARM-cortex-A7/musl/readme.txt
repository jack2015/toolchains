:::::::::::::build_pc = x86_64 :::::::::::::::
CPU_TYPE:=cortex-a7
CPU_SUBTYPE:=neon-vfpv4

linux 4.1.49
musl 1.1.16
gcc 7.5.0

with-cpu = cortex-a7
with-fpu = neon-vfpv4
with-float = hard

with-mode = arm
little-endian
32-bit
