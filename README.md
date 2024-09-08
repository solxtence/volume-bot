
# Volume Bot

A Solana volume bot integrated with Jito 🚀

This script uses the [solana-swap](https://www.npmjs.com/package/@solxtence/solana-swap) package to get swap instructions and send transactions with Jito.

## Example Usage
Here we run the script on a random **pump.fun** token:


https://github.com/user-attachments/assets/37dc68b8-dea2-42e7-b6de-3e2ccdaed532



## Key Features

- **Jito Integrated**: 🚀 Experience much faster buys and sells with Jito.
- **It's Fast**: ⏱️ Average 1-3 buys and sells per minute.
- **Easy Setup and Use**: ⚙️ Simple to set up and easy to use.
- **Supports Multiple Platforms**: 🌐 Compatible with all platforms like Pump.fun, Raydium, Moonshot, Ocra, and more with the help of our [solana-swap](https://www.npmjs.com/package/@solxtence/solana-swap) package.

## Prerequisites

- Node.js (install from [nodejs.org](https://nodejs.org/))

## How to Use

1. Clone the repository:

   ```sh
   git clone https://github.com/your-repo/volume-bot.git
   cd volume-bot
   ```

2. Move to the `/script` folder:

   ```sh
   cd script
   ```

3. Rename the `.env.example` file to `.env`:

   ```sh
   cp .env.example .env
   ```

4. Open the `.env` file in a text editor and fill in your `PRIVATE_KEY` and `RPC_URL`. The `.env` file should look like this:

   ```
   PRIVATE_KEY=your_private_key_here
   RPC_URL=https://your.rpc.url
   ```

5. Run the script:

   ```sh
   node volume-bot.js
   ```

6. Follow the prompts to set your configurations, such as the amount of runs, amount per run, token address, Jito tip, etc.

7. Once in the bot menu, enter `1` to start the volume bot.

**Make sure you have some SOL in your wallet for transaction fees.**

## Important Notes

- The `volume-bot.js` script is compiled and minified to run faster and to prevent unauthorized copying and redistribution. This is the free version of the bot.
- **Stay tuned!** A paid version of this bot is coming soon, which will enable you to send 5x or more transactions with different wallets per run compared to the current version.

## Troubleshooting

- **Swap issues**: 🔄 Check that your token addresses are correct and that you have enough balance.
- **Unexpected errors**: ❓ Open an issue [here](https://github.com/solxtence/volume-bot/issues) and we’ll help you out!

## Resources

- [SolanaSwap NPM Package](https://www.npmjs.com/package/@solxtence/solana-swap)
- [Swap API Docs](https://docs.solxtence.com/swap)

## FAQ

**Is there a fee for using this bot?**

No, there are no fees for using this bot. It’s free to use!
