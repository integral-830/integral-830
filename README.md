```rust
pub struct Dev {
use std::fmt::Display;

struct Dev<'a, T: Display> {
    name: &'a str,
    role: Option<&'a str>,
    langs: [&'a str; 4],
    _m: std::marker::PhantomData<T>,
}

fn main() {
    let d: Dev<i32> = Dev {
        name: "Ayush Verma",
        role: Some("Web3 Dev"),
        langs: ["🟦 Solidity","🦀 Rust","⚡ TS","Kotlin"],
        _m: std::marker::PhantomData,
    };
}
```

- 🔗 I’m currently into blockchain.

### Things I code with

![TypeScript](https://img.shields.io/badge/-TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Web3](https://img.shields.io/badge/-Web3-3C3C3D?style=flat-square&logo=web3dotjs&logoColor=white)
![Solana](https://img.shields.io/badge/Solana-9945FF?logo=solana&logoColor=fff)
![Web3.js](https://img.shields.io/badge/-Web3.js-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61dafb?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-06b6d4?style=flat-square&logo=tailwind-css&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DD0031.svg?logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?logo=neovim&logoColor=fff)
![Arch Linux](https://img.shields.io/badge/Arch%20Linux-1793D1?logo=arch-linux&logoColor=fff)
![Kotlin](https://img.shields.io/badge/Kotlin-%237F52FF.svg?logo=kotlin&logoColor=white)

### Where to find me

[![Gmail](https://img.shields.io/badge/-Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:andy.ayushverma@gmail.com)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/_integral_30)
