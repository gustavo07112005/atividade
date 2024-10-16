package produtos;

public class Principal {

		public static void main(String[] args) {
	        Estadual produtoEstadual = new Estadual("Produto Estadual", 200.0);
	        Nacional produtoNacional = new Nacional("Produto Nacional", 200.0);
	        Importado produtoImportado = new Importado("Produto Importado", 200.0);

	        System.out.printf("Valor final do %s: %.2f%n", produtoEstadual.getDescricao(), produtoEstadual.calcularValorFinal());
	        System.out.printf("Valor final do %s: %.2f%n", produtoNacional.getDescricao(), produtoNacional.calcularValorFinal());
	        System.out.printf("Valor final do %s: %.2f%n", produtoImportado.getDescricao(), produtoImportado.calcularValorFinal());
	    }

	}


