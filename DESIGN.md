## score guess
For this I would want to set all the spaces in result to x. Following that I can loop through indexes of guess and secret to see if any match, and if so set the correpsonding index in result to a g. To place y's I would have nested for loops that go through every index in secret compared to guess and if an index in guess is valid, then turn that index to y in result. Another check would need to be done to see if guess and secret are exactly the same as well.

## valid guess
For this function I can iterate a loop num words many times and in each iteration check if the word at that index in vocabulary matches to guess. Then return true or false depending on the result.

## load vocabulary
First I need to open the file for reading. Then with a buffer of 6 loop while fgets run and then on each iteration I can allocate memory for a char and point it to my empty array that will then get filled by copying the word on that line of the file over. Then I can close at the file once fgets is done running and return out.

## free vocabulary
For this function I would traverse through vocabulary to free each string and then once the loop is done I can free vocabulary itself 
