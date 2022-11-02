# odev1-soru1

#include <stdio.h>
#include <time.h>
#include <conio.h>


int main(){
	int sum = 0;
	for(int i = 0; i<1000; i++){
		if(i%3 == 0 || i%5 ==0){
			sum += i;
		}
	}
	
	printf("toplam = %d",sum);
	
	return 0;
}
