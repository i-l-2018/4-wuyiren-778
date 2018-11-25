#include<stdio.h>
#include<algorithm>
using namespace std;
int main()
{
	int l[]={45676,45345,6767,2342};
	sort(l,l+4);
	for(int i=0;i<4;i++)
		printf("%d ",l[i]);
	printf("\n");
	return 0;
}
