# Programa-Principal.java
public class ProgramaPrincipal {
    public static void main(String[] args) {
        Voo voo1 = new Voo(101, "Londrina", "São Paulo", "2023-11-15 10:00", 150);

        // Realizar uma reserva de assento
        if (voo1.reservarAssento()) {
            System.out.println("Assento reservado com sucesso!");
        } else {
            System.out.println("Não há assentos disponíveis.");
        }

        // Exibir informações do voo
        voo1.exibirInformacoes();
    }
}
