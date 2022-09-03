### structure command tree for making project easier:

- 513 vi public/index.html
- 514 vi package.json
- 515 npm run dev
- 519 cargo init --lib .
- 520 vi Cargo.toml
- 521 cargo build
- 522 rustup target add wasm32-unknown-unknown
- 523 vi src/lib.rs
- 524 cargo build --target wasm32-unknown-unknown
- 526 cargo install -f wasm-bindgen-cli
- 527 wasm-bindgen target/wasm32-unknown-unknown/debug/new_1.wasm --out-dir build
- 528 vi package.json
- 529 npm i -D @wasm-tool/wasm-pack-plugin
- 530 vi webpack.config.js
- 531 npm run build
- 532 vi src/index.jsx
- 533 npm run dev
