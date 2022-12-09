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
	
## SIMPLE CALCULATOR WITH SWITCH

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

## MULTI OPTION PROGRAM

Algoritmo MultiOp

	Escribir " ------------ MULTI OPCION ----------- "
	Escribir "Opciones Disponibles"
	Escribir "1. Suma de dos numeros"
	Escribir "2. Imprimir dia de la semana"
	Escribir "3. Calcular longitud de texto"
	Escribir "Escoga una opcion: "
	leer opt
	Segun opt Hacer
		1:
			Escribir "Ingrese primer numero"
			leer num1
			Escribir "Ingrese segundo numero"
			leer num2
			Escribir "Realizando suma ", num1, " + ", num2
			sum <- num1 + num2
			Escribir "El resultado es: ", sum
		2:
			Escribir "Ingrese un numero del 1 al 7"
			leer sem
			Si sem == 1 Entonces
				Escribir "El dia de la semana es: Lunes"
			Fin Si
			Si sem == 2 Entonces
				Escribir "El dia de la semana es: Martes"
			Fin Si
			Si sem == 3 Entonces
				Escribir "El dia de la semana es: Miercoles"
			Fin Si
			Si sem == 4 Entonces
				Escribir "El dia de la semana es: Jueves"
			Fin Si
			Si sem == 5 Entonces
				Escribir "El dia de la semana es: Viernes"
			Fin Si
			Si sem == 6 Entonces
				Escribir "El dia de la semana es: Sabado"
			Fin Si
			Si sem == 7 Entonces
				Escribir "El dia de la semana es: Domingo"
			Fin Si
			Si sem >= 8 Entonces
				Escribir "Numero no valido"
			Fin Si
			
		3:
			Escribir "Ingrese una palabra"
			leer pal
			lpal <- Longitud(pal)
			Escribir "La palabra ", pal, " tiene ", lpal, " letras"
		De Otro Modo:
			Escribir  "Opcion no disponible"
	Fin Segun
	
	
FinAlgoritmo

## MULTIPLICATION TABLES

Algoritmo TablasMult

	Escribir " ------------ TABLAS DE MULTIPLICAR ------------- "
	Escribir "Ingrese un numero"
	Leer num
	mult <- 0
	Escribir "La tabla de multiplicar de ", num, " es: "
	Mientras mult <= 10 Hacer
		
		Escribir num * mult
		mult <- mult + 1
	Fin Mientras
	
FinAlgoritmo

## SIMPLE CALCULATOR DO WHILE

Algoritmo CalcDoWhile

	Repetir
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
		Escribir "¿Desea realizar otra operacion? (Y/N)"
		Leer cont
	Mientras Que cont == "Y" | cont == "y"
	
FinAlgoritmo

## MULTIPLICATION TABLES WITH FOR

Algoritmo MultFor
	
	Escribir  " ------------ TABLAS DE MULTIPLICAR ------------ "
	Escribir "Ingrese un numero: "
	Leer num
	Escribir "Tabla de multiplicar del ", ConvertirATexto(num)
	Para i<-0 Hasta 10 Con Paso 1 Hacer
		Escribir ConvertirATexto(num), " * ", ConvertirATexto(i), " = ", num * i
		
	Fin Para
	
FinAlgoritmo

## ASCENDING AND DESCENDING NUMBERS

Algoritmo AscDesc

	Escribir " ------------ ASCENDING AND DESCENDING NUMBERS ----------- "
	Escribir "Ingrese un numero"
	Leer num
	Escribir "Seleccion si los quiere de forma ascendente o descendente"
	Escribir  "1. Ascendente"
	Escribir "2. Descendente"
	Leer  opt
	Segun opt Hacer
		1:
			Para i<-0 Hasta num Con Paso 1 Hacer
				Escribir ConvertirATexto(i)
			Fin Para
		2:
			Para i<-num Hasta 0 Con Paso -1 Hacer
				Escribir ConvertirATexto(i)
			Fin Para
		
		De Otro Modo:
			Escribir "Opcion invalida"
	Fin Segun
	
FinAlgoritmo
