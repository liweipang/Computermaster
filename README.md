# RSA Web Application

An interactive client-side web application that demonstrates RSA key generation, encryption, decryption, and verification step by step.

## Features

- User-defined RSA parameters `p`, `q`, and `e`
- Prime-number and parameter validation
- RSA key generation
- Numeric plaintext encryption and decryption
- Text plaintext support through character-code conversion
- Step-by-step output for the full RSA workflow
- Runs entirely in the browser with no backend or external cryptography library

## Technologies

- HTML
- CSS
- JavaScript
- BigInt
- Public-Key Cryptography

## How to Run

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Enter RSA parameters and either numeric or text plaintext.
4. Click **Run RSA**.

Example parameters:

- `p = 61`
- `q = 53`
- `e = 17`
- Text plaintext: `HELLO`

## Implementation Notes

The application implements core RSA calculations directly in JavaScript, including:

- Greatest common divisor
- Extended Euclidean Algorithm
- Modular inverse
- Fast modular exponentiation
- Simple primality validation for demonstration inputs

## Educational Scope

This project is designed for learning and demonstration rather than production security.

Limitations include:

- Small prime numbers are used for demonstration
- No OAEP or other modern padding scheme is implemented
- Text is encrypted character by character
- The implementation is not intended for real-world secure communication

## Project Context

Developed as an academic project to provide a transparent, browser-based demonstration of the RSA public-key cryptosystem.
