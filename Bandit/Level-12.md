# Bandit Level 11 --> Level 12
#### Goal: The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions.
#### Username: bandit12
#### Password: 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
#### Steps: Since the alphabets (both uppercase & lowercase' in 'data.txt' is said to be rotated by 13, then- a -> m; A -> M; n -> z; N -> Z. Thus we use 2 chained commands like- 'cat data.txt | tr 'a-zA-Z'  'n-za-mN-ZA-M'', which outputs the password. 

![Bandit Level-12](Bandit-Level-12)
