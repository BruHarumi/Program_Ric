# Program_Ric

public static Integer calcularSalario(double saldo, double salario, double juros, int anosDevidos) {

final int MESES_EM_UM_ANO = 12;

    int meses = anosDevidos * MESES_EM_UM_ANO; 
  // referente ao 13o. salario de cada ano
    meses += anosDevidos;

  	while (meses > 0) {
  	saldo = saldo + salario;
  	salario = salario * juros;
 	meses = meses - 1;
}

     if (s < 0){
	return null;
	} else {
	return (int) saldo;
	}
}

