# < eriwek's motto />

```rust
/// Gavin Wood's Quote
struct GavinWood;

impl GavinWood {
    /// Return Gavin Wood's quote
    fn said(&self) -> &str {
        "In software, we’re not constrained by physical reality; \
         the only limits are the limits of our own imagination."
    }
}

fn main() {
    let gavin_wood = GavinWood;
    println!("gavin wood - {}", gavin_wood.said());
}
```
