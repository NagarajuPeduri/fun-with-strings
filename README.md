# fun-with-strings

Programming question, where you will be given a number n, and we need to return count of strings that are generated after applying below conditions.
conditions:
- string should only have vowels
- 'a' should be followed by only 'e'
- 'e' should be followed by only 'a' or 'i'
- 'i' should not be followed itself
- 'o' should only be followed by 'i' or 'u'
- 'u' should only be followed by 'a'

ex:
i/p : 1
o/p : 5   // {a, e, i, o, u}  number of possible strings with length one

i/p : 2
o/p : 10  //{ae, ea, ei, ia, ie, io, iu, ou, oi, ua} number of possible strings with length two
