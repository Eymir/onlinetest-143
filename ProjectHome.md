To create an online test covering 'x' number of questions from the database using x questions from a question table and x\*6 answers from an answer table..

The question table has fields
Q\_ID, QUESTION, MULTIPLE\_ANS,Q\_MARK

answer table has fields..

ANS\_ID , ANSWER, ANS\_OF\_Q\_ID, ANS\_OF\_CQ\_ID

where qid is the question number (primary key) , question is the question, multiple choice an int saying type of the question. and q\_mark is the mark

ans\_id is the primary key.. answer is the answer, ans\_of\_q\_id is the field denoting which questions answer it is of... ans\_of\_cq\_id is 1 if the answer is correct else 0

..tats it with db design...


now to the asp.net  part...with c#.net


i am planning to use a repeater to hold the questions and answers in the examhall.aspx page...

Thats all for now...

waiting for replys for my first google project..!!