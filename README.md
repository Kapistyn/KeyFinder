— Instructions for using KeyFinder

Step 1.

This program already has a list of bitcoin addresses with a positive balance. 
File name Addresses.txt (661386 wallet addresses).

If you want to load the lists of your bitcoin addresses, create an Addresses.txt file and add the addresses there.

Important: The file must be named Addresses.txt

———————————————————————————————————————————————————————————————

Step 2.

Run KeyFinder.exe

When you run the program, the wallet addresses from the Addresses.txt file will be loaded.


The following text appears...
Enter start range in BITs [min. 0 max. 255]:

You need to enter an initial range to search for private keys.
Almost all bitcoin addresses with a balance are in the 254-256 BITs range.
It is recommended to set the values to 254, 255 (Enter only numbers), then press Enter.

———

The following text appears...
Enter end range in BITs. More than the first. [max. 256]:

Set the values 256 (Enter only numbers), then press Enter.

———

The following text appears...
Output data [1 — Full info, 2 — Mini info]:

Set to value 1 if you want to see all bitcoin addresses that will be random generated, or value 2 to see the minimum information.
Press Enter, and the private key search begins.

———————————————————————————————————————————————————————————————

Step 3.

When the private key is found, all the information will be written to the Found.txt file.

———————————————————————————————————————————————————————————————

Step 4.

Bitcoin Puzzle

There is a Bitcoin Puzzle, where participants pick up private keys that are already in a known range.
Visit https://privatekeyfinder.io/bitcoin-puzzle/
There you will see solved riddles and unsolved

Example:

HEX Unsolved
Start key 0000000000000000000000000000000000000000000000008000000000000000 
Stop key 000000000000000000000000000000000000000000000000ffffffffffffffff 
8000000000000000...ffffffffffffffff (263...264)
P2PKH(c) 16jY7qLJnxb7CHZyqBP8qca9d51gAjyXQ - 0.64032959 BTC

(263...264) - To find the solution to this puzzle, specify the range 63-64 in KeyFinder.exe
You do not need to enter the number 2 as this puzzle has 64 BITs

Bitcoin address 16jY7qLJnxb7CHZyqBP8qca9d51gAjyXQ is already in the Addresses.txt file

———————————————————————————————————————————————————————————————

We wish you luck in your search for bitcoins!
