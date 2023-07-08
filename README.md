## cargo-err-bin

# Attempt to Reproduce Error in cargo check

Steps:

1. Create repository at [https://github.com/JesseGlick/cargo-err-lib].
2. Clone cargo-err-lib to local machine.
3. Run `cargo init --lib` in cloned repository cargo-err-lib.
4. Commit all changes in cargo-err-lib and push to Github.
5. Create repository at [https://github.com/JesseGlick/cargo-err-bin].
6. Clone cargo-err-bin to local machine.
7. Run `cargo init` in cloned repository cargo-err-bin.
8. Update README with steps performed.
9. Commit all changes in cargo-err-bin and push to Github.
10. Run `cargo add cargo-err-lib --git "https://github.com/jesseglick/cargo-err-lib"` in cargo-err-bin.
11. Note that Cargo.lock references commit "#8b2df1a86905641a5661cab2a64e170a893f3734" of cargo-err-lib.
12. Update README with steps performed.
13. Commit all changes in cargo-err-bin and push to GitHub.