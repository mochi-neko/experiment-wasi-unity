FROM rust:latest

RUN apt-get -y update

WORKDIR /wasm

RUN cargo install wasmer-cli --features compiler,cranelift,singlepass