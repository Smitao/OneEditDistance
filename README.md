# OneEditDistance
Have you used auto-correction in documents or phones? Here is an example – if you type “interveew” the word will be auto-corrected to “interview” . One of the common technique for auto-correction is to use One-Edit-Distance approach. This approach looks up the dictionary for all the words that are one distance apart and provides the recommendation or auto-corrects. 
We have an implementation of One-Edit-Distance. It is suppose to return true if two words are exactly one edit apart, where an edit is:
Insert one character anywhere in the word (including at the beginning and end)
Remove one character
Replace exactly one character
 
Unfortunately, there is a bug in our implementation. It doesn’t work for certain scenarios. Could you please help us fix the bug in the code, we and our customers will appreciate it.

Hint1: The bug is only applicable when s2.length() - s1.length() ==1 and the first s1.length() chars are same for the two string.
