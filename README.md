# Verakey
A custom Yubikey I'm designing to act as a cool keychain for my backpack! Along with having a keyring for me to mount it to a carabiner, it doesn't have a button, but instead a OLED screen I plan on adding some cute animations to, maybe a frog or something.

<img width="1724" height="948" alt="Verakey" src="https://github.com/user-attachments/assets/01042772-eb8a-47d7-b200-9ac4ae46464f" />

<img width="1465" height="592" alt="image" src="https://github.com/user-attachments/assets/13348919-3e71-4153-a647-4488c8b04787" />

It uses the STM32L432KBUx with an ATECC608 for maximum security, and will have the following protocol stack
-FIDO2
-U2F
-HOTP
-PIV

for maximal security. I also added a cool silkscreen.
