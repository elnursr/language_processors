# Language Processors[CPU]  (Dil Prosessorlari)
### Dil prosessoru high-level programlashdirma dillerinde yazilan kodlari machine diline cheviren bir programdir. Bu dil programlarin inkishaf etdirilmesi ve run edilmesinde chox onemlidir. Belelikle dil prosessorunun novleri ashagidakilardir:
---
1. Compilers
   * Funksiyasi: High-level programlashdirma dilinde yazilan kodu machine code-a ve ya intermediate code-a chevirir.
   * Example: GCC(GNU Compiler Collection) for C/C++
---
2. Interpreters
   * Funksiyasi: Elave bir run edilecek file yaratmadan code-u seti-setir oxuyur ve run edir.
   * Example: JavaScript, Python
---
3. Assemblers
   * Funksiyasi: Assembly dili code-nu machine code-na chevirir.
   * Example: NASM (Netwide Assembler)
---
4. Hybrid
   * Funksiyasi: Bu dil prosessoru programlarin run edilmesini optimizasiya etmek uchun *compiler* ve *interpreters* dilin xususiyyetleirni ozunde birleshdirir.
   * Example: 
     * Java => Java Virtual Machine (JVM) 
     * C# => Common Language Runtime (CLR)
     * Python => PyPy Just-In-Time (JIT)