# Homework14

#include <stdio.h>

int main(){
	int a = 0;
	int b = 0;
	int count = 0;
	printf("Enter the value");
	scanf("%d %d",&a,&b);
	if(a > b){
		int temp = a;
		a = b;
		b = temp;
}	
	for(int i = a; i < b;i++){
		if( i % 5 == 0){
			count++;
}
		printf( "count = %d\n" ,count);
}
	return 0;
}
