Generate a Tambola Ticket with below rules:

1. Ticket has dimensions of 3 rows and 9 columns (27 cells)
2. Ticket must contain a exact 15 numbers
3. Each column has numbers arranged in Ascending order
4. Each row has exact 5 numbers
5. Each colum will have minimum of 1 and maximum of 2 numbers
6. Each i column will contain numbers from (i * 10 + 1) to (i * 10 + 10) only. For example 0 column will contain numbers from 0-10, 1 column will contain numbers from 11-20 and so on.

Create a function which return the below result:
Output: 
[
  [0, 14, 22, 0, 0, 0, 64, 76, 86],
  [1, 16, 0, 30, 0, 51, 68, 0, 0],
  [6, 0, 27, 37, 44, 0, 0, 79, 0],
]

Sample Ticket:

![Image](https://i.stack.imgur.com/0w29r.jpg)

