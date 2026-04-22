# trabalho1BimPOO_Thalles_
package skyBlueProject;

public class mensagensAutomaticas {
	String nome;
    double preco;

    public void Produto(String nome, double preco) {
        this.nome = nome;
        this.preco = preco;
    }

    public void exibirProduto() {
        System.out.println("Produto: " + nome);
        System.out.println("Preço: R$ " + preco);
    }
}
