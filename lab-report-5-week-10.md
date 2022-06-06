# Lab Report 5

## Found the tests
the way I found the tests was by running ```script.sh``` file and having to save the results to a file called resulst's. From there, I compared the two result's files using Vimdiff.

# [First Test File ](https://github.com/nidhidhamnani/markdown-parser/edit/main/test-files/194.md)
1. Each of the implementations did not give me the correct output for the first test file. 
2. ![image](/images/Screenshot463.png)
On the left side of the result is the implementation provided by CSE15L, and on the right side of the result is my own implementation.
3. What the result is suppoed to be ```[my_url]```.
4.  honestly I’m not sure why this test file has a valid link. It probably has something to do the with the colon, which what i think it does is it registers things as a reference for the stuff before it. This is something complicated to fix, but if done right, might require checking for a colon after the closing bracket parsing the stuff after it that’s inside of parenthesis. Or maybe implement some method to skip/escape the parenthesis when it’s found.

![image](/images/Screenshot459.png)
What we could is add a variable to look for a special character where the circle is and then add an if statement to skip or parse the things behind it.

# [Second Test File](https://github.com/nidhidhamnani/markdown-parser/edit/main/test-files/519.md)
1. My implementation gave the correct output for this file but for the file provided by CSE15L did not.
![image](/images/Screenshot456.png)
2. Mine is on the right of the result, and the CSE15L is on the left
3. The result should be  [].
4. The bug that’s causing the wrong output is when the code doesn’t realize that the link is being sandwiched between an image.  To fix this we have to change the part of the code which checks the indices of the adjacent brackets or parenthesis, and there needs to be at least an ensure that there is a space between the exclamation mark and the open bracket.
![image](/images/Screenshot465.png)
 To fix this bug I think, we should add more if statements under the one that checks for ```nextOpenBracket and or nextClockBracket == -1```, so it checks for the position of the adjacent brackets and exclamation mark.