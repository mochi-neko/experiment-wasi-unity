FROM rust:latest

RUN apt-get -y update

WORKDIR /wasm-compiler

COPY Cargo.toml .
COPY Cargo.lock .

RUN cargo install --path .