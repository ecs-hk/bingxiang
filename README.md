# bingxiang

Symmetric file encryption using openssl

## Setup

After cloning the repository:

```bash
$ sudo cp bingxiang /usr/local/bin
$ sudo chmod 755 /usr/local/bin/bingxiang
```

## Usage

```bash
$ bingxiang lock /tmp/foo.txt
enter aes-256-cbc encryption password:
Verifying - enter aes-256-cbc encryption password:
Encrypted output file is foo.txt.bbxxa
```

```bash
$ bingxiang unlock foo.txt.bbxxa
enter aes-256-cbc decryption password:
Decrypted output file is foo.txt
```
