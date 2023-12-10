# Typescript Labs

## Lab 1: Implicit "Any" type error

file: `/src/01-number.problem.ts`

Consider this addTwoNumbers function:

```ts
export const addTwoNumbers = (a, b) => {
  return a + b;
};
```

This function takes in a and b and adds them together.

It looks like perfectly valid JavaScript.

Running npm run exercise 01 in the terminal, we can see that our tests pass.

But even though it looks valid and tests pass, TypeScript isn't happy.

The terminal displays the following errors along with the line of code where they happen:

```sh
Parameter 'a' implicitly has an 'any' type.
Parameter 'b' implicitly has an 'any' type.
```

**_challenge_**: Read through the ["Migrating from JavaScript" article in the TypeScript docs](https://www.typescriptlang.org/docs/handbook/migrating-from-javascript.html) and see if you can find how to fix these TypeScript errors.