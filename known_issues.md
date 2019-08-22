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
* https://github.com/rust-gamedev/wg/issues/20 - Map/Set in .natvis files
* https://github.com/rust-gamedev/wg/issues/22 - RLS for huge projects
* https://github.com/EmbarkStudios/rust-ecosystem/issues/8 - RLS in VS Code robustness & performance
* https://github.com/EmbarkStudios/rust-ecosystem/issues/9 - Better debugger experience in VS Code
 
## Debug Performance
* https://github.com/rust-gamedev/wg/issues/32 - Selective Enabling/Disabling optimizations at a crate/file/function level
    * Profile overrides do not work for code using generics (such as nphysics) https://github.com/rust-lang/rust/issues/63484
* https://github.com/EmbarkStudios/rust-ecosystem/issues/5 - More efficient runtime code generation for debug builds
 
## Iteration Times
* https://github.com/EmbarkStudios/rust-ecosystem/issues/13 - Dynamic libraries (dll/dylib) for fast iteration
* https://github.com/EmbarkStudios/rust-ecosystem/issues/11 - Distributed compilation for fast iteration
 
## Runtime Performance
* https://github.com/EmbarkStudios/rust-ecosystem/issues/2 - fast math support
