# Rust API Using Hyper
This is an example of how to build a Rust API using [Hyper](https://crates.io/crates/hyper) with [Tokio](https://crates.io/crates/tokio), to generate a simple API containing the following endpoints
- GET /cars = to fetch all cars
- GET /cars/:id = to fetch a specific car
- POST /cars = to create a new car

The car records are not stored in a database but rather in memory as the main reason of this project is for explanation purposes. If you need a thorough explanation, check out the article https://www.becomebetterprogrammer.com/rust-api-using-hyper/.

## Requirements
This example codebase uses Rust programming langauge. Hence, you must have Rust properly installed in your machine if you want to run the code.

Refer to https://www.rust-lang.org/tools/install to setup Rust in your local machine.

## Do you want to run the code?
Clone this repo to your local machine. Open the terminal and run the command `cargo run` command.
