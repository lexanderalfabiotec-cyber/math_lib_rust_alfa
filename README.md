# math_lib_rust_alfa

A simple and efficient Rust math library providing basic arithmetic operations.

## Features

- **soma** - Addition operation
- **subtracao** - Subtraction operation  
- **multiplicacao** - Multiplication operation
- **divisao** - Division operation

## Installation

Add this to your `Cargo.toml`:

```toml
[dependencies]
math_lib_rust_alfa = "0.1"
```

## Usage

```rust
use math_lib_rust_alfa::{soma, subtracao, multiplicacao, divisao};

fn main() {
    let result = soma(5, 3);
    println!("5 + 3 = {}", result); // Output: 5 + 3 = 8
    
    let result = subtracao(10, 4);
    println!("10 - 4 = {}", result); // Output: 10 - 4 = 6
    
    let result = multiplicacao(6, 7);
    println!("6 * 7 = {}", result); // Output: 6 * 7 = 42
    
    let result = divisao(20, 4);
    println!("20 / 4 = {}", result); // Output: 20 / 4 = 5
}
```

## License

This project is dual-licensed under either of:

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.
