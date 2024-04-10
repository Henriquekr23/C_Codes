#include <stdio.h>

#define COLOR_BOLD "\e[1m"
#define COLOR_OFF "\e[m"

int peso, next, idade;
float altura, imc;
int main(void){

    printf("CALCULADORA IMC:\n");
    do{
    printf("Qual a sua idade?\n");
    printf("Resposta: ");
    scanf("%d", &idade);

    if(idade <= 5){
        printf("Muito novo para calcular IMC.\n");
        return 0;
    } else if(idade >= 110){
        printf("Voce esta vivo?\n");
        return 0;
    }

    printf("Digite seu peso em KG:\n");
    printf("Resposta: ");
    scanf("%d", &peso);

    printf("Qual a sua altura em M?\n");
    printf("Resposta: ");
    scanf("%f", &altura);

    printf("--------\nPeso: %d, Altura: %.2f.\n", peso, altura);
    printf("As informacoes estao corretas?\n (1)SIM\n (2)NAO\n");
    printf("Resposta: ");
    scanf("%d", &next);

    }while (next == 2);
    altura = altura*altura;
    imc = peso/altura;
    printf("--------\nIMC: %.2fkg/m2.\n", imc);

//IMC CRIANCA

        if (idade >= 6 && idade <= 9){
            if (imc >= 14.50 && imc <= 15.99){
                printf("Peso adequado\n");
                printf("Tudo indica que esta tudo bem, mas e importante avaliar outros parametros da composicao corporal, para compreender se estao dentro do recomendado.\n");
            } else if (imc >= 16.00 && imc <= 18.99){
                printf("Sobrepeso\n");
                printf("O sobrepeso esta associado ao risco de doencas como diabetes e hipertensao. Entao, atencao! Consulte um medico e reveja habitos para reverter o quadro.\n");
            } else if (imc >= 19){
                printf("Obesidade\n");
                printf("E importante buscar orientação medica e nutricional para entender melhor o seu caso, mesmo que os exames (colesterol e glicemia, por exemplo) estejam normais.\n");
            } else if (imc <= 14.49){
                printf("Baixo peso\n");
                printf("E recomendado procurar um medico para avaliacao criteriosa do resultado.\nPode indicar um estado de consumo do organismo, com poucas reservas e riscos associados.\n");
            }
        } else if(idade >= 10 && idade <= 15){
            if (imc >= 16.50 && imc <= 20.99){
                printf("Peso adequado\n");
                printf("Tudo indica que esta tudo bem, mas e importante avaliar outros parametros da composicao corporal, para compreender se estao dentro do recomendado.\n");
            } else if (imc >= 21.00 && imc <= 23.99){
                printf("Sobrepeso\n");
                printf("O sobrepeso esta associado ao risco de doencas como diabetes e hipertensao. Entao, atencao! Consulte um medico e reveja habitos para reverter o quadro.\n");
            } else if (imc >= 24.00){
                printf("Obesidade\n");
                printf("E importante buscar orientação medica e nutricional para entender melhor o seu caso, mesmo que os exames (colesterol e glicemia, por exemplo) estejam normais.\n");
            } else if (imc <= 16.49){
                printf("Baixo peso\n");
                printf("E recomendado procurar um medico para avaliacao criteriosa do resultado.\nPode indicar um estado de consumo do organismo, com poucas reservas e riscos associados.\n");
            }
        }

//IMC ADULTO

    if (idade >= 16 && idade <= 59){
        if (imc <= 18.49){
            printf("Baixo peso\n");
            printf("E recomendado procurar um medico para avaliacao criteriosa do resultado.\nPode indicar um estado de consumo do organismo, com poucas reservas e riscos associados.\n");
        } else if (imc >= 18.50 && imc <= 24.99){
            printf("Peso adequado\n");
            printf("Tudo indica que esta tudo bem, mas e importante avaliar outros parametros da composicao corporal, para compreender se estao dentro do recomendado.\n");
        } else if (imc >= 25.00 && imc <= 29.99){
            printf("Sobrepeso\n");
            printf("O sobrepeso esta associado ao risco de doencas como diabetes e hipertensao. Entao, atencao! Consulte um medico e reveja habitos para reverter o quadro.\n");
        } else if (imc >= 30.00 && imc <= 34.99){
            printf("Obesidade Grau I\n");
            printf("E importante buscar orientação medica e nutricional para entender melhor o seu caso, mesmo que os exames (colesterol e glicemia, por exemplo) estejam normais.\n");
        } else if (imc >= 35.00 && imc <= 39.99){
            printf("Obesidade Grau II\n");
            printf("Indica um quadro de obesidade mais evoluido em relacao a classificacao anterior e, mesmo com exames laboratoriais dentro da normalidade,\nnao se deve atrasar a busca por orientacao medica e nutricional.\n");
        } else if (imc >= 40.00){
            printf("Obesidade Grau III\n");
            printf("Nesse ponto, a chance de ja estarmos diante de outras doencas associadas e mais elevada. E fundamental buscar orientacao me dica.\n");
        }
    
//IMC IDOSO

    } else if (idade >= 60 && idade <= 110){
        if (imc <= 21.99){
            printf("Baixo peso\n");
            printf("E recomendado procurar um medico para avaliacao criteriosa do resultado.\nPode indicar um estado de consumo do organismo, com poucas reservas e riscos associados.\n");
        } else if (imc >= 22.00 && imc <= 26.99){
            printf("Peso adequado\n");
            printf("Tudo indica que esta tudo bem, mas e importante avaliar outros parametros da composicao corporal, para compreender se estao dentro do recomendado.\n");
        } else if (imc >= 27.00 && imc <= 29.99){
            printf("Sobrepeso\n");
            printf("O sobrepeso esta associado ao risco de doencas como diabetes e hipertensao. Entao, atencao! Consulte um medico e reveja habitos para reverter o quadro.\n");
        } else if (imc >= 30.00){
            printf("Obesidade Grau\n");
            printf("E importante buscar orientação medica e nutricional para entender melhor o seu caso, mesmo que os exames (colesterol e glicemia, por exemplo) estejam normais.\n");
        }
    }
    printf("--------\n");
    return 0;
}
