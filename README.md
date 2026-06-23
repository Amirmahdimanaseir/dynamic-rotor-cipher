# Enigma Machine Simulator

## Overview

This project implements a simplified version of the historical Enigma Machine using Python.

The simulator reproduces the fundamental concepts of rotor-based encryption, including rotor substitution, reflection mechanisms, and rotor rotation after each character.

---

## Features

* Three independent rotors
* Random rotor generation
* Rotor state persistence
* Reflector mechanism
* Character-by-character encryption
* Rotor rotation after encryption
* Symmetric encryption concept

---

## How It Works

1. Three random rotors are generated.
2. Rotor states are saved using pickle.
3. Each character passes through:

   * Rotor 1
   * Rotor 2
   * Rotor 3
4. The reflector reverses the signal.
5. The signal travels back through the rotors.
6. Rotors rotate after each encrypted character.

---

## Technologies

* Python
* Random Module
* Pickle
* File Handling

---

## Project Structure

```text
enigma-machine/
│
├── rotor_generator.py
├── enigma.py
├── today_rotors_state_enigma
└── README.md
```

---

## Example

Plain Text:

```text
zqdafzfzqit
```

Cipher Text:

```text
encrypted_output
```

---

## Concepts Demonstrated

* Classical Cryptography
* Rotor-Based Encryption
* Reflection Systems
* State Machines
* Substitution Ciphers
* File Serialization

---

## Historical Background

The Enigma machine was an electro-mechanical cipher device used during World War II. Its rotating rotors produced a changing substitution cipher that made messages difficult to decrypt without the correct settings.

This project demonstrates the core principles behind rotor encryption systems.

---

## Skills Demonstrated

* Algorithm Design
* Cryptography Fundamentals
* State Management
* Python Programming
* File Serialization
* Data Transformation

---

## Future Improvements

* Plugboard implementation
* Rotor selection system
* Decryption mode
* Graphical user interface
* Historical rotor configurations
* Command-line interface
* Multiple reflector types

---

## Disclaimer

This project is an educational implementation of historical cryptographic concepts and should not be used for modern security purposes.
