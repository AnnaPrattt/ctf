# Forgotten

## Description:
Julius uses the same password to log on to all of his favorites sites like Neopets, Club Penguin, and Webkinz. He's trying to log in, but forgot his password! He only has it written down in a code, can you help him get his password to log back in?

Flag format - `ctf{password}` (case insensitive)

## Writeup:
This problem was composed of two steps - a Club Penguin cipher, followed by a Caesar Cipher (hinted because the person in the description is named Julius). Decoding the picture using the Club Penguin cipher would result in `htyytsujslzns`. Shifting each character by 5 letters results in the flag.

**Flag** - `ctf{cottonpenguin}`