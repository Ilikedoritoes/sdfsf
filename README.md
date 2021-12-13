#include <stdio.h>
#include <stdlib.h>

void main()
{
	int grades[5];
	int index = 0;
	printf("enter 5 grades\n");
		for (index = 0; index < 5; index++)
	{
		scanf("%d\n", &grades[index]);
	}

	
		printf("grades are %d %d %d %d %d\n", grades[0], grades[1], grades[2], grades[3], grades[4]);
		printf("%d \n", grades[????]);
		system("pause");
}
