#include<iostream>
using namespace std;
int compare(const void *a, const void *b)
{
	return *((int *)a) % 10 - *((int *)b) % 10;
}
void main()
{
	int m[5] = { 4,18,19,23,25 };
	qsort(m, 5, sizeof(int), compare);
	for (auto &i : m)
		cout << i<<'\t';
	getchar();
}
