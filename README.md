# KPL_compiler
* These are 4 file:
  * KPL: the compiler, use in final test (written by Prof.)
  * interpreter: the virtual machine for running binary created by KPL(written by Prof.)
  * stack_machine_compiler: create binary from stack machine assembly. 
  * vm_exploit: vm has a bug, so well, exploit it. Turn out quite easy.
<pre>
  python exploit.py > asm #create asm file
  smc asm binary
  echo "/bin/sh" >> binary # or any command U want
  kplrun binary #pwn
</pre>
