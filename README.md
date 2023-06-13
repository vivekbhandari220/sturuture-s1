# sturuture-s1
sructure first program
#include<stdio.h>
#include<string.h>
#include<string.h>
//void salting(char newpass[]);
struct student{
int rollno;
float cgpa;
char name[100];
};

int main(){
struct student s1;
s1.rollno=555;
s1.cgpa=99.9;
//s1.name = "vivek";
strcpy(s1.name,"vivek");
printf("roll no of the student is:%d \n",s1.rollno);
printf("cgpa of student is : %f \n",s1.cgpa);
printf("student name : %s \n \n",s1.name);

struct student s2;
s2.rollno=551;
s2.cgpa=55.01;
strcpy(s2.name,"abhishek");
printf(" roll no of the student is :%d \n",s2.rollno);
printf("cgpa of student is : %f \n", s2.cgpa);
printf("student name : %s \n \n",s2.name);

struct student s3;
s3.rollno=552;
s3.cgpa=56.01;
strcpy(s3.name,"karki");
printf("roll no of student is : %d \n",s3.rollno);
printf("cgpa of student is :%f \n",s3.cgpa);
printf(" student name :%s \n\n",s3.name);


return 0;
}








