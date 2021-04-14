//A importância de R$ 780.000,00 será dividida entre três
//ganhadores de um concurso. Sendo que da quantia total:
//O primeiro ganhador receberá 46%;
//O segundo receberá 32%;
//O terceiro receberá o restante;



#include <stdio.h>
#include <stdlib.h>

int main (){
        const int premio = 780000;
        float Ganhador1;
        float Ganhador2;
        float Ganhador3;
        
        Ganhador1 = (46 * premio)/100;
        Ganhador2 = (32 * premio)/100;
        Ganhador3 = (22 * premio)/100;
        
        printf ("valor q cada participante levara para casa:\n ganhador 1 = %.2f,\n ganhador 2 = %.2f,\n ganhador 3 = %.2f,\n",
        Ganhador1, Ganhador2, Ganhador3);
        
}
