# pyramid

The purpose of this project is to find the maximum sum of the numbers per the given rules below:

1. You will start from the top and move downwards to an adjacent number as in below.

2. You are only allowed to walk downwards and diagonally.

3. You should walk over the numbers as evens and odds subsequently. Suppose that you are on an even
number the next number you walk must be odd, or if you are stepping over an odd number the next
number must be even. In other words, the final path would be like
Odd -> even -> odd -> even ...

4. You must reach to the bottom of the pyramid.
Your goal is to find the maximum sum if you walk the path. Assume that there is at least 1 valid path to
the bottom. If there are multiple paths giving the same sum, you can choose any of them.

# Sample Input:
1 <br />
8 9 <br />
1 5 9 <br />
4 5 2 3 <br />

# Output:
Max sum: 16  <br />
Path: 1, 8, 5, 2

# Challenge 
215 <br />
192 124 <br />
117 269 442 <br />
218 836 347 235 <br />
320 805 522 417 345 <br />
229 601 728 835 133 124 <br />
248 202 277 433 207 263 257 <br />
359 464 504 528 516 716 871 182 <br />
461 441 426 656 863 560 380 171 923 <br />
381 348 573 533 448 632 387 176 975 449 <br />
223 711 445 645 245 543 931 532 937 541 444 <br />
330 131 333 928 376 733 017 778 839 168 197 197 <br />
131 171 522 137 217 224 291 413 528 520 227 229 928 <br />
223 626 034 683 839 052 627 310 713 999 629 817 410 121 <br />
924 622 911 233 325 139 721 218 253 223 107 233 230 124 233 <br />


## Acknowledgments

* Project create on Visual Studio Code in a Mac (if you are running in Windows, you might have a issue with new line format).

## Next Steps 
* You can face some issues running all unit tests in once, this is due concurrency. Try run one by one it will work.
