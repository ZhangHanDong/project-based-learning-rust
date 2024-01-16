


## no `clap`

```rust
use std::env;

fn main() {
    let args: Vec<String> = env::args().collect();

    // Access command line arguments
    if args.len() > 1 {
        let arg1 = &args[1];
        println!("Argument 1: {}", arg1);
    }
}
```