# digital-clock
#include <iostream>
#include <stdlib.h>
#include <time.h>
#include <unistd.h>  
 

using namespace std;

int main() 
{
  int hour, min, sec;
  cout <<"Enter current time: "<<endl;
  cin >>hour>>min>>sec; 
    if(hour > 24) 
    {
        cout <<"Wrong Time input";
    }
    else if (min > 60)
    {
        cout <<"Wrong Time Input";
    }
    else if (sec > 60)
    {
        cout <<"Wrong Time Input";
    }
    else 
    {
    while (1)
    {
      for(hour; hour<24; hour++ )
      {
      for(min; min<60; min++)
      {
      for(sec; sec<60; sec++)
      {
          cout <<"\nreal time g: ";
          cout <<"\n->"<<hour<<":"<<min<<":"<<sec<<"Hrs";
          sleep(1);
      }
     sec = 0;
     }
    min = 0;
   }   
 }
}
}
