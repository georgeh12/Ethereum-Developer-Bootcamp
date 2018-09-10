# Setup
1. Load code on [Remix](http://remix.ethereum.org/#optimize=true&version=soljson-v0.4.24+commit.e67f0147.js)
2. Open 2 files in Remix browser: UniCoin.sol, MintedCrowdsale.sol
2. Run > dropdown select "UniCoin" contract > Deploy
3. Run > dropdown select "UniCoinICO" contract > expand dropdown to enter parameters
	* _tokensPerWei: value sets how many tokens you get per Wei sent to this contract
	* _wallet: wallet address to transfer Wei from this contract
	* _token: use address of "UniCoin" contract
	* transact button: press this to deploy ICO
4. Expand "UniCoin" contract > transferOwnership > expand dropdown to enter parameters
	* newOwner: enter the address of the ICO contract
	* transact button: press this to start accepting payments thru ICO
5. Enter Value for amount of Wei to send
6. On the ICO contract, click fallback to buy tokens using the value amount
7. Send tokens to a friend by entering the "address_to" on the "buyTokens" function

Note: there is no way to end the ICO, so prepare to get rich.