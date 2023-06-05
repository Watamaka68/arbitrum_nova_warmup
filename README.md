 1. About: 

Script to warms up your wallets on Arbitrum nova.

First of all, it swaps random tokens (USDC, DAI, WBTC, ARB) on a random platform (arb, sushi, rpc, slingshot)

At the end, it adds liquidity to one of them.

 2. Config: 

 amount_max - amount_min - maximum and minimum swap random value in eth

 liquidity_amount - how much liquidity you want

 private_keys.txt - put to your private keys here

 3. Install required packages

```commandline
    pip install -r requirements.txt
```

 4. Start

  ```
  python main.py
  ```


And I do not advise you to do swaps for LARGE AMOUNT.