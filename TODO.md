pgp.rs/
├── Cargo.toml       # Rust project metadata and dependencies
├── src/
│   ├── main.rs      # CLI entry point, command-line argument parsing
│   ├── commands/
│   │   ├── encrypt.rs       # Encryption functionality
│   │   ├── decrypt.rs       # Decryption functionality
│   │   ├── sign.rs          # Signing functionality
│   │   ├── verify.rs        # Verification functionality
│   │   ├── keygen.rs        # Key generation & management
│   │   ├── export.rs        # Export keys
│   │   ├── import.rs        # Import keys
│   └── utils.rs             # Helper functions for common tasks
├── tests/                   # Integration tests for the project
│   ├── encrypt_test.rs      # Tests for encryption functionality
│   ├── sign_test.rs         # Tests for signing functionality
│   ├── keygen_test.rs       # Tests for key generation functionality
└── README.md                # Project documentation (usage, installation, etc.)
