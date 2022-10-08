# wait-function
 A very very very short script that make a wait function

## Function
This function is very short, it's something that make your script wait for X milliseconds

## Usage
It is very easy to use, as long as it's in an async function.
Import the file [`wait.ts`](./wait.ts) in your code to use it.

#### JavaScript
```js
const { wait } = require('./wait.ts');

const sendJoke = async (joke) => {
    console.log(joke.title);
    await wait(1000); // Wait 1 second

    console.log(joke.answer)
};

sendJoke({ title: "Knock knock - Who's here", answer: 'Wu!' });
```

#### TypeScript
```ts
import { wait } from './wait';

async function run() {
    await wait(1000): // Wait 1 second

    console.log("foo");
};

run();
```

## Contact
You can contact me on [this discord server](https://discord.gg/fHyN5w84g6)