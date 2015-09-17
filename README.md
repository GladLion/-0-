
// 0laba_GLadkiy.cpp : Defines the entry point for the console application.
//

#include "stdafx.h"
#include <iostream>
#include <conio.h>
#include <ctime>
#include <cstdlib>
#include <cstdio>
#include "0laba_GLadkiy.h"

#ifdef _DEBUG
#define new DEBUG_NEW
#endif


using namespace std;

int main (int argc, char* argv[])
{
	int couple = 0;
	srand(time(0));
	double beg = clock();
	const int array_size = 20000;
	int array1[array_size];
	for (int counter = 0;  counter  < array_size;counter++)
	{
		array1[counter] = rand() % 50 - rand() % 50;
		cout << array1[counter] << " ";
		int min = array1[0];
		for  (int counter = 1;  counter < array_size; counter++)
		{
			if (min > array1[counter])
				min = array1[counter];
		}
		beg = clock() - beg;
		cout << "\nmin = " << min << endl;
		if ()
		{
			couple = couple + 1;
			

		}
		printf("4lf", beg / CLOCKS_PER_SEC);
		system("pause");
		return 0;
		
	}
	
}
