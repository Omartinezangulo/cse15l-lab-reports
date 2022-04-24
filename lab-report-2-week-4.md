# Lab report 2

## Previous Lab report [here.](https://omartinezangulo.github.io/cse15l-lab-reports/lab-report-1-week-2.html)

# #1 Code Change.

## My Commit Message
 ![image](/images/Screenshot294.png)
 [Test File we Fixed.](https://github.com/leahkuruvila/markdown-parser/blob/6938e7d578994dbde1da1c611c9ee5034838fcc9/test-file.md)


# Symptom/Error
![image](/images/Screenshot295.png)

# Explanation
If there is anything after the link then the file would go into a infinite loop until it it finds a closed bracket. The way we solved it was we checked if ```closeParen +1 ``` was smaller by comparing it to the ```currentIndex```. If currentIndex kept getting bigger but ```closeParen + 1``` went back to the start of the file. We made this if statement that states ``` if closeParen + 1 is less then currentIndex```, then ```break```, which stops the code.    

#  #2 Code Change.

## My Commit Message
![image](/images/Screenshot297.png)
[Test File We Fixed.](https://github.com/wchester/markdown-parser/commit/70178e38fc382f9f4bce230aeff84d3a2385ab2d)

# Sypmton/Error
![image](/images/Screenshot296.png)

# Explanation  
 If there is nothing but just text, then it would not read anything and it would give you an error that is out of bounds. The way we fixed it was make a if statement that states ``` if the markdown.indexof("[, currentindex) equals -1 then return toReturn```. this checks if there is a bracket and if there is and it is on the last index then it returns nothing, same as if there wasn't. 

# 3 Code Change.

 ## My Commit Message.
 ![image](/images/Screenshot298.png)
 [Test File we fixed](https://github.com/wchester/markdown-parser/commit/9c06a935770e43f36587140ccb6ae5b7810a95b1)

# Sypmton/Error
![image](/images/Screenshot299.png)

# Explanation  
The error we tested this time was if the file didn't have () but had []. The [] weren't used in a link so the code could not find a link and had an out of bounds error. The way we fixed it is with any cases with brackets or parentheses being used from something other than for links we used an if to check that all these characters exist in a file and if not just return. That is the if statment is saying ``` if(the markindex with any type of bracket equals -1) then return toReturn.```
