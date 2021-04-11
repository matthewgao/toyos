# toyos
a toy os

# env

```
rustup override add nightly
rustup override set nightly
rustup component add llvm-tools-preview
cargo install bootimage
```

# build
```
cargo build
cargo bootimage
```

# run

```
qemu-system-x86_64 -drive format=raw,file=bootimage-rustos.bin
```