# JavaScript Task - Purchase Summary

You are given an array of purchase objects:

```js
const purchases = [
  { id: 1, customer: 'Alice', category: 'Books', amount: 25 },
  { id: 2, customer: 'Bob',   category: 'Games', amount: 60 },
  { id: 3, customer: 'Alice', category: 'Games', amount: 40 },
  { id: 4, customer: 'Alice', category: 'Books', amount: 15 },
  { id: 5, customer: 'Bob',   category: 'Books', amount: 30 },
];
```

## Task

Write a function

```js
function summarizePurchases(purchases) {
  // your code
}
```

that returns an object with the following structure:

```js
{
  totalAmount: number,
  byCustomer: {
    // customer name -> total amount
    // e.g. "Alice": 80, "Bob": 90
  },
  byCategory: {
    // category name -> total amount
    // e.g. "Books": 70, "Games": 100
  }
}
```

For the sample `purchases` above, the result should be:

```js
{
  totalAmount: 170,
  byCustomer: {
    Alice: 80,
    Bob: 90
  },
  byCategory: {
    Books: 70,
    Games: 100
  }
}
```

## Requirements

- Try to keep the solution clear and concise.
- Try not to traverse the `purchases` array more than once.
