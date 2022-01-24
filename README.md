# Axie.Taxi Documentation!

### Living document that describes the Axie.Taxi service

## What is Axie.Taxi
Axie.Taxi is a website that automates your guild team payments without seed phrases. Simply approve our Ronin address to operate for your team, and we'll automatically claim and transfer SLP as soon as it is available for all of your teams, in the background.

## How Axie.Taxi works
We rely on two basic concepts to make Axie.Taxi work:

1. Metamask -- We rely on Metamask (either a hot wallet or an attached hardware wallet) so we are never in custody of your keys or data.
2. SLP Spend Approval -- We send your wallet a request that gives us permission to spend your team's SLP so we can claim and transfer it.

## How to use it
- Import your Ronin seed phrase into Metamask (we recommend using a separate Chrome profile for Axie.Taxi if you have an existing Metamask wallet already.
- Press the "create account" button a bunch of times (for as many accounts as you have in your Ronin wallet, for all of your teams)
- Create a guild on [axie.taxi](https://axie.taxi), MAKING SURE to sign in the first time with your guild treasury account
- Go to the `/app/teams` page and click "automate all" to automate all teams
- Now, whenever a new claim comes in, the dashboard should update with the total claimed SLP.

## How to get help
- Reach out on Discord! Find our team's [specific user IDs](https://axie.taxi/team) or join the Axie.Taxi Discord.


## Contributing
If there is any information you want to record here, feel free to submit a pull request!
