# Algorithme
the problem: write an algorithm that reads a sentence, which ends with a point, character by character, and to determine the number of characters , words and vowels
-------------------
Constraints: the sentence should be type string, also the number of characters, words and vowels should be integers

Input: the sentence added

Output: the number of characters, words and vowels
-------------------
the Solution: consist of reading the sentence then run the length of sentence with iterrative process using the for_loop, and start counting the number of characters then run an if statement and place a condition to count words after every space or point and another if to count vowels.
-----------------------------------------------------------------------------------------------------------------------------------------------
algorithm design:
begin
declare six variables: sen:string , nbcharacters:integrer, nbwords:integer, nbvowels:integer , ch:char, i:integer
Read the value of sen
initiated a for_loop from 1 to length(sen)
stored every character of the sentence in the ch variable
counted the number of characters
initiated an if statment inside the loop with a condition to count the number of words
initiated another if statement to count the number of vowels
print the value of theses variables nbcharacters, nbwords and nbvowels
end

