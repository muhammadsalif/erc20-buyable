### Exercise:
Create a token based on ERC20 which is buyable. Following features should present;

- Any one can get the token by paying against ether
- Add fallback payable method to Issue token based on Ether received. Say 1 Ether = 100 token.
- Owner on creation of token will decide the Value based on ether.
- There should be an additional method to adjustPrice that allow owner to adjust price.
- Limit the buyer that it should be the EOA.
- The buyer can buy token even against 1 wei.