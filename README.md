# Datalocker

Use it to easily encrypt/decrypt csv files.

## Getting started

1. `git clone https://github.com/insaiyancvk/OOPminiProject.git`

2. `cd OOPminiProject`

To encrypt a file:
```
python dlocker.py  -e dummy.csv --save-as encrypted.csv --key 1234
```

To decrypt a file:
```
python dlocker.py  -d encrypted.csv --save-as decrypted.csv --key 1234
```

For help:
```
python dlocker.py --help
```
