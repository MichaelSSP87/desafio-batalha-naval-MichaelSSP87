#include <stdio.h>

int main() {
    // Declaração do tabuleiro como uma matriz 5x5
    int tabuleiro[5][5];

    // Inicializa todas as posições do tabuleiro com 0 para indicar que estão vazias.
    for (int i = 0; i < 5; i++) {
        for (int j = 0; j < 5; j++) {
            tabuleiro[i][j] = 0;
        }
    }

    // --- Posicionamento do Navio Vertical (3 partes) ---
    // Posição inicial: (1, 2)
    int navioVerticalX = 1;
    int navioVerticalY = 2;

    // Marcando as partes do navio no tabuleiro com o valor 1
    tabuleiro[navioVerticalX][navioVerticalY] = 1;      // Parte 1
    tabuleiro[navioVerticalX + 1][navioVerticalY] = 1;  // Parte 2
    tabuleiro[navioVerticalX + 2][navioVerticalY] = 1;  // Parte 3

    // --- Posicionamento do Navio Horizontal (2 partes) ---
    // Posição inicial: (4, 0)
    int navioHorizontalX = 4;
    int navioHorizontalY = 0;

    // Marcando as partes do navio no tabuleiro com o valor 1
    tabuleiro[navioHorizontalX][navioHorizontalY] = 1;      // Parte 1
    tabuleiro[navioHorizontalX][navioHorizontalY + 1] = 1;  // Parte 2

    // --- Exibição das Coordenadas dos Navios ---
    printf("=== Batalha Naval - Nivel Novato ===\n");
    
    // Exibe as coordenadas do navio vertical
    printf("\nNavio Vertical posicionado nas coordenadas:\n");
    printf("(%d, %d)\n", navioVerticalX, navioVerticalY);
    printf("(%d, %d)\n", navioVerticalX + 1, navioVerticalY);
    printf("(%d, %d)\n", navioVerticalX + 2, navioVerticalY);

    // Exibe as coordenadas do navio horizontal
    printf("\nNavio Horizontal posicionado nas coordenadas:\n");
    printf("(%d, %d)\n", navioHorizontalX, navioHorizontalY);
    printf("(%d, %d)\n", navioHorizontalX, navioHorizontalY + 1);

    return 0;
}
