- 👋 Hi, I’m @TioFlash13
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
TioFlash13/TioFlash13 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import java.util.Scanner;

public class BonusSalarial {
	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		
		System.out.println("Digite o fautramento do ano passado: ");
		Double faturamentoDoAnoPassado = scanner.nextDouble();
		
		System.out.println("Digite a meta de faturamento do ano passado: ");
		Double metaFaturamento = scanner.nextDouble();
		
		System.out.println("Digite a média salarial do funcionário: ");
		Double mediaSalarialFuncionario = scanner.nextDouble();
		
		Boolean metaBatida = faturamentoDoAnoPassado >= metaFaturamento;
		
		Double faturamentoParcial = metaFaturamento * 80 / 100;
		
		Boolean MetaParcial = faturamentoDoAnoPassado == faturamentoParcial;
		
		if (MetaParcial) {
			
			Double BonusSalarial = mediaSalarialFuncionario + mediaSalarialFuncionario;
			
			System.out.println(" Seu salário com o bônus total será de: " +);
		}
		if (MetaParcial) {
			
			Double BonusSalarialParcial = mediaSalarialFuncionario * 80 / 100;
			
			Double BonusSalarialIncompleto = mediaSalarialFuncionario + BonusSalarialParcial;
			
			System.out.println("O seu salário com o bônus parcial será de: " + BonusSalarialIncompleto);
		}
		
		scanner.close();
	}

}
