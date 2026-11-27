# Tact course

A hands-on course on writing TON smart contracts in [Tact](https://tact-lang.org). Ten lessons, each in its own repository with contracts, tests and deploy scripts built on [Blueprint](https://github.com/ton-org/blueprint).

| # | Lesson | What you build |
|---|--------|----------------|
| 1 | [lesson1](https://github.com/alefmanvladimir/lesson1) | First steps on TON from TypeScript: open a wallet and send a transfer on testnet |
| 2 | [lesson2](https://github.com/alefmanvladimir/lesson2) | First Tact contract: a counter with tests and deploy scripts |
| 3 | [lesson3](https://github.com/alefmanvladimir/lesson3) | Types: integers, bools, addresses, strings, constants, getters |
| 4 | [lesson4](https://github.com/alefmanvladimir/lesson4) | Messages and receivers: counter, bulk adder, fund, contract-to-contract calls |
| 5 | [lesson5](https://github.com/alefmanvladimir/lesson5) | Sending TON and deploying child contracts from a contract |
| 6 | [lesson6](https://github.com/alefmanvladimir/lesson6) | Functions, loops, maps, optionals, time and randomness |
| 7 | [lesson7](https://github.com/alefmanvladimir/lesson7) | Traits: Deployable, Ownable, Stoppable and a custom Trackable trait |
| 8 | [lesson8](https://github.com/alefmanvladimir/lesson8) | Parent–child contracts and a Jetton (fungible token) |
| 9 | [lesson9](https://github.com/alefmanvladimir/lesson9) | NFT collection and NFT item contracts |
| 10 | [lesson10](https://github.com/alefmanvladimir/lesson10) | Telegram Web App front end for a Jetton contract (React, Vite, TON Connect) |

## Get all lessons

```bash
git clone --recurse-submodules https://github.com/alefmanvladimir/tact-course.git
```

Each lesson is a separate project:

```bash
cd tact-course/lesson2
npm install
npx blueprint build
npx blueprint test
```

## Note on versions

The lessons were written in 2023 for the Tact and Blueprint versions of that time. The ideas carry over; some syntax and package names have changed since, so check the current [Tact documentation](https://docs.tact-lang.org) when something does not compile.
