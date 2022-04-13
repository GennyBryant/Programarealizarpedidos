Algoritmo Restaurante
	Escribir "sistema de pedidos del restaurant **The world of flavors** "
	
	Arroz=50
	Habichuelas=60
	Pollo=75
	
	acumula=0
	c=0
	m=0
	n=0
	p=0
	
	Escribir "PARA ENTRAR AL SISTEMA ESCRIBA  :  1"
	Escribir "PARA SALIR DEL SISTEMA ESCRIBA  :  2"
	
	LEER Z 
	Mientras Z=1 Hacer
		Escribir "seleccione una opcion"
		Escribir "1.Arroz ................. RD/50.00"
		Escribir "2.Habichuela....  RD/60.00"
		escribir "3.Pollo............  RD/75.00"
		leer pl
		Segun pl Hacer
			1:
				escribir "Ha elegido Arroz "
				Escribir "Ingrese cantidad de platos"
				leer m  
				acumula=acumula+Arroz*m   //con esto hallamos el precio de pl 1
				c=c+m     //acumula platos totales de pl1
				
			2: escribir "Ha elegido Habichuelas"
				Escribir "Ingrese cantidad de platos"
				leer n
				
				acumula=acumula+Habichuelas*n
				c=c+n
				
			3:
				escribir "Ha elegido Pollo "
				Escribir "Ingrese cantidad de platos"
				leer p 
				acumula=acumula+Pollo*p
				c=c+p
			De Otro Modo:
				Escribir "opcion no valida ingrese otro numero"
		Fin Segun
		
		
		
		
		
		Escribir "PARA PEDIR ALGO MAS ESCRIBA  :  1"
		Escribir "PARA SALIR    DE    ESCRIBA  :  2"
		LEER Z
		
	Fin Mientras
	
	ESCRIBIR "LA CUENTA TOTAL ES :  ", ACUMULA
	escribir "EL TOTAL DE PLATOS PEDIDOS ES : ",c 
	
	// Genny Bryant Medina Matricula 21-EIIT-1-008 seccion 0463
	
FinAlgoritmo
