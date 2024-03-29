# Mnemosyne
## About
Mnemosyne is a payload encryptor that encrypts payloads using keys generated by the xor function.

This encryption works like a charm in AV Evasion.

## How to install it
### 🔴 Clone this repository
```
git clone https://github.com/mbxisbankai/Mnemosyne
cd ./Mnemosyne
chmod +x mnemosyne.py
sudo pip3 install -r requirements.txt
```
### 🔴 Or download the zip file from the **<> Code** area

## Usage for mnemosyne.py
+ Mnemosyne generates a key of the same byte size as the payload, using the xor function.

+ The key and payload are encrypted printed out in the terminal.

+ However, the payload should be entered in **base64** format.

+ To convert your payload to base64, visit <a href="https://gchq.github.io/CyberChef/" target="_blank" rel="noopener noreferrer">CyberChef</a>.

  ![b64](https://github.com/mbxisbankai/Mnemosyne/assets/108576900/8da1603d-bc15-4b1d-810e-6aa126ff291f)

+ Run **mnemosyne.py** and paste in the base64 payload.

+ The output is the Payload length, XOR Encryption key and the Payload; all encoded.

## Using build-payload.py
+ Using the payload builder requires slight editing but nothing too complex.
```
  nano build-payload.py
```
+ Just paste the encrypted payload and key from **mnemosyne.py** into the double quotes.

   ![Mnemosyne screenshot](https://github.com/mbxisbankai/Mnemosyne/assets/108576900/68627455-35fc-44ee-854a-490cfa5cf4c6)

+ The program is fully encrypted and can run without AV detection.

🚩Remember to give the built payload permissions 









