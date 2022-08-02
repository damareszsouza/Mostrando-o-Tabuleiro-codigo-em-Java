# Mostrando-o-Tabuleiro-codigo-em-Java

Mostrando o Tabuleiro
O método mostraTabuleiro será bem simples: devemos percorrer o vetor e mostrar cada uma de suas posições na tela. Mostraremos um espaço em branco entre cada posição, para facilitar a visualização das letras e também deixaremos uma linha em branco após o tabuleiro. O código do método é mostrado abaixo.



static void mostraTabuleiro(char[] tabuleiro) {

       for(int cont = 0; cont < tabuleiro.length; cont++) {

             System.out.print(tabuleiro[cont]);

             System.out.print(“ ”);

       }

       System.out.println();

}
