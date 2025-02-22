# pgp.rs

## Batch Encrypting Multiple Files

The PGP tool now supports batch encrypting multiple files in one operation. You can specify a directory or a list of files to encrypt at once.

### Usage

To encrypt multiple files, use the following command:

```sh
pgp_tool encrypt --files file1.txt file2.txt --output /path/to/output --key your_pgp_key
```

Or, to encrypt all files in a directory:

```sh
pgp_tool encrypt --files /path/to/directory/* --output /path/to/output --key your_pgp_key
```

## Batch Signing Multiple Files

The PGP tool now supports batch signing multiple files in one operation. You can specify a directory or a list of files to sign at once.

### Usage

To sign multiple files, use the following command:

```sh
pgp_tool sign --files file1.txt file2.txt --output /path/to/output --key your_pgp_key
```

Or, to sign all files in a directory:

```sh
pgp_tool sign --files /path/to/directory/* --output /path/to/output --key your_pgp_key
```
