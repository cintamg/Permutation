# Permutation
All possible 2 letter permutations of a word.
from itertools import permutations
x,y=input().split(" ")
z=list(permutations(x,int(y)))
z.sort()
for i in z:
    print("".join(i))
