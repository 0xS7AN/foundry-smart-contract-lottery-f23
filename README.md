# Proveably Random Raffle Contract

## About

This code is to create a proveably random smart contract lottery.

## How does it work?

1. User can enter by paying for a ticket.
   1. The ticket fees are going to go to winner during the draw.
2. After X period of time, the lottery will automatically draw a winner.
   1. This will be done programatically.
3. Using Chainlink VRF & Chainlink Automation.
   1. Chainlink VRF -> Randomness.
   2. Chainlink Automation -> Time based trigger.
