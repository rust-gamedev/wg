# Known Issues

One of the goals of this working group is to improve the user experience of people using rust for game development.

**This document tracks issues that we as a group would like to raise for the core Rust language team.** This may
include missing functionality, or problems that impede productivity. This is not an exhaustive list, and only 
includes language-level issues. 

If you feel that something should be added to this list:
 * Please open an issue on this or another repository so that we can link to it
 * Submit a PR to this document

If you're not sure, just open an issue in this repo. We're happy to help!

## IDE/Debugging Experience
* [wg #20](https://github.com/rust-gamedev/wg/issues/20): Map/Set in .natvis files
* [wg #22](https://github.com/rust-gamedev/wg/issues/22): RLS for huge projects
* [embark-rust-ecosystem #8](https://github.com/EmbarkStudios/rust-ecosystem/issues/8): RLS in VS Code robustness & performance
* [embark-rust-ecosystem #9](https://github.com/EmbarkStudios/rust-ecosystem/issues/9): Better debugger experience in VS Code
 
## Debug Performance
* [wg #32](https://github.com/rust-gamedev/wg/issues/32): Selective Enabling/Disabling optimizations at a crate/file/function level
    * This is due to hit stable in 1.41, but there are caveats for code using generics (see 
      [rust-lang #63484](https://github.com/rust-lang/rust/issues/63484))
* [embark-rust-ecosystem #5](https://github.com/EmbarkStudios/rust-ecosystem/issues/5): More efficient runtime code generation for debug builds
 
## Iteration Times
* [embark-rust-ecosystem #13](https://github.com/EmbarkStudios/rust-ecosystem/issues/13): Dynamic libraries (dll/dylib) for fast iteration
* [embark-rust-ecosystem #11](https://github.com/EmbarkStudios/rust-ecosystem/issues/11): Distributed compilation for fast iteration
* [wg #50](https://github.com/rust-gamedev/wg/issues/50): The linker in the default windows toolchain is very slow
    * Workaround: LLD can be used a drop-in replacement in many cases, see [wg #50](https://github.com/rust-gamedev/wg/issues/50) for more info
 
## Runtime Performance
* [embark-rust-ecosystem #2](https://github.com/EmbarkStudios/rust-ecosystem/issues/2): Support for fast fp math
* [wg #49](https://github.com/rust-gamedev/wg/issues/49): Support for branch prediction hints

## Memory Management
* [wg #60](https://github.com/rust-gamedev/wg/issues/60): Custom allocator support in standard library
    * More broadly, we are concerned that not having a standard way to specify custom allocators could can cause 
      fragmentation in the Rust library ecosystem
    * [wg #47](https://github.com/rust-gamedev/wg/issues/47): From a practical standpoint this also discourages use of
      multiple heaps, a standard practice in the games industry
* [wg #48](https://github.com/rust-gamedev/wg/issues/48): There is currently no equivalent to placement new
