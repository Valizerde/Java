# Java
Aula 1

import javax.swing.JOptionPane;

public class Exemplo {

    public static void main(String[] args) {
        // Declaração de variaveis
        String nome, cargo; 
        int matricula;
        double salario;
        
        //Cadastrar os valores
        nome = JOptionPane.showInputDialog("Qual o seu nome");
        cargo = JOptionPane.showInputDialog("Qual o seu cargo");
        matricula = Integer.parseInt( JOptionPane.showInputDialog("Qual sua matrícula") );
        salario = Double.parseDouble( JOptionPane.showInputDialog("Qual o seu salario") );
       
    }
    
}
