# Lab report 4 

## Implementation
[here](https://github.com/Omartinezangulo/markdown-parser)

## Other Implementation
[here](https://github.com/ANGUYEN625/markdown-parser)

# Snippet 1

## Junit test
![image](/images/Screenshot403.png)

## My result 
![image](/images/Screenshot408.png)
My implementation didn't work 
## there result 
![image](/images/Screenshot4016.png)
 there implementation did work either for the same cause that it couldn't find the file.
# Snippet 2

## Junit test 
![image](/images/Screenshot404.png)

## My result 
![image](/images/Screenshot407.png)
My implementation didn't work 

## there result 
![image](/images/Screenshot417.png)
 there implementation did work either for the same cause that it couldn't find the file.

# Snippet 3

## Junit test
![image](/images/Screenshot414.png)

## My result 
![image](/images/Screenshot415.png)


## there result 
![image](/images/Screenshot420.png)
My implementation didn't work becuase of the brackets and theres didn't work becuase it couldn't find the files.

# Questions 

1.  For Snippet 1 it is possible to make these cases work in a small code change. To make ```url.com line 1``` readable, we can first check to start the parsing after the first closed bracket using the indexOf method.
2.   Brackets within the variable name, we can check by seeing if there is an even amount of brackets there (which they should be in pairs). This could be checked with a code change. It should also read the brackets on the outer layer by looking and comparing the int value using indexOf. It should use open braket [  with the smallest int value and the closebraket ] with the largest int value.
3.  With line conditions, there may be cases that may need to be accounted for because in some cases, new lines cause our system to not know when exactly parser should end for a link. This can happen by checking when openbracket ```]``` is there or not. It’s can be tricky as there may be no closing parenthesis at all. We can keep track of a counter that has the amount of characters/text that exist when reading past close parenthesis ) in order to stop it.
 
 