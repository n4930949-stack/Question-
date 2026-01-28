# Question-
#include <iostream>
using namespace std;

int main()
{
int num=1;
while (num<=10)
{
cout << num << " ";
num++;
} cout << endl;
return 0;
}
Q2:
#include<iostream>
using namespace std;
struct student{
int roll_no;
string name;
int marks;
};
int main(){
student s1, s2; // Added semicolon
s1.roll_no=1012;
s1.name="huma";
s1.marks=595;
s2.roll_no=3595;
s2.name="sidra";
s2.marks=890; // Corrected variable name
cout<<"details for student 1:"<<endl;
cout<<"Roll no: "<<s1.roll_no<<endl; // Added colon for clarity
cout<<"Name: "<<s1.name<<endl; // Added colon for clarity
cout<<"Marks: "<<s1.marks<<endl; // Added colon for clarity
cout<<"details for student 2:"<<endl;
cout<<"Roll no: "<<s2.roll_no<<endl; // Added colon for clarity
cout<<"Name: "<<s2.name<<endl; // Added colon for clarity
cout<<"Marks: "<<s2.marks<<endl; // Added colon for clarity
cout<<"student name whose marks are maximum: "<<endl;

// Logic to check which student has more marks
if (s1.marks > s2.marks) {
    cout<<"Name: "<<s1.name<<" Marks: "<<s1.marks<<endl;
} else {
    cout<<"Name: "<<s2.name<<" Marks: "<<s2.marks<<endl;
}

return 0;
}
