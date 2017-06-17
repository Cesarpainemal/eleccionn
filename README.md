# eleccionn
package borrador;

import java.util.Scanner;

public class Elecciondeedificio {

    public static void main(String[] args) {
       
        int resultado = 0;
        int edificio = 0;
        int cara = 1;
        int cruz = 2;

        Scanner entrada = new Scanner(System.in);

        while (resultado != cara) {
            System.out.println("Eliga [1] Cara -- [2]Cruz");
            resultado = entrada.nextInt();
            if (resultado == cruz) {
                edificio++;
            } else if (edificio == 0) {
                System.out.println("encontre una mesa en el ra");
            } else if (edificio == 1) {
                System.out.println("encontre una mesa en r1");
            } else if (edificio == 2) {
                System.out.println("Encontre una mesa en d");
            } else if (edificio == 3) {
                System.out.println("Mesa E");
            } else if (edificio == 4) {
                System.out.println("Mesa DIS");
            }

        }

    }
}

--------------------------------------------------------------------

ackage eleccion;



public class Moneda {
    private int cara;
    private int cruz;
    
    public Moneda(int cara , int cruz) {
        this.cara = cara;
        this.cruz = cruz;
    }

    public int getCara() {
        return cara;
    }

    public int getCruz() {
        return cruz;
    }

  
}

