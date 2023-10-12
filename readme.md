

## first cannister id  
- h5gsv-4qaaa-aaaam-aburq-cai

 ## Create Canister
 dfx canister --network ic create first_canister --with-cycles 1000000000000

## build
dfx build --network ic first_canister

## install 
dfx canister --network ic install first_canister

## call greet 
dfx canister --network ic call first_canister greet '("Samuel")'