# BIP39-diceware

Generate BIP39 seed words or passphrase using plain six sided dice and a coin in an uniform way

## How to use it

Flip the coin (H|T) and roll the dice four times [1-6]{4}. Select a word from the list that matches your result. If your result is greater than 5534 roll again.

This can be used to generate Bitcoin seed words or passphrases using manual entropy.

## For example

You flipped the coin and got tails (T). Then you rolled the dice and got 1, 6, 2, and 3 (`T1623`). The matching word in the list is `nurse`.

You flipped the coin and got heads (H). Then you rolled the dice and got
5, 6, 1, 1. Because the result is greater than 5534 you have to roll again.

## Print friendly format

`column -c 120 words`
