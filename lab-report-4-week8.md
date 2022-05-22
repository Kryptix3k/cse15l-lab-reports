[Reviewed Repo](https://github.com/AllKeng/markdown-parser)

[My Repo](https://github.com/Kryptix3k/markdown-parser)

## **First Snippet**

### Expected Out for test1: `[google.com]`
![image1](codeSnippet1.PNG)

### My Test failure 1:
![test1](faileSnippet1.PNG)

### Reviewed Test failure 1:
![otherTest1](otherSnippet1Fail.PNG)

## **Second Snippet**

### Expected output for test2: `[b.com, a.com(()), example.com]`
![code2](codeSnippet2.PNG)

### My Test Failure 2:
![fail2](faileSnippet2.PNG)

### Reviewed Test Failure 2: 
![other2](otherSnippet2Fail.PNG)

## **Third Snippet**

### Expected output for test 3: `[https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule]`
![code3](codeSnippet3.PNG)

### My Test failure 3:
 ![fail3](faileSnippet3.PNG)

### Reviewed Test Failure 3:
![other3](faileSnippet3.PNG)


## **Implementation Questions**

- A code change that we could implement could be to add a conditional, checking for the existance of a back tick and ignoring whatever is between them, however this might not be only a small code change due to conflicts in text formatting.
- For this change I believe there is no simple way to change the code in order to correct it, because we would have to create a different function for open parenthesis or brackets that are not accounted for as it wasn't designed with the thought of nested behavior.
- For this code change we can as we would just use a conditional checking for newlines between parenthesis and brackets and if it does, ignore it, as it is not a link.
