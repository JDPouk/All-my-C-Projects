#include "stdafx.h"
#include <iostream>

int doubleNumber(int x)
{
	return x*2;
}

int main()
{
	using namespace std;
	cout << "Enter a number to be doubled" << endl;
	int x;
	std::cin >> x;
	std::cout << "Youe doubled number is: " << doubleNumber(x) << std::endl;
	return 0;
}
	std::cin.get();
        std::cout << "Press ENTER to continue..." << std::flush;
	std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
