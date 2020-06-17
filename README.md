# Autocomplete-with-Trie

The trieNode holds the letter then its children hold other letters.
You can find the other letters of the node by traversing the nodes.
The A dictonary stores the children of each node.
I chose a  dictionary because it provides O(1) access and insert.

The trie node class enables the user to find and insert words

TrieNode methods:
Method   Time complexity    Space complexity
Insert:        O(1)             O(1)
suffixes     O(l*(nm) * k)      O(n)

Time variables
l is the number of child nodes
n length of the suffix
m is the number of letters
k is the length of nm

Space variable
n length of list in stored in each stack frame

Trie methods
Time to create trie O(w*l)
where w is num of words and l avg length of the word

insert: O(l) l is the length of the string O(1) space
find: O(l) l is the length of the string O(1) space
