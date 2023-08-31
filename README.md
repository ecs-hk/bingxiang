# bingxiang

Symmetric file encryption using openssl

## Setup

After cloning the repository:

```bash
sudo cp bingxiang /usr/local/bin
```

```bash
sudo chmod 755 /usr/local/bin/bingxiang
```

## Usage

The following will prompt for encryption password, and then save encrypted file as `foo.txt.bbxxa`:

```bash
bingxiang lock /tmp/foo.txt
```

The following will prompt for decryption password, and then save plain text file as `foo.txt`:

```bash
bingxiang unlock foo.txt.bbxxa
```
