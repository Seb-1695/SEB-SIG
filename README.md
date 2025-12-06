Algoritmo mi_primer_codigo
	contador=0
	suma=0
	Repetir
		leer x
		Si contador == 0 Entonces
			min=x;
			max=x;
		Fin Si
		Si x<min Entonces
			min=x
		SiNo
			si x>max y x<>0 Entonces
				max=x
			FinSi
		FinSi
		si x<>0 Entonces
			contador=contador+1
		FinSi
		suma=suma+x
	Hasta Que x==0
	imprimir "el promedio es:",suma/contador, " el max es:",max, " y el min es:",min
FinAlgoritmo
