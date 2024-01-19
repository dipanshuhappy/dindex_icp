# dindex_icp

In an index fund , you buy one index of  a bags of assets . You are equally buying/paying for the price of all those shares either shared equally or some custom ratio ....
S&P 500 , Nifty 50 these are all index funds in the tranditional finance sense . But what if there were verifiable index funds in defi (this should not be confused with crypto index , that exists in traditional fiance) . So a verifiable index funds in defi alias as dindex (pronouced as din-dex ) can be defined as a crypto token which if minted will equally be backed by what ever crypto tokens the user specifices and in the ratio which the user specifices. This dindex protocol will have the following specification...

## Specification
1. Any user can create a dindex anonymously (lets call him the Creator) but dindex tokens can also be backed by verified offchain data like Twitter account or Youtube account . This gives any social media influencer or Defi Expert to create his/her
dindex and retail users can be 100% sure this is the official dindex.
2. While creating dindex , the Creator speicifies all the details a normal tokens have except for the fact that the totalSupply of the token will be infinite (in practicality there won't be enough liquidity to support that). This is because the dindex supply can grow as the liquidty allows it too.
4. Then the Creator selects tokens and there appropriate ratio . For example user will select Eth and BTC and select the ratio as 0.5 and 0.5 .
5. In the current specification the dindex ratio and tokens can't be changed . This is because it will be near impossible to liquidate retail users if they want to withdraw the underlying assets of the index .
6. The Creator then sends a ZK proof of their social account to verify that they are the autorised makers of this dindex
7. The Creator can also set a dindex royalty fee for him/her self , as a reward.
8. The dindex contract will have a mint function ,which will mint a valid token only if you pay it enough ICP tokens to transaction to purchase the tokens from a liquidity pool and keep incustody of the smart contract.
9. Then there will be a withdraw function ,which will take in the valid dindex transaction and burn it and will give you your respect backend tokens .


## UI Specification
1. A create token page
3. A dindex listing page.
4. A dindex portfolio page of the user.
