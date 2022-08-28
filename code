#include <iostream>
#include <string.h>
using namespace std;
char* join(const char* a, const char* b);
char* joinb(const char* a, const char* b);
int main() {
	cout << join("alpha", "bet") << endl;
	cout << joinb("duck", "soup") << endl;
	return 0;
}

char* join(const char* a, const char* b) {
	int i;
	char* array1 = new char[8];//The length of alphabet using strlen() is 8 so that is the length that we use to define array1.
	for (i = 0; i < 8; i++) {//Initialize array1.
		array1[i] = '\0';
	}
	strcat(array1, a);
	return strcat(array1, b);	
}

char* joinb(const char* a, const char* b) {
	int i;
	char* array2 = new char[9];//The length of "duck soup" using strlen() is 9 so that is the length that we use to define array2.
	for (i = 0; i < 9; i++) {//Initialize array2.
		array2[i] = '\0';
	}
	strcat(array2, a);
	strcat(array2, " ");//We add the space character in the string
	return strcat(array2, b);
}
