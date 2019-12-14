# project_3
#include <iostream>
#include <vector>
using namespace std ;
//TODO:
// Write your main program. Remember that all C++ programs need
// a main function. The most important part of your program goes
// inside the main function. 




int main() {
    
    vector<int> vector1(3) ;
   
    vector1[0] = 5 ; 
    vector1[1] = 10  ;
    vector1[2] = 27 ; 
   
   
    for(int i=0 ; i < vector1.size(); i++ )
    {
        cout << vector1[i] << " " ; 
    }
    
    return 0 ;
}
