# Papyrus API
Blazing fast fuzzy search for the Bible. Check it out here: http://papyrusapp.net/

## Requirements
`rustc` & `cargo` which can be installed following these [instructions]

## Getting Started
Run `cargo run`. This will build and run the application listening on port `3000`

Make a request to `/bible?query={YOUR SEARCH}` to get back matches as `.json`.

## Goals
1. Create the fastest Fuzzy search for the Bible
2. Learn rust
3. Learn about how computers actually work

## Road Map
- [x] Create working server with single translation
- [x] Build a frontend
- [x] Handle errors
- [ ] Add more translations

[instructions]: https://doc.rust-lang.org/cargo/getting-started/installation.html
[rust]: https://www.rust-lang.org/
