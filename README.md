# length-of-string
string in c
#include <stdio.h>
#include <string.h>
#define MAX_SIZE 100
int main()
{
  char text[MAX_SIZE];
  int length;
  printf("Enter any string: ");
  scanf("%s",text);
  length = strlen(text);
  printf("Length of '%s' = %d", text, length);
  return 0;
}
