# DA_Assignment-4.2
Q1 : x<-c('data.science.in.R', 'machine.learning.in.R') Perform the below operaion: Replace the character"." with "-" for each string

Ans: 
> x<-c('data.science.in.R', 'machine.learning.in.R')
> x
[1] "data.science.in.R"     "machine.learning.in.R"
> x1<-gsub("[.]", "-", x)
> x1
[1] "data-science-in-R"     "machine-learning-in-R"

Q2: 2. x <- c('data.science.in.R','machine.learning.in.R')
Perform the below String Operation:
Append again with “-“ minus sign character at the start of the each string and finally concatenate all the
string within the vector to form a final single string and assigning it the object.

Ans: 
> x2<-paste("-", x)
> x2
[1] "- data.science.in.R"     "- machine.learning.in.R"
