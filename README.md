
//Loop Basics.
#include <iostream>

using namespace std;

int main()
{
    int i = 0;
    
    for(int i = 0; i < 5; i++){
        std::cout << i << " ";  
    }
    std::cout << std::endl;
    
    i = 0;
    
    while(i < 5){
        std::cout << i << " ";
        ;
    }
    std::cout << std::endl;
    return 0;
}
