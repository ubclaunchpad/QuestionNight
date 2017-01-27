# QuestionNight
UBC Launch Pad Coding Interview Workshop

1.) Given a list of integers L and a value, k, determine whether there exist two elements in L, a, b so that a + b = k. Can you do it in O(n)?

2.) Lineville is a one-dimensional city with n houses, where each house is located at some xi, on a discrete-valued x-axis that begins at 0. The Mayor wants to install radio transmitters to cover every house in the city. All radio transmitters have a range, k, and can only be installed on existing houses. Given a map of Lineville (represented as an array with a 1 at indices containing a house and a 0 otherwise) and the value of k, find the minimum number of transmitters needed to cover every house in Lineville.

3) Given a string sentence, reverse the words (do not use library functions)
	Input: “I love dogs”
	Output: “I evol sgod”
Follow-up question: What other chars are considered whitespaces?

4) Given a binary tree, return true if there exists a path (strictly from parent to child) whose sum is equal to the root. How can you improve the algorithm if nodes are strictly positive? (start with drawing the node structure). What is the time complexity?

5) Given a string and a pattern string, return the index of the first occurrence of that pattern in the string. If the pattern does not exist, return -1.

Eg:
public int stringMatch(“Apple”, “ppl”) ---> 1
public int stringMatch(“My dog ran away”, “cat”) ---> -1

6.) Levenshtein distance is the minimum number of single character edits required to make two words equal. For example, for the words wish and disk, the Levenshtein distance is two because it takes two single-character edits to turn wish to disk (wish => dish => disk). Given two words of the same length, find their Levenshtein distance.
