# Welcome

**Object Pascal**, (specifically [Free Pascal](https://www.freepascal.org/)) didn't vanish. It kept evolving. It's open source, still maintained, and still getting better:

- It produces fast native binaries, with no virtual machine or runtime, and modest memory use.
- It compiles in _seconds_ rather than minutes, so the edit-compile-test loop feels instant again.
- Targets almost everything from one machine: Windows, Linux, macOS, BSD, Android, ARM, microcontrollers, WebAssembly.
- It reads the way you think. begin and end, procedure and function, clearly declared types. It doesn't have the pseudocode-ness of Ruby, but it was designed for teaching, and it shows: the code shows intent before mechanics.
- It’s safer than its reputation suggests: range checking, reference-counted strings and dynamic arrays, strict typing, and you rarely need to do pointer arithmetic.
- Its concurrency is boring (and boring is good): threads, critical sections and queues. Stuff that fit in your head.
- AI already knows it and can write it.

I’m not saying Pascal is perfect. Its ecosystem is small, libraries are missing, and if you're writing something low-level then Rust or C may still the better tools. But most software is not a kernel, though. It’s web services, tools, desktop apps, and internal utilities. For that kind of work I'd rather have a language a person can actually read straight through.

The code of the future can be fast and portable and still be understandable. That's why I'm looking at Pascal again. You might want to take another look too.
