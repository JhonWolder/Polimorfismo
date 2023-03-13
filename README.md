class Main {
  public static void main(String[] args) {
    Quadrado q1 = new Quadrado();
    q1.desenhar(); 

    Circulo c1 = new Circulo();
    c1.desenhar();
  }
}

class Circulo extends Poligono {
  public void desenhar(){
    System.out.println("Desenhando Circulo");
  }
}


class Poligono {
  public void desenhar(){
    System.out.println("Desenhando Poligono");
  }
}


class Quadrado extends Poligono {
  public void desenhar(){
    System.out.println("Desenhando quadrado");
  }
}


