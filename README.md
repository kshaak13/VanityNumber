# VanityNumber
VanityNumberCode

Best for this problem would be the results with the most amount of letters in the results.

1. Record your reasons for implementing the solution the way you did, struggles you faced and problems you overcame.
  A lot of the struggles I faced during this implementation are why I ended up implementing the solution the way I did. To start, once I figured out what a Vanity number is my first thought was to find every possible combination of letters that would match the number that the users would enter. I quickly found that this had me doing conversations that seemed unnecessary. At one point I ended up with 5 loops all with in each other along with two if statements. My code was getting longer and it seemed to be more complex than necessary. Eventually I got stuck and was unable to figure out how to continue on the path I had started. At this point I decided to trash my code and I started to Google for other directions that other people took similar codes like this. From what I had found some people had done it by using trees and others had attacked the problem the same way I was but their codes did not make sense to me. Eventually I came across a discussion where the users were coding in python and discussioning how to find what would would earn the most points in scrabble. They did this by reverting the letters to numbers and then adding and multipling them as they fit on the board depending on the combination and the pattern of letters and numbers they had access to. Realizing if I used numbers to find the patterns instead of letters I would have a lot less values that I needed to work with all at once helped me to then. With this thought in mind, I coded from top to bottom the process that the data would have to take to give the needed results. This is the first time I have ever used AWS services together. At most we had used one or two services for a Web API and left it at that point. Learning a lot of new applications all at once was defiently a huge struggle I faced along with learning about S3 that I have never used before. After days and hours of Googling I was able to figure out most of my mistakes and made it work. 

2. What shortcuts did you take that would be bad practive in production?
    Some of the outstanding short cuts that I took was that I coded everything in one file whhich is something we are taught not to do from the beginning. It would have been more logical, safe, and organized if I had created different methods  and organized them into different files and had not had one complete flowing code. Another huge bad practice that I did was I did not create proper test cases or write in exception handling. For this code the way I tested was mostly through Console.Write statements after loops to make sure that the data was being manipulated the way I wanted it to. Exception handling should defielty be added but I've never had a love for it and usually end it once all is said in done in codes. I like to make codes as small and clean as possible. (I'm not even a fan of commenting due to the amount of space it takes in a code). But commenting and exception handling are necesary so I usually also go back over the code and do it at the end. It also helps me to review the code this way to make sure everything follows the correct path. Another short cut I kinda took was by using the S3 bucket for the dictionary text file. It would have been better to pull from a public API so that more words could be used and compared in the code. However having access to edit the file helped with testing and keeping my testing more predictiale. 

3. What would you have done with more time?
   If I had more time I would go though and add exception handling to the code so that it is more complete. I would also look into other ways of making sure the top 5 are the actual top 5. I am not 100% sure that the ordering on the dictionary worked the way I wanted it to, I think if it can't find 5 that work then it prints repeats. I was trying to order the top five by seeing which combination had the most letters in it. Something else I would have liked to add would be to code it so that a person can enter their whole number and the code would disregard the area code and also it would ignore the dashses if someone added them and also to see if combining two words would work for the phone number (ex. GOTMILK, right now the code would only find GOT and MILK, it wouldn't think to show GOTMILK as a possibility). Which brings me to another point of the code I would like to add which would be formatting the output to looks nicer. Lastly if I had more time, I would have liked todo this in python and also to have used a dictionary API instead of a text file. 


**Note: I did spend the whole weekend on the other assignment by accident :)
