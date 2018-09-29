# VIZIX
An operating system for fun

## Development Tools Required
- qemu
- nasm
- gcc 

PS: On Mac, Using homebrew: `brew install qemu nasm`

## Development Flow (Write an OS)
- Create Boot Sector
- 

## Registers:
- General Purpose Registers:
  - ax; Accumulator (EAX)
  - bx; Base (EBX)
  - cx; Counter (ECX)
  - dx; Data (EDX)
- Stack Registers:
  - bp; Base Pointer, Stores the base address of stack (EBP)
  - sp; Stack Pointer, Stores the top address of stack, sp gets decremented (ESP)
- Pointer Registers:
  - si; Source Index, (ESI)
  - di; Destination Index, (EDI)
  - ip; Instruction Pointer
- Segmentation: Obsolete memory protection technique
  - Segment Register: Can be altered using registers
   - cs; Code Segment; Can not be altered
   - ds; Data Segment
   - ss; Stack Segment
   - es; Extra Segment
   - fs, gs; General Purpose Segment
- Special Registers:
  - CR0,2,3
  - DR0,1,2,3,6,7
  - TR4,5,6,7


## Bootloaders:
- Geek Loading: Everything in Boot Record
- One-stage Loading
- Two-stage Loading: GRUB (GRand Unified Bootloader)



### References:
- Little OS Book - https://littleosbook.github.io/
- https://github.com/cfenollosa/os-tutorial
- http://www.cs.bham.ac.uk/%7Eexr/lectures/opsys/10_11/lectures/os-dev.pdf
- https://wiki.osdev.org/Main_Page
- http://stanislavs.org/helppc/idx_interrupt.html
- https://legacy.gitbook.com/book/samypesse/how-to-create-an-operating-system/details
- https://github.com/SamyPesse/How-to-Make-a-Computer-Operating-System
