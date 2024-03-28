#include <iostream>

int main() {
  
  std::string dog_name; //entering the dog's name
  std::cout << "Enter your dog's name: ";
  std::cin >> dog_name;

  double dog_age; // entering the dog's age
  std::cout << "Enter your dog's age: ";
  std::cin >> dog_age;

  double early_years;
  double later_years;
  double human_years;
  early_years = 21; // this variable shows the first 2 years of a dog's life counting as 21 human years
  later_years = (dog_age - 2)*4; // this variable shows each following year counts as 4 human years
   if (dog_age < 2) {
    early_years = (early_years / 2) * dog_age;
    later_years = 0;
  }


  human_years = early_years + later_years; // this variable shows the total number of human years for the dog.
  std::cout << "My name is " << dog_name << "! Ruff ruff, I am " << human_years << " years old in human years. \n";

}


 

