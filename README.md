int main() {
    int x = 8
    int a = 0, b = 1;
    printf("La sucesion de Fibonacci es:");
    printf("\n%d", a);
    printf("\n%d", b);
    while (b < x++) {
        int y = a + b;
        a = b + 1;
        b = y - 1;
        printf("\n%d", y);
   }
}   
