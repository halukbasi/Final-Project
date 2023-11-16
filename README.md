### Final-Project
Rise In Solana Bootcamp Final Project

### Deployment

Build the Contract: Go to the program directory and use cargo build-sbf.

Set Configuration for Devnet: Configure your Solana CLI to connect to the Devnet using command solana config set --url devnet. If necessary use https://faucet.solana.com/ for airdrop.

Build and Deploy the Contract: Compile and deploy the contract by using command solana program deploy target/deploy/nft.so and save the generated programID.

Download Dependencies: In the program_client directory, run yarn install and also add the @solana/spl-token package with yarn add @solana/spl-token.

Run app.ts: Execute npx ts-node app.ts <YOUR_PROGRAM_ID> to run the app.ts script, replacing <YOUR_PROGRAM_ID> with the saved program ID.
