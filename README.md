# Github Action for rustc_codegen_cranelift

If you're trying to reduce the build time in your Rust project, and you have read blog posts like [this one](https://endler.dev/2020/rust-compile-times/#cranelift-the-alternative-rust-compiler) by Matthias Endler, there's a chance that you are here to try using an alternative compiler that runs in parallel with rustc for every CI build: Cranelift, also called CG_CLIF.

Here is the [original post](https://jason-williams.co.uk/posts/a-possible-new-backend-for-rust/) by Jason Williams describing how `cg_clif` works.

This Github Action simply gives you an "interface" to use [this alternative compiler](https://github.com/bjorn3/rustc_codegen_cranelift) in other Actions you may have.

PRs are welcomed.
