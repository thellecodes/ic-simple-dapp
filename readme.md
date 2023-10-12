## get principal
dfx identity get-principal     

## Convert to canister
dfx ledger --network ic create-canister principalID --amount 0.3

## Canister id 
h2hub-riaaa-aaaam-abura-cai

## deploy wallet
dfx identity --network ic deploy-wallet

## top up wallet canister balance
dfx ledger --network ic top-up --amount 0.7 h2hub-riaaa-aaaam-abura-cai

## first canister id  
- h5gsv-4qaaa-aaaam-aburq-cai

 ## Create Canister
 dfx canister --network ic create first_canister --with-cycles 1000000000000

## build
dfx build --network ic first_canister

## install 
dfx canister --network ic install first_canister

## call greet 
dfx canister --network ic call first_canister greet '("Samuel")'