#include <iostream>
#include<stdlib.h>
#include<time.h>

using namespace std;

// PROTOTIPO DE LA FUNCION
int tirar(int[]);
void jugar(int[], int);

int main()
{
    srand(time(NULL));
     const int cantJugadores=3; // MODIFICAR: eliminar "const" y J tendrá el valor q se ingrese por consola

  //  cout << "Cantidad de Jugadores:";
   // cin >> J;
    int cantTiros = 0;
    int tiro[5]; //tirada de dados
    int grilla[11][cantJugadores];
    /*
    [0]= 1*
    [1]= 2*
    [2]= 3*
    [3]= 4*
    [4]= 5*
    [5]= 6*
    [E]= Escalera --> Servida: 25 , Armada: 20 
    [F]= Full --> Servido: 35 , Armado: 30
    [P]= Poker --> Servido: 45 , Armado: 40
    [G]= Generala: 50
    [DG]= Dobre Generala: 100
    
    GENERALA SERVIDA = GANA
    */
    for (int ronda = 1; ronda <= 11; ronda++) { // 11 RONDAS donde los jugadores tiran sus dados por turnos
        cout << endl << "RONDA" << ": " << ronda << endl;

        for (int jugador = 1; jugador <= cantJugadores; jugador++) { //se realiza tantas veces como jugadores haya

            cout << endl<< "Jugador" << ": " << jugador << endl;
            cantTiros = tirar(tiro);                      //se ejecuta el tiro

            for (int i = 0; i < 5; i++)                   // muestra resultados
                cout << "dado " << i + 1 << ":" << tiro[i]<< endl;

            cout << "con " << cantTiros << endl;         //muestra en cuantos tiros 

            jugar(tiro, jugador); //juego según resultados del tiro

        }
    }
    
}

int tirar(int juego[]) { //tiene 3 tiros max


    int num = 0;
    int tiros = 0;


    for (int i = 0; i < 5; i++) {//5 dados
        num = 1 + rand() % 6;
        juego[i] = num;
    }
    tiros = 1 + rand() % 3;

    return tiros;
}

void jugar(int juego[], int jugador) {
    //evalúa jugada
    // primero ordenamiento por burbujeo
    // si todos son distintos y son consecutivos--> ESCALERA O SERVIDA O ARMADA
    // si todos son iguales && cantTurnos==1 --> GANAA
    // si todos son iguales && cantTurnos!=1--> GENERALA O ARMADA O DOBLE 
    // 

    
    
    // calcula puntos
    //carga los puntos en la grilla
}
