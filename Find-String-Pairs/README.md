Find String Pairs 

Create a method that takes a string parameter and looks for pairs of strings in the code, breaking the string up using spaces as the delimiter. There are two types of pairs, combinations and adjacent, and you'll need to find a count of each. Adjacent pairs appear alongside each other, while combination pairs cover every permutation that can be found of pairing the strings.

So if you have a string 

dzone java dzone dzone javascript java

the results would be 

dzone has 1 adjacent pair 
dzone has 3 combination pairs (0,2) (0,3) (2,3)
java has 1 combination pair (1,5) 
