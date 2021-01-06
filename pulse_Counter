#include <iostream>
#include <windows.h>
#include <time.h> 
#include <stdlib.h>
using namespace std;

void delay(int number_of_seconds) {
	int milli_seconds = 1000 * number_of_seconds;
	clock_t start_time = clock();
	while (clock() < start_time + milli_seconds);
}

int main() {
	int loops; int i; int I2; int I6;
	do {
		cout << "\n\nhow many loops: ";
		cin >> loops;
		do {
			for (int i = 0; i < loops; i++) {
				cout << "\nI6: "; cin >> I6;
			}
			if (I6 == 1) {
				cout << "\nlamp aan";
				cout << "\n\nI2: "; cin >> I2;
				if (I2 == 0) {
					cout << "\nlamp blijft 5 sec 'aan' loopen.";
					for (i = 0; i < 2; i++) {
						delay(1);
						cout << "\n"; cout << i + 1;
						for (i = 1; i < 3; i++) {
							delay(1);
							cout << "\n"; cout << i + 1;
							for (i = 2; i < 4; i++) {
								delay(1);
								cout << "\n"; cout << i + 1;
								for (i = 3; i < 5; i++) {
									delay(1);
									cout << "\n"; cout << i + 1;
								}
							}
						}
					}
				} else if (I2 == 1) {
					cout << "\nlamp gaat uit.";
				}
			} else {
				exit(0);
			}
		} while(i < loops);
	} while(true);
	return 0;
}
