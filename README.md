Describe: pigLatin()

Test: It will recognize a single vowel.
Code: pigLatin("a");
Expected Output: true

Test: It will recognize any vowel.
Code: pigLatin("e"); etc.
Expected Output: true

Test: It will recognize if a vowel is in index 0.
Code: pigLatin("apple");
Expected Output: true

Test: If a vowel is in index 0, it will concatenate "way" to the end of the element.
Code: pigLatin("apple");
Expected Output: "appleway"

Test: It will recognize a single consonant.
Code: pigLatin("p");
Expected Output: true

Test: It will recognize any consonant.
Code: pigLatin("p"); etc.
Expected Output: true

Test: It will recognize if a consonant is in index 0.
Code: pigLatin("prince");
Expected Output: true

Test: If consonant is in index 0 it will move consonant to end
Code: pigLatin("prince");
Expected Output: "rincep"

Test: If consonant is in index 0 it will move consonant to end and concatonate "ay".
Code: pigLatin("prince");
Expected Output: "rincepay"

Test: It will recognize "qu".
Code: pigLatin("qu"); 
Expected Output: true

Test: It will recognize "qu" at index 0,1.
Code: pigLatin("queen"); 
Expected Output: true

Test: If "qu" at index 0 & 1, then it will move "qu" to index.lenth -1
Code: pigLatin("queen"); 
Expected Output: "eenqu"

Test: If "qu" at index 0 & 1, then it will move "qu" to end and concatonate "ay" to end.
Code: pigLatin("queen"); 
Expected Output: "eenqu"

Test: It ignores non-alphabetical characters since they cannot be vowls or consonants.
Code: pigLatin("?");
Expected Output; false

Test: It will apply rules to multiple words in a string.
Code: pigLatin("This is a sentance.");
Expected Output; "isth isway away entancesay."



