# Huffman Decoding

- A huffman encoding is a way of encoding a string using the least amount of data as possible
- Write a script that will decode a huffman encoding

```txt
message: Hello World
encoding: 00000110101100100111101110101111

frequency chart:
| letter | # of occurrences | code |
| ------ | ---------------- | ---- |
| l      | 3                | 10   |
| o      | 2                | 110  |
| h      | 1                | 000  |
| e      | 1                | 001  |
|        | 1                | 010  |
| w      | 1                | 011  |
| r      | 1                | 1110 |
| d      | 1                | 1111 |
```