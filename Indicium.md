## 🚀 Indicium
Author: @kkevsterrr

Rwa Kuv, if you catch my drift.
${\color{red}103, 109, 98, 104, 124, 99, 99, 50, 54, 53, 99, 101, 103, 49, 49, 51, 98, 55, 51, 49, 101, 99, 55, 54, 56, 99, 57, 101, 103, 57, 53, 98, 57, 56, 49, 55, 53, 126}$

## 🔍 Decoding the Mystery
The first clue was the numerical values. I knew these could be ASCII codes. First i removed the `,` then convert them with decimal to ASCII, 
![440943807_887515263421061_1131888379776816692_n](https://github.com/MyBoss214/CTF-Writeups/assets/149683905/ce0be3b3-6071-439c-90ed-1e686bcc5487)
and revealed:`gmbh|cc265ceg113b731ec768c9eg95b98175~`


## 🧩 Unraveling the Cipher
At first glance, this looked like a jumbled mess. However, patterns soon began to emerge. The `|` symbol hinted at a possible separator, and the `~` at the end suggested a terminus. It felt like the text was encoded.

### 🕵️ Detecting the Shift
Upon closer inspection, the text appeared to be shifted by one character in the ASCII table. By reversing this shift, each character fell into place, revealing the hidden message.
![441889370_1499400707627776_4969735749390819506_n](https://github.com/MyBoss214/CTF-Writeups/assets/149683905/1b487e3c-7273-4317-9317-f81bed8442fb)

## 🏆 The Revelation
With the pieces in place, the final message emerged from the shadows: 
`flag{bb154bdf002a620db657b8df84a87064}`
