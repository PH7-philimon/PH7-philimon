Write Psedocode that will accept 25 integers and then display in +Ve and -Ve
#include <studio.h>
int main () {
int number;
printf ("Enter a number from 0 to 25");
scanf ("%d",&number);

if(number >0) {
printf ("number is POSITIVE");
}
else {
printf ("number is NEGATIVE");
}
return 0;
}
