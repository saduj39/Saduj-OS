# Saduj-OS
2021操作系统课程作业

周雪妍 2019141450132

## Source Structure

```
├─ main
│  .gitignore
│  README.md
├─ Lab_3
│  │  rust-toolchain
│  ├─ os
│  │  │  Cargo.toml[3.3增加两项依赖]
│  │  │  Makefile
│  │  ├─ .cargo
│  │  ├─ .idea
│  │  ├─ src
│  │  │  │  console.rs
│  │  │  │  entry.asm
│  │  │  │  linker.ld
│  │  │  │  main.rs
│  │  │  │  main.rs.0
│  │  │  │  panic.rs
│  │  │  │  sbi.rs
│  │  │  ├─ buddy_system_allocator
│  │  │  ├─ algorithm[3.3新增]
│  │  │  │  │  Cargol.toml
│  │  │  │  │  ├─ src
│  │  │  │  │  │  lib.rs
│  │  │  │  │  │  ├─ allocator
│  │  │  │  │  │  │  bitmap_vector_allocator.rs
│  │  │  │  │  │  │  mod.rs  stacked_allocator.rs
│  │  │  │  │  │  │  stacked_allocator.rs
│  │  │  ├─ memory
│  │  │  │  │  config.rs
│  │  │  │  │  mod.rs[3.3新增pub mod range&frame]
│  │  │  │  │  heap.rs
│  │  │  │  │  heap2.rs[3.3新增]
│  │  │  │  │  range.rs[3.3新增]
│  │  │  │  │  address.rs[3.3新增]
│  │  │  │  │  ├─ frame[3.3新增]
│  │  │  │  │  │  allocator.rs
│  │  │  │  │  │  frame_tracker.rs
│  │  │  │  │  │  mod.rs
│  │  │  ├─ interrput
│  │  │  ├─ riscv
│  │  ├─ target
​```
```

## Screenshots of the results

实验一结果截图：

![实验一结果截图.jpg](https://i.loli.net/2021/03/24/WPK5b1HqfN4A6GY.jpg)

实验二结果截图：

![实验二结果截图.jpg](https://i.loli.net/2021/03/24/P3tzir6jJ8GAfVY.jpg)

实验三（3.1 3.2 3.3)结果截图：

![实验三-1结果截图.jpg](https://i.loli.net/2021/04/06/NF2loqkQSnAadJR.jpg)

![实验三-2结果截图.jpg](https://i.loli.net/2021/04/08/decqmozaAukJGj5.jpg)

![实验三-3结果截图.jpg](https://i.loli.net/2021/04/08/OGa2NIcBq96ufSA.jpg)

