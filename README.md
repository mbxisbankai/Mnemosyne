# Mnemosyne
## About
Mnemosyne is a payload encryptor that encrypts payloads using keys generated by the xor function.

This encryption works like a charm in AV Evasion.

## How to install it
### 🔴 Clone this repository
```
git clone https://github.com/mbxisbankai/Mnemosyne
```
### 🔴 Download the zip file from the **<> Code** area

## Usage for mnemosyne.py
+ Mnemosyne generates a key of the same byte size as the payload, using the xor function.

+ The key and payload are encrypted printed out in the terminal.

+ However, the payload should be entered in **base64** format.

+ To convert your payload to base64, visit <a href="https://gchq.github.io/CyberChef/">CyberChef</a>.

+ Run **mnemosyne.py** and paste in the base64 payload.

+ The output is the Payload length, XOR Encryption key and the Payload; all encoded.

## Using build-payload.py
+ Using the payload builder requires slight editing but nothing too complex.

+ Just paste the encrypted payload and key from **mnemosyne.py** into the double quotes.






