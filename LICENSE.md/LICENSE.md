// Datum und Zeit.cpp : Definiert den Einstiegspunkt für die Konsolenanwendung.
//

#include "stdafx.h"
#include <iostream>
#include <iomanip>
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
{
	time_t currentTime;
	time(&currentTime);
	printf("%s\n", ctime(&currentTime));

    return 0;
}

