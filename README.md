<snippet>

# Vigenere Cipher
Implementation of the Vigenère cipher learned in CIS-3360 at the University of Central Florida

## Usage
*Command Line Parameters*

1. The first parameter must be the name of the encryption key file, as described below. 
2. The second parameter must be the name of the file to be encrypted, as also described below. 

*Run command*
`javac vigenere.java`
`java vigenere keyfilename plaintextfilename`


*Encryption Key File Format*

The encryption key is plain text that may contain upper and lower case letters, numbers, and other
text. The input must be stripped of all non-alphabetic characters. Please note that the input text
must be converted to contiguous lower case letters to simplify the encryption process.


*Format of the File to be Encrypted*

The file to be encrypted can be any valid text file with no more than 512 letters in it. (Thus, it's safe
to store all characters in the file in a character array of size 512, including any padding characters.)
Please note that the input text file will also generally have punctuation, numbers, special characters,
and whitespace in it, which should be ignored. You should also ignore whether a letter is uppercase
or lowercase in the input file. Thus, you should treat ‘A’ and ‘a’ the same in your program.
Therefore, convert the upper case letters to lower case letters.

## Output
```
Key: 

bbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbb

Plaintext: 

ifyoufindthatyourespendingalmostallyourtimeontheorystartturningsomeattentiontopr
acticalthingsitwillimproveyourtheoriesifyoufindthatyourespendingalmostallyourtim
eonpracticestartturningsomeattentiontotheoreticalthingsitwillimproveyourpractice
donaldknuthxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

Ciphertext: 

jgzpvgjoeuibuzpvsftqfoejohbmnptubmmzpvsujnfpouifpsztubsuuvsojohtpnfbuufoujpoupqs
bdujdbmuijohtjuxjmmjnqspwfzpvsuifpsjftjgzpvgjoeuibuzpvsftqfoejohbmnptubmmzpvsujn
fpoqsbdujdftubsuuvsojohtpnfbuufoujpoupuifpsfujdbmuijohtjuxjmmjnqspwfzpvsqsbdujdf
epobmelovuiyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyy
