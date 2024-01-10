## Vultures = Provably Fair Rock Paper Scissors Bot, only on Bustabit.com

Vultures is a provably fair Rock Paper Scissors bot that players can interact with to safely play RPS against each other. Vultures will organize the game, declare a game winner, and tip the winner all by itself, automatically.

### How does it work ?

Player 1 tags Vultures to start a game with the following command: `@Vultures start game [username] [amountinBits]`. Vultures then starts the game, and asks for Player 2 to send their hash. After that, Vultures asks for Player 1 to send their plain text pick. And finally, Vultures asks Player 2 for their hash secret. Vultures then verifies if the hash secret matches with the hash, and instantly declares a winner and tips them the game amount via Shiba.

If Player 2 refuses to send their hash secret after Player 1 sends their hash, they are automatically forfeited from the game, and the bits for the game go to Player 1.

## What are the commands ?

### For Ryan, Daniel and Dark_Hero

Users "Daniel", "Ryan", and "Dark_Hero" are allowed to fund and check user balances with the following commands:

- `!fund [username]` to fund a user's balance with an amount of bits.
- `!bal [username]` to check a user's balance.
- `fixBal [username]` to correct a user's balance.

### For normal users

For normal users, here are the following commands:

- `!wd [amount]` to withdraw your account balance
- `@Vultures start game [username] [amountinBits]` to start a game with someone.
- `!rainon Vultures [amount]` to fund their account balance via Shiba.

### How to play

All hash secrets must have no spaces in them, and the pick in the hash secret must be lowercased.

For instance, `ThisIsMyHashSecret477299?#^*@()?|rock` is a valid hash secret because the pick is lowercased, and there's no spaces.
