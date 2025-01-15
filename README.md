# Intra-exchange_arbitrage_scanner
The code checks intra-exchange trades on the binance cryptocurrency exchange. Its peculiarity is that after checking a pair, it will check it again and again, which allows analyzing permanent arbitrage trades. 
In practice, no trade will be successful because of the limitation in STEP-SIZE. The code uses tax_rate. We take the pairs from filtered_coins_output_pairs_simplified02, filter them and get filtered_coins_output_pairs_simplified03.txt to create the validation pairs 


https://github.com/user-attachments/assets/dbc28495-de25-44d1-8aea-6a4cb53a720a
