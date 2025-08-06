# Kalshi stuff
A demo of some of the kalshi exchange API's in Python. I'm working on more complex tooling for the exchange privately. Email any inquiries to Drake.adams@hotmail.com

***DISCALIMER:*** Make sure you understand any code you run from this repository...

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
