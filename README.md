This library uses rejection sampling to provide cryptographically secure `n`-sided dice rolls and random sampling (within a given range).

## Usage:

If we want to use the system-specific entropy source (`systemEntropy`) to
produce 10 dice rolls of a 6-sided dice (i.e. range [0,5]), you can write:

> systemEntropy $$ diceRolls 6 =$= CL.take 10
> [5,1,3,3,0,5,3,2,2,1]
