//  C++ Program that uses pointers and arrays 
      
   #include <iostream>
   using namespace std;
   
   int main()
   {
           int numbers[5]; // Sets up an integer and array
           int *p;
          int n;
          p = numbers;    // numbers = p; is not valid because arrays operate as a constant pointer
  
          for(*p = 10 ;*p <= 20; *p++)
          {
                  for(n=0; n<5; n++)
                  {
                          cout << numbers[n] << ", ";
                  }
          }
  
  return 0;
  }
