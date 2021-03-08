# ejercicio-4
Algoritmo Ejercicio4
	
    Definir cont, n, suma como Entero;
	Definir calififcacion Como Entero
    suma <-- 0;
	
    Escribir Sin Saltar "Digite la cantidad de notas que deseas ingresar : ";
    Leer n;
	
    Para cont <-1 Hasta n Con Paso 1  Hacer
        Escribir Sin Saltar "NOTA ", cont , " : ";
        Leer calififcacion;
		suma <-- suma + calififcacion;
		
		Si cont> 3.0 Entonces
			Escribir "Estudiante Aprobado : ", cont
		SiNo
			Escribir "Estudiante NO Aprobado : ", cont
		Fin Si
		Escribir "El promedio de las notas es : ", (suma/n);
    FinPara

    Escribir "El promedio de las notas es : ", (suma/n);
	
FinAlgoritmo
