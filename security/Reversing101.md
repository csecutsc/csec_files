Recommended Text: https://www.amazon.ca/Reversing-Secrets-Engineering-Eldad-Eilam/dp/0764574817
Recommended Text: http://ca.wiley.com/WileyCDA/WileyTitle/productCd-1118787315,subjectCd-CSJ0.html
Recommended WebCast: http://liveoverflow.com/binary_hacking/reverse_engineering.html

1. What is Reverse Engineering

- Investigating disassembled binary to unravel it's complete behaviour.

- Many propriety software will explicitly forbid the act

- Involves in-depth understanding of various architectures since machine code is machine specific

- Frustration redefined

- Need to be aware of compiler behaviours and optimizations

- Requires knowledge of advanced debugging techiniques

- Some advanced decompilers can guess at the original source

- Useful for analysing malicious code

- May be near impossible to achieve

 Resources:

  - Secrets of Reverse Engineering Chapt. 1

2. Executables

- ELF is to Linux as PE is to Windows

- Subtle differences in disassembled code

   Resources: 
   - This awesome course on Binaries http://opensecuritytraining.info/LifeOfBinaries.html

   - Secrets of Reverse Engineering Chapt. 3

   - Practical Reverse Engineering Chapt. 3

   - This awesome article on ELF http://www.skyfree.org/linux/references/ELF_Format.pdf

   - PE from Microsoft https://msdn.microsoft.com/en-us/library/ms809762.aspx

3. Before the dive (Recon)

- Before jumping on our debuggers and assembly cheatsheets, we need to do some reconnaissance to understand the task at hand. For all we know, the task at hand could be impossible or there's a simpler approach. Recon will reveal

- Linux (ELF) Recon:

- Windows (PE) Recon:

  Resources:

  - Secrets of Reversing Chapt. 6

4. Intro to Intel x86 I

- Introducing program space (text, data, stack, heap e.t.c) and registers

  Resources: 
  
  - This awesome FREE course on x86 http://opensecuritytraining.info/IntroX86.html

  - Practical Reverse Engineering Chapt 1

  - Secrets of Reverse Engineering Chapt 2

5. Intro to Intel x86 II

- Introducing instructions (mov, xor etc)

 Resources:

  - This awesome FREE course on x86 http://opensecuritytraining.info/IntroX86.html

  - IA32 quick reference https://www.cs.swarthmore.edu/~kwebb/cs31/s16/IA32_Cheat_Sheet.pdf

6.  Debuggers

- Know your adversary, pick your tools: radare2, Ollydbg, Windbg, gdb, edb, IDA Pro, etc

- Ideally, you'll master one of these tools especially platform independent tools. Are you more like the GUI or the commandline hacker ;-)

 Resources:

  - Secrets of Reversing Chapt. 4

  - Practical Reverse Engineering Chapt. 4
 
7. Anti-reverse/Binary Recon: Packed, stripped, strings e.t.c

  - Because people like you exist, closed source software developers must go the extra mile to protect proprietary intellectual material

 Resources:

  - Secrets of Reversing Chapt. 9 - 11
 
 
