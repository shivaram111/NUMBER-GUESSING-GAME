#include <iostream>
#include <cstdlib>
#include <ctime>
using namespace std;

int main() {
    srand(time(0)); // Seed random number generator
    int numberToGuess = rand() % 100 + 1; // Random number between 1 and 100
    int userGuess;
    
    cout << "Welcome to the Number Guessing Game!" << endl;
    cout << "Guess a number between 1 and 100: ";

    do {
        cin >> userGuess;
        
        if (userGue
