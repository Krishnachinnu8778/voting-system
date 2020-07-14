# voting-system
#include<iostream>
using namespace std;
int main()
{

   
   int age;
   cout<< "enter the age :";
   cin>> age;
   if(age>=18)
   {
    
     cout<< "you are major and you are eligible for voting.";
   }
   else{
   
   cout<< "you are a minor and you are not eligible for voting";
}
return 0;
}
