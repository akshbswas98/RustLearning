# 🦀 RustLearning

Practice repo for **[Rust Course 2026 – Complete Rust Programming for Beginners](https://www.youtube.com/watch?v=tS1PFlTmpuU&t=149s)** — a zero-to-project crash course by [Codynn](https://www.youtube.com/@codynn-org) covering Rust fundamentals, memory safety, and backend development with Axum.

![toolchain](https://img.shields.io/badge/toolchain-stable-informational?logo=rust&logoColor=white)
![edition](https://img.shields.io/badge/edition-2024-blue)
![course](https://img.shields.io/badge/course-Rust%20Course%202026-important?logo=youtube&logoColor=white&link=https://www.youtube.com/watch?v=tS1PFlTmpuU)
![status](https://img.shields.io/badge/status-in%20progress-yellow)

---

## 📚 Course Roadmap

Tick the boxes as you work through each section — the checklists live in the README so progress is tracked right in the repo.

### 🚀 Prelude — Setup [0h00m](https://www.youtube.com/watch?v=tS1PFlTmpuU&t=0s)
- [ ] Install the toolchain (rustup adds `rustc`, `cargo`, `rustup`)
- [ ] Verify with `rustc --version` and `cargo --version`
- [ ] Run this project with `cargo run`

### 1️⃣ Fundamentals — variables, types, functions, control flow
- [ ] Variables & immutability (`let`, `mut`, `const`)
- [ ] Scalar & compound types (`i32`, `f64`, `bool`, `char`, tuples, arrays)
- [ ] Functions & expressions vs. statements
- [ ] Control flow: `if`/`else`, `loop`, `while`, `for`
- [ ] `println!` formatting (`{}`, `{:?}`, positional args) — see `src/main.rs`

### 2️⃣ Memory Safety — ownership, borrowing & lifetimes
- [ ] Ownership rules & moves
- [ ] References & the borrow checker
- [ ] Slices (`&str`, `&[T]`)
- [ ] Lifetimes (basic annotations)
- [ ] Common borrow-checker pitfalls & fixes

### 3️⃣ Structs, Enums & Pattern Matching
- [ ] Defining & instantiating `struct`s (incl. tuple & unit structs)
- [ ] `impl` blocks & methods
- [ ] Enums & associated data
- [ ] `match` & `if let`

### 4️⃣ Error Handling — `Option<T>` & `Result<T, E>`
- [ ] `Option` for absent values
- [ ] `Result` for fallible operations
- [ ] `?` operator, `unwrap`, `expect`
- [ ] Custom error types with `impl Display`/`Error`

### 5️⃣ Project — Backend API with Axum
- [ ] `cargo new` a server crate; add `axum`, `tokio`
- [ ] First route + `#[tokio::main]`
- [ ] Path, query & JSON body extraction
- [ ] State & shared application state
- [ ] Error responses with proper status codes

### 6️⃣ Beyond the Course — where Rust goes
- [ ] Systems programming use cases
- [ ] Blockchain/Solana (Anchor) ecosystem
- [ ] Rust careers & learning paths afterwards

---

## 🗂 Project Structure

```
RustLearning/
├── Cargo.toml        # package metadata & dependencies
├── Cargo.lock        # locked dependency graph
└── src/
    └── main.rs       # course exercises & experiments
```

---

## 🚀 Getting Started

```sh
# 1. Install Rust (skips if you already have a toolchain)
rustup-init   # or: winget install Rustlang.Rustup

# 2. Run the project
cargo run
```

---

## 🔗 Useful Links

- 📺 [Course video](https://www.youtube.com/watch?v=tS1PFlTmpuU&t=149s) (time-stamped to where this repo picks up)
- 📖 [The Rust Programming Language (the book)](https://doc.rust-lang.org/book/)
- 🧰 [Rust Playground](https://play.rust-lang.org/)

---

*Progress & code in this repo are tracked as I follow the course.*