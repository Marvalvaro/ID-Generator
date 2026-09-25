#include <stdio.h>

int main() {
    char name[30];
    int age;
    char city[30];
    char color[30];
    char id[30];

    scanf("%[^\n]", name);
    getchar();
    scanf("%d", &age);
    getchar();
    scanf("%[^\n]", city);
    getchar();
    scanf("%[^\n]", color);

    int number1 = 1000 - (age * 5); 
    int number2 = city[0] + color[0] + 50;
    int number3 = city[0] - color[0] + 200;

    sprintf(id, "%c%d%c%d%c%d", name[0], number1, city[0] , number2, color[0], number3);

    printf("-----------------------------------------\n");
    printf("|                                        \n");
    printf("|  ID             : %s\n", id);
    printf("|  Name           : %s\n", name);
    printf("|  Age            : %d\n", age);
    printf("|  City           : %s\n", city);
    printf("|  Favorite Color : %s\n", color);
    printf("|                                        \n");
    printf("-----------------------------------------\n");

    return 0;
}
