## get principal
dfx identity get-principal     

## Create canister
dfx ledger --network ic create-canister principalID --amount 0.3

## deploy wallet
dfx identity --network ic deploy-wallet cannisterID

## check wallet balance
dfx wallet --network ic balance

## top up wallet canister balance
dfx ledger --network ic top-up --amount 0.7 cannisterID 

## first canister id  
- h5gsv-4qaaa-aaaam-aburq-cai

 ## Create Canister
 dfx canister --network ic create  canisterName --with-cycles 1000000000000

## build
dfx build --network ic canisterName 

## install 
dfx canister --network ic install canisterName 

## call greet 
dfx canister --network ic call  canisterName greet '("Samuel")'