caesar cipher algorithm:

Caesar Cipher Technique is the simple and easy method of encryption technique.
It is simple type of substitution cipher.
Each letter of plain text is replaced by a letter with some fixed number of positions down with alphabet.
For each character in the given plain text, transform the given character as per the rule depending on the procedure of encryption and decryption of text.
After the steps is followed, a new string is generated which is referred as cipher text.

There is an integer value required to define each letter of the text that has been moved down. This integer value is also known as the shift.
We can represent this concept using modular arithmetic by first transmuting the letter into numbers, according to the schema, A = 0, B = 1, C = 2, D = 3…….. Z = 25
for decryption:
The decryption is the same as encryption. We can create a function that will accomplish shifting in the opposite path to decrypt the original text. However, we can use the cyclic property of the cipher under the module.
Cipher(n) = De-cipher(26-n)
The same function can be used for decryption. Instead, we will modify the shift value such that shifts = 26 - shift.
