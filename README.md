// Task-2-Calculator
#include <iostream>

int main() 
{
    char Operator;
    double number_1, number_2, Result;
    
    std::cout << "Enter the first number: ";
    std::cin >> number_1;
    
    std::cout << "Choose the Operator(/ * - +): ";
    std::cin >> Operator;
    
    std::cout << "Enter the Second number: ";
    std::cin >> number_2;
    
    switch (Operator) {
        case '+':
            Result = number_1 + number_2;
            std::cout << "The Answer Is: " << Result << std::endl;
            break;
            
        case '-':
            Result = number_1 - number_2;
            std::cout << "The Answer Is: " << Result << std::endl;
            break;
            
        case '*':
            Result = number_1 * number_2;
            std::cout << "The Answer Is: " << Result << std::endl;
            break;
            
        case '/':
            Result = number_1 / number_2;
            std::cout << "The Answer Is: " << Result << std::endl;
            break;
            
       /* case '%':
            Result = number_1 % number_2;
            std::cout << "The Answer Is: " << Result << std::endl;
            break;*/
            
        default:
            std::cout << "You Chose invalid operator" << std::endl;
    }
    return 0;
}


