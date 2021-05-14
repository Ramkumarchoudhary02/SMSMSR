# smsmsr
#include <iostream>
int main7()
{
	
	std::cout << " enter two numbers " << std::endl;
	int v1 = 0, v2 = 0;
	std::cin >> v1 >> v2;
	int val = v1;
	while (val <= v2) {
		std::cout << val << std::endl;
		++val;
	}
	return 0;
}
