# Wheatstone-Playfair-Cipher
The Wheatstone Playfair cipher is a multiple letter encryption cipher that uses a substitution technique.

Steps in encrypting/decrypting a text using playfair

1. Create a 5×5 matrix using the secret key provided by the sender. In this matrix, I and J are in the same cell. you start filling the matrix with the key, then you use the alphabet. Letters are placed only once in the matrix.
2. We seperate the message into digram(two letters each at a time). To do that, we follow four rules:
  a. When you get two letters, if they are the same letter, you add a “filler” in the middle. It can be the letter ‘x’.
  b. If the two letters fall in the same row of the matrix, you substitute them with the next letter in the row. Rows have a circular behavior. The next letter of the        last in a row is the first letter in that row.
  c. If the two letters fall in the same column of the matrix, you substitute them with the next letter in the column (going down). Columns have a circular behavior. The      next letter of the last in a column is the first letter in that column.
  d. If the two letters are not in the same row and column, then you substitute each letter by the letter in the same row and the column of the second letter. 
