# rust-tutorial

<https://doc.rust-lang.org/book/>

`rustup docs --book` for offline doc

`cargo new [directory name]` -- create cargo project with git files if the current directory is not in a git repo
`cargo new --vcs=git [directory name]` -- create cargo project with git files

`cargo build` to build the project and create exe in `./target/debug/project_name.exe` because default build is debug build

run it with `./target/debug/project_name.exe` or `cargo build`

`cargo check` to check code to make sure it compiles and does not produce exe

use `cargo check` to check if your code is compiling bcs its faster, when ready use `cargo build` to create an exe

use `cargo build --release` to compile the code that is ready for release with optimisation that makes the code run faster but compile time will be longer. it will create an exe in `./target/release/`

if benchmarking code running time, use `cargo build --release`

:: = associated function

i32 =  32-bit number, u32 = unsigned 32-bit number, i64 = 64-bit number