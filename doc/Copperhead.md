# Project Copperhead

Generate a portable app using Swagger spec files.
Provide builds for: native (osx/linux/min), wasm, nodejs, FFI interop.

## CLI

// CLI Tools to do things like generate a Rust CLAP CLI from a Swagger/OpenApi spec file (json/yaml)
copperhead --help
copperhead project new --json_spec <base64> --yaml_spec <base64> // either json _or_ yaml is required.

## App

Consume the generated CLAP CLI definition from the CLI tool. 

# Utils

