# akireOS
Aiming to make a modern full monolithic UEFI x86_64 OS. This is not and is not going to be useful in any way.  
I'm the only maintainer, if you want to help, feel free to open a PR or discuss with me (find ways of contacting me on my website (link in my GitHub bio)).

## Getting started
Compile to an ISO image: `make all`
You will need: make, xorriso , a C cross-compiler (with a linker), git, curl
Run it directly in Qemu: `make run-uefi`
You will need everything above, plus qemu.

## Roadmap (super roughly)
- [ ] GDT
- [ ] IDT
- [ ] SIMD
- [ ] PMM 
- [ ] VMM
- [ ] Paging
- [ ] ACPI
- [ ] APIC
- [ ] IOAPIC
- [ ] LAPIC
- [ ] HPET
- [ ] APIC Timer
- [ ] SMP
- [ ] Multitasking
- [ ] Syscalls 
- [ ] Userspace
