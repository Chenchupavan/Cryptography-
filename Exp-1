#include<stdio.h>
#include<string.h>
#include<ctype.h>
int main(){
	int k=3;
	char input[1000],cipher[1000];
	printf("Enter input string:");
	scanf("%s",&input);
	printf("Encrytption is : ");
	for(int i=0;i<strlen(input);i++){
		if(islower(input[i])){
			cipher[i]=((input[i]-'a'+k)%26)+'a';	
		}
		else{
			cipher[i]=((input[i]-'A'+k)%26)+'A';	
		}
		printf("%c",cipher[i]);
	}
	printf("\nDecrytption is : ");
	for(int i=0;i<strlen(cipher);i++){
		if(islower(input[i])){
			input[i]=((cipher[i]-'a'-k)%26)+'a';	
		}
		else{
			input[i]=((cipher[i]-'A'-k)%26)+'A';	
		}
		printf("%c",input[i]);
	}
	
}
