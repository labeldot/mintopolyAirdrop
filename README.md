# Mintopoly! Money Airdrop

**Note: to view the results of each airdrop transaction and prize distribution, click on each round's txt file in this repo.**

This repo records the airdrop results for the Mintopoly round awards. Each week, the top X finishers recieve an airdrop of our ERC-20 token (Mintopoly Money) based on their net worth and finish position. The distribution formula works like this...

1. Tally net worth of combined top n (typically 250-500) players
2. Loop through each player, in order of rank. For each:
	1. Divide their net worth by total net worth
	2. Multiply this by the airdrop size to get their payout amount
	3. If their share is > 1% of airdrop size, cap their payout at 1%
	4. Subtract this player's payout from total payout remaining and their net worth from total net worth remaining.
	5. Repeat with each successive player with these new totals 


Each weekly calculation is posted in a txt file here, and airdrop transactions are recorded below. Note that transactions may not occur immediately after reach round – they may be batched for 2-4 rounds (i.e. 2-4x per month in order to save gas fees).


## Layer 2 ETH <-> Polygon Layer 2 Bridge

Starting with round #8, a layer-2 bridge was created on the Polygon network for Mintopoly Money tokens and all airdrops were preformed via these layer 2 tokens. **For full details on how this bridge functions, please see our official banker application at https://mintopoly.io/banker.** In addition to full documentation on the bridge system, that link will also allow you deposit / withdraw tokens across this Polygon bridge.

## Contracts / Links

**Mintopoly Banker** (to view balances and transact):
* https://mintopoly.io/banker

**Official Polygon Bridge** (to move tokens on/off the mainnet):
* https://wallet.polygon.technology/bridge

**Ethereum Mintopoly Money Contract:** 
* https://etherscan.com/token/0xf6a09deadf5a10aa7822d95e3228b2315de8f6fa

**Polygon Mintopoly Money Contract:** 
* https://polygonscan.com/token/0xf6a09deadf5a10aa7822d95e3228b2315de8f6fa

