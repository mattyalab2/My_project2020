Health management System : Check health knowlege and your condition.  
This system output the question that computer randomly selected.

・quiz.txt  
There are many quiestions, are holding 3 elements in quiz.txt file

format
-------------------------------  
No True_number  
Question[1: , 2: , 3:]  
True or False
-------------------------------  

・function.h  
include each function  
1.checkfilename(char* name)  
2.resetfile(char* name, int thismonth, int quizlen)  
3.txt2csv(char* name, int lastlogmonth)  
4.getQuizNumber(char* name, int len, int* lastlogmonth)  
5.getQuizArray(char QuizArray[][BUFSIZE], int CorrectAnsArray[])   
6.getMonth()  


HealthQuiz.cpp  
this is system controller.

![HealthManagement](https://user-images.githubusercontent.com/75316867/107142349-b42cfc00-6971-11eb-85e8-598f1fb2fadf.png)
