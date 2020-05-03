Name of the language- C
      C is one of the most popular programming languages. Most of the users who interest in programming are wondering why this programming language is called just a single alphabet letter. This section is about why this programming language why it is C, not other letters of the alphabet.   
      Why C? Because C comes after B due to the alphabetical order. The author of "C" had already a programming language called B. Some features of B were inadequate and less understandable and less readable. Therefore, the author of the language decided to make the language simpler, understandable, and readable. Therefore, the author of the language called this reorganized language C. Hence, C is a kind of compiled version of B. If you curious about B, "B" is derived from BCPL(Basic Combined Programming Language) which was not available at that time.
Authors of C
     "C" has supported structured programming and recursion. And, it has a static type checking that type of variable is known at compile-time instead of run-time. It is written by  Dennis Ritchie and Ken Thompson.
Dennis MacAlistair Ritchie- is an American scientist. He is known for creating "B", "C", and UNIX.
Kenneth Lane Thompson- is an American scientist. He is known for designing and implementing UNIX operating system. He also created "B" and "C" programming languages. He worked at Google. So, he is also one of the inventors of Go programming languages.
History of C, Why was it invented
     The history of the programming languages C is quite interesting. It was a turbulent time for computer science in the late 1960s at Bell Labs(nowadays known for Nokia Bell Labs). All company researchers focusing on Multics, a time-sharing operating system(Multics also has influenced other modern operating systems.). Later, they thought it would be expensive and time-consuming. However, they didn't give up, they created informal group which is leading by Ken Thompson. Thereafter, the implementation language of Multics did not suit their taste, as they say.
     They were facing some hardware inadequate problems. After that, they achieved the writing Unix system in PDP-7(PDP-7 is a minicomputer produced by Digital Equipment Corporation) assembler. Not long after Unix first ran in PDP-7, in 1969.
     In those years, programmers needed a more useful instruction system, namely programming language, to get better efficiency from their work with the UNIX operating system. Thompson wanted to produce a high-level programming language. Thus, he produced the "B" language that supports the BCPL system programming language. B language examples: 
/*B programming language example*/
main( ) {
   auto a, b, c, sum; /* defining variables, example of typeless enviroment*/
   auto v[10]; /* defining an array*/
   a = 1; b = 2; c = 3;
   sum= a+b+c; /*note that delimiting with curly brackets inherited from BCPL and B is a typeless language,arithmetic on characters is quite legal */
   putchar(’*n’);/* "*n" is new line character*/
   putnumb(sum);/* putnumb is a library function of one argument, print a number on the terminal*/ }
      B's semantic in PDP-7 was sufficient for them. However, they were facing some problems in PDP-11. They decided to change B's semantic model. Also, they had 3 reasons to reorganize "B". The first one is the character handling mechanism which is inherited with a few changes from BCPL. Second is floating-point arithmetic(the original PDP-11 didn't provide floating-point arithmetic. But, the manufacturer said that it would be available soon.). Third one is language rules about pointers. "B" is a typeless programming language that means it has only one data type(e.g. only one data type exists and all data stored in the same type). Authors realized that a typing scheme was necessary to handle charactering, byte addressing, and floating-point. Thereafter, Dennis Ritchie has added data typing for variables and rewrote the compiler for PDP-11 in 1971.  Between 1971 and 1972, rearranged B was named New B (NB), later called "C". 
    In 1973, C became strong enough. At first, Unix was originally written in the assembly language PDP-11/20. After that,  most of the kernel of UNIX was rewritten in "C". Thus, UNIX became one of the first operating systems in which the kernel was not written in an assembly language. 
    On the other hand, the C language was widely used outside of the Bell Lab. So, there was a need for a resource on how to use "C". Thereafter, the book called "C programming language " published which was written by Brian Kernighan and Dennis Ritchie. So, it became a great resource for "C". Later, this book was called K&R(initials letters for the name of authors) by the programmers of C. It is also known as the holy book of the C language.
    The second edition of the books covers ANSI C standard. And, K&R introduced several languages feature. It's described below:
1.struct data type added
2.long int data type added
3.unsigned int data type added
4. And, =+ operator changes to += operator. = + C was confusing programmers.
Also, note that like  Java, C#, and C++ languages derived from "C".

When/why shall we use C
     C is widely used by programmers. But, why important? Why you should learn C? When do you need to use C? What is the benefit of C? These questions' answers described below.
                               Benefits of C language
•	C programming language is a small language. The concepts that it requires is quite short . It has 32 keywords in ANSI C so, it is easy to remember.
•	C has features of both low-level languages and high-level languages. For example, you use low-level programming features like kernel in the operating system and you can use high-level programming features like the software application.
•	C is more convenient to develop the operating system. For example,  Windows kernel mostly written in C. OS X also mostly written in C. Including IOS, Android, Windows phones.The most popular database mostly coded in  C (e.g. MySQL, Oracle databases, PostgreSQL).
•	Programs written in C are more readable, understandable, and writable.
•	C is widely used for embedded system programming. Maybe you noticed, the syntax of Arduino is very close to C.
•	C language is free, and you do not have to pay anythingC has been around 35 years so, there is a lot of resources to learn the language.
•	C is a basic language that can give you how programming looks like. You know what things like register, stack, heap and memory mapped IO mean.
•	The use of algorithms and data structures makes programs very fast, especially for complex calculations.
       We saw the benefits of C and answered some questions. Some people think that C is an old language so, there is no need to learn C. However, it is wrong. Learning C at least gives an idea of what is programming and you'll know some programming basics. C is great especially if you are developing an operating system and embedded system.
       
       
 How to setup an environment to use it in different platforms (windows, mac, linux)
 
For windows OS, you can download dev cpp 5.11 version using this site https://sourceforge.net/projects/orwelldevcpp/files/latest/download and then configure dev cpp setup. After installing, you can change font, color in the first step.

For mac OS, you can download c compiler in Appstore. The name of c-compiler is Xcode in mac. Also, you can run code in the terminal.this command is gcc -o {program} {program.c}
the second way you can install gcc compiler which is you can run code using a text editor and terminal . open browser and you enter https://brew.sh/  site and copy this command "/bin/bash -c "$(curl fsSLhttps://raw.githubusercontent.com/Homebrew/install/master/install.sh)" ". After download is finished, you write this command "brew install gcc.

For Linux operating systems, you can download gcc using terminal.And write sudo apt-get install gcc or you can download using this command sudo apt-get instal build essential. It downloads all required libraries. To running C code write gcc {c-file} -o {createdfile.out}.And you can see that there is new file with .out extension. and write "./{createdfile}.out .You can see the output of code

Example codes
Fisrt example
#include <stdio.h>
#include <string.h>

// Example about struct 
struct profile{
	char name[25];
	char surname[25];
	int age;
	int id;
}profil2;



int main(){
	
 struct profile profil1;
 
 strcpy(profil1.name,"Mustafa");
 strcpy(profil1.surname,"Celik");
 profil1.age=24;
 profil1.id=7;


 
 printf("%s %s %d %d\n",profil1.name,profil1.surname,profil1.age,profil1.id);	
 
	struct profile *profile2Address;
strcpy(profil2.name,"Mustafa");
 strcpy(profil2.surname,"Celik");
 profil2.age=32;
 profil2.id=46;
//using pointer
 profile2Address=&profil2;

printf("%s %s %d %d",profile2Address->name,profile2Address->surname,profile2Address->age,profile2Address->id);
	


}


Second example

#include <stdio.h>
#include <string.h>
//Reverse a char array example
//For example, word is programming ,reverse is gnimmargorp
//find lengths
int length(char a[] ){
int length=0;
for(int i=0;a[i]!='\0';i++){

length++;
}
return length;
}
//also can use strlen() instead of above method

void reverse(char word[]){

int len=length(word);
	for(int i=0;i<len/2;i++){
	   int temp=word[i];
	   word[i]=word[len-i-1];
	   word[len-i-1]=temp;
	
	}
	
}
int main(){
	
 char word[200];
 scanf("%s",word);
 reverse(word);
 printf("%s",word);

return 0;

}

Third example

#include <stdio.h>
//example about pointer
int main()
{
   int *ptr, q;
   q = 50;
 
   ptr = &q;
   
 // address of q in hex
   printf("%p\n", ptr);
   //address of ptr in decimal
   printf("%d\n",ptr);
   //value of q
   printf("%d",q);
   return 0;
}

Fourth example:

#include <stdio.h>
#include <string.h>
//Example about file i/o
int main(){
FILE *fp=fopen("PLadfg.txt", "a+");
char text[30]="Programming Language ";
char user[100];
//find length of string
int length= strlen(text);
if( fp==NULL){
printf("File does not create");
}
else{
	printf(" Write");
	fgets(user,100,stdin);
	for(int i=0;i< length;i++){
		fputc(text[i],fp);
	printf("%c",text[i]);	}
	
	fputs(user,fp);
	
printf("\nFile crated sucessfully");
fclose(fp);

}
return 0;	
}





-Things that are specific to this language?
1.Pointer is the address of a variable. Pointer can be any datatype e.g float, char, int, long, etc. For example, we have int a=5; pointer shows that address of 5 in ram. The syntax of a pointer is int *ap. It is used ampersand (&) to show address in memory.Final syntax of a pointer is int *ap=&a;  If pointer return null, it means nothing or does not mean anything in memory. There is two way to print pointer. These are %p and %d. %p shows number in hexadecimal .%d shows number in decimal. For example, using the pointer,  we can learn the memory between two variables.
2.The sizeof() function calculates the size of datatype in bytes. It can be changed in your device.  For example,  sizeof() return 4 bytes for integer in 64-bit operating system. But this byte change in 32-bit operating system. The syntax is "sizeof(datatype)"

3.There is some important method for memory allocation. For example, When you write array, this is static and sometimes array size is not enough. However, you can write an array as dinamically. This method is malloc. It takes one parameter and syntax is malloc(n*sizeof(int)).if you write n* sizeof,then malloc provides n bytes allocated memory. revoke malloc when you need memory blocks. Another method is free() that used with malloc or calloc because malloc or calloc is not de-allocated by themselves. It means that free() is de-allocated memory.calloc is same as malloc but it differs from some points with malloc.Calloc takes two parameter and syntax is calloc(n,sizeof(int)). n shows allocated memory as malloc is the same in calloc method. Also, calloc has zero values. 
Instead, malloc has garbage values. It means that calloc is zero initialization but malloc does not initialization. However, malloc is faster than calloc.
Another method is realloc. It means re-allocation. It is used to update values in malloc, calloc, or realloc. This method increase or decrease memory allocation.If there is no enough memory, it returns null. However, old memory blocks is not released. 

4.The size of the character array is 10. but we only wrote a part of 5. Then it automatically sets the last character to '/ 0'. It does this so that it understands where the last character ends. In short, the last character is / 0 automatically set which is null character.For example, we have char array; char arr [10] = "Hello".It looks like "Hello/0"




