# btcde-passfile-reader

A python script for parsing a pdf file consisting of passwords provided by [Bitcoin.de](https://www.bitcoin.de) when enabled the two-factor authentication over a hashed password table.

## Requirements

* Python 2.7 or Python 3
* PyPDF2 (`pip install pypdf2`)

## Usage

### Python 3.x

```
> btcde_validate.py
```

### Python 2.7

```
> btcde_validate2.py
```

### Example usage (commandline):

```
> btcde_validate.py
> Code: B6 D2 A3 N8   <= Code received after logging in
> k p * 7             <= Answer code to be passed back to bitcoin.de
```

Tested on Windows 7 and further.
