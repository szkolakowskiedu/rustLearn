you need to install rust along with:  
```
sudo apt install build-essential  
```
cargo - better structure, listing all of the dependencies (especially useful in bigger projects)  
```
cargo new project-name
cd project-name
cargo build *compiles program*
./target/debug/project-name
cargo run *compiles and runs the program*
cargo check *checks if program has no errors*
```
rustfmt - automatically formats rust code  
```
rustfmt path-to-file
```

