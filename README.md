# Task: Greeting Program with Current Time

## Overview

This project contains two small programs that print a greeting message along with the current time:
1. **Rust Program**: Prints a personalized greeting with the current time using the `chrono` crate.
2. **PHP Program**: Outputs the same message using PHP's built-in date functionality.

## Files Included

- `main.rs`: Rust source file for printing the greeting and time.
- `greeting.php`: PHP script for printing the greeting and time.

## Requirements

### Rust Program
- Rust and Cargo installed.
- Add `chrono` crate as a dependency in your `Cargo.toml`:
    ```toml
    [dependencies]
    chrono = "0.4"
    ```

### PHP Program
- PHP installed.
- Modify the timezone in the PHP script if required.

## Usage

### Rust Program
1. Compile the Rust program using:
    ```bash
    cargo build
    ```
2. Run the program:
    ```bash
    cargo run
    ```

### PHP Program
1. Run the PHP script using the following command:
    ```bash
   <?php
   date_default_timezone_set('Asia/Kolkata');
   echo "Hello Saira S Elizabeth, right now the time is " . date('Y-m-d H:i:s');
    ?>
    ```
2. Save file program
```bash
hello.php
```
## Output

Both programs will output:
Hello Saira S Elizabeth,right now the time is 18:30:25
