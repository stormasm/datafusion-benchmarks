# datafusion-benchmarks

This is a fork of [the datafusion benchmarks directory](https://github.com/apache/arrow-datafusion/tree/main/benchmarks)

Step One : You must first generate out a copy of the *benchmarks/data* folder

To run the tpch commands enter the following command in the benchmarks folder...

```rust
./bench.sh run tpch
./bench.sh run tpch_mem
./bench.sh run sort
./bench.sh run parquet
```

```rust
cargo run --bin tpch benchmark datafusion --path "/Users/ma/j/tmp09/datafusion-benchmarks/benchmarks/data"
```

```rust
cargo run --bin tpch benchmark datafusion --path "/Users/ma/j/tmp09/datafusion-benchmarks/benchmarks/data" --query 4
```
