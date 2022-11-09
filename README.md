# Building a Fibonacci Circuit with Halo2

This is an attempt to build a circuit to verify Fibonacci series following 0xParc's halo2 Learning Group [Video](https://www.youtube.com/watch?v=vGQAMQRlN3E).

Build

``` script
cargo build
```

Run

``` script
cargo test -- --nocapture test_example1
```

Output the Circuit Layout to a PNG file

``` script
cargo test --all-features -- --nocapture plot_fibo1
```
