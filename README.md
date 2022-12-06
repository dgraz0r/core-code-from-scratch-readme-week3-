# core-code-from-scratch-readme-week3-

## SIMPLE CALCULATOR

Algoritmo SimpleCalc
	
	Escribir " ----------- CALCULADORA ---------- "
	Escribir  ""
	Escribir "Ingrese primer numero"
	Leer num1
	Escribir "Ingrese segundo numero"
	Leer num2
	Escribir "Seleccione una operacion a realizar"
	Escribir "1. SUMA"
	Escribir "2. RESTA"
	Escribir "3. MULTIPLICACION"
	Escribir "4. DIVISION"
	Leer opr
	Segun opr Hacer
		1:
			Escribir "Procesando ", num1, " + ", num2
			sum <- num1 + num2
			Escribir "Resultado: ", sum
		2:
			Escribir  "Procesando ", num1, " - ", num2
			res <- num1 - num2
			Escribir  "Resultado: ", res
		3:
			Escribir  "Procesando ", num1, " * ", num2
			mult <- num1 * num2
			Escribir  "Resultado: ", mult
		4:
			Escribir "Procesando ", num1, " / ", num2
			div <- num1 / num2
			Escribir  "Resultado: ", div
			
		De Otro Modo:
			Escribir "Error la operacion no es valida"
	Fin Segun
	
		
FinAlgoritmo

## SPECIAL NUMBER

Algoritmo specialNumber
	
	Escribir "Ingrese un numero: "
	Leer n
	Si n == 100 Entonces
		Imprimir 'This is a special number'		
	SiNo
		Si (n < 1000) & (n % 10 == 0) Entonces
			Imprimir 'This number is almost special'
		SiNo
			Imprimir 'Just a regular number'
		FinSi
		
	FinSi
	
FinAlgoritmo

