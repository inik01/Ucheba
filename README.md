#include <iostream>
int main (void)
{
  double value;
 
  std::cout << "Введите количество см: ";
  std::cin >> value;
 
  std::cout << "Дюймов: " << value / 2.54 << std::endl;
  std::cout << "Вершков: " << value / 4.445 << std::endl;
  std::cout << "Футов: " << value / 30.48 << std::endl;
 
  return 0;
}
