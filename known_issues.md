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
    * [rust-lang #63484](https://github.com/rust-lang/rust/issues/63484): Profile overrides do not work for code using generics (such as nphysics) 
* [embark-rust-ecosystem #5](https://github.com/EmbarkStudios/rust-ecosystem/issues/5): More efficient runtime code generation for debug builds
 
## Iteration Times
* [embark-rust-ecosystem #13](https://github.com/EmbarkStudios/rust-ecosystem/issues/13): Dynamic libraries (dll/dylib) for fast iteration
* [embark-rust-ecosystem #11](https://github.com/EmbarkStudios/rust-ecosystem/issues/11): Distributed compilation for fast iteration
 
## Runtime Performance
* [embark-rust-ecosystem #2](https://github.com/EmbarkStudios/rust-ecosystem/issues/2): Fast fp math support
