# The Justin Steven Presentation for Cross-Site Scripters Who Can't Stack Buffer Overflow Good and Want to Do Other Stuff Good Too

CrikeyCon 3, 20 Feb 2016

## Abstract

 Did you miss out on stack-smashing for enjoyment and financial gain? Have you always meant to get in to "all that debugger stuff" but don't know your EIP from your ESP? Let's take it back to the 90s for an overview of Win32 stack buffer overflow exploitation.

 We'll cover assembly, registers, the stack, function call and return mechanics, triggering stack buffer overflows, taking advantage of saved return pointer overwrites, generating shellcode, and some other weird tricks (software devs hate him!)

 This is not new stuff, and modern mitigations (ASLR, DEP and stack canaries) totally harsh its mellow. If you're a stack savant who has a handle on the heap and ROPs relentlessly then I dunno go grab a beer or something.

 tl;dr pop calc not alert(1)

## Files

* dostackbufferoverflowgood - Visual Studio solution for dostackbufferoverflow.exe
* dostackbufferoverflowgood.exe - Intentionally vulnerable binary, compiled without ASLR, DEP or Stack Canaries
* dostackbufferoverflowgood.pdb - Debug symbols for the above
* dostackbufferoverflowgood_slides.pdf - Presentation slides
* dostackbufferoverflowgood_walkthrough.pdf - A (currently incomplete) guide/walkthrough for dostackbufferoverflowgood.exe
