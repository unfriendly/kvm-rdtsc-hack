# KVM RDTSC timer stabilizer

This project aims to stabilize and minimize the perceived time difference of 2 RDTSC calls and a vmexit (cpuid specifically) in programs running inside a KVM virtual machine.
