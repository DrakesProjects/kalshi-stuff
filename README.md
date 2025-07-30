# Kalshi stuff
A demo of how to access kalshi API's. I'm currently working on a trading bot and robust infrastructure/tooling for trading on the platform. Direct any inquiries to drake.adams@hotmail.com

***DISCALIMER:*** Make sure you understand any code you run from this repository...

Any program not listed below is under development.

## root: general programs used in subdirectories
 - <ins>keyloader.py</ins>
 
   + Use make_headers method to easily create headers for api calls where api keys are needed

## data-pull: programs for pulling data from Kalshi's servers

 - <ins>get_historical_data.py</ins>
 
   + Creates an organized directory of raw files downloaded from kashi.com/market-data
   + Sets up a directory for you (input-path/kalshi-historical) on its first run and can be ran afterwards to update the dataset without redownloading old files.
   + Current size of dataset is around half a gigabyte as of 2025-05-30

 - <ins>websockets_tests.py</ins> (API Key required)

   + Make contact with Kalshi's WebSockets api for real-time exchange data
