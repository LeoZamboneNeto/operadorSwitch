#include <stdio.h>
#include <math.h>

int main() {
    char operador;
    double num1, num2, resultado;

    printf("Digite um operador (+, -, *, /, ^, r): ");
    scanf(" %c", &operador);

    switch (operador) {
        case '+':
            printf("Digite dois números: ");
            scanf("%lf %lf", &num1, &num2);
            resultado = num1 + num2;
            printf("Resultado: %.2lf\n", resultado);
            break;
        case '-':
            printf("Digite dois números: ");
            scanf("%lf %lf", &num1, &num2);
            resultado = num1 - num2;
            printf("Resultado: %.2lf\n", resultado);
            break;
        case '*':
            printf("Digite dois números: ");
            scanf("%lf %lf", &num1, &num2);
            resultado = num1 * num2;
            printf("Resultado: %.2lf\n", resultado);
            break;
        case '/':
            printf("Digite dois números: ");
            scanf("%lf %lf", &num1, &num2);
            if (num2 != 0) {
                resultado = num1 / num2;
                printf("Resultado: %.2lf\n", resultado);
            } else {
                printf("Erro: Divisão por zero!\n");
            }
            break;
        case '^':
            printf("Digite a base e o expoente: ");
            scanf("%lf %lf", &num1, &num2);
            resultado = pow(num1, num2);
            printf("Resultado: %.2lf\n", resultado);
            break;
        case 'r':
            printf("Digite o número para calcular a raiz quadrada: ");
            scanf("%lf", &num1);
            if (num1 >= 0) {
                resultado = sqrt(num1);
                printf("Resultado: %.2lf\n", resultado);
            } else {
                printf("Erro: Número negativo para raiz quadrada!\n");
            }
            break;
        default:
            printf("Operador inválido.\n");
            break;
    }

    return 0;
}
