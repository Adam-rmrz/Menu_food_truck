# Menu_food_truck Algoritmo Menú_Restaurante
	Escribir "Ingrese el nombre del cliente"
	Leer nombre
	Escribir "Direccion del pedido"
	Leer direccion
	Escribir "Ingrese el número de telefono"
	Leer telefono 
	
	ClubSandwich=250
	alitaspicante=300
	pechugaalacrema=350
	parrilladamix=500
	hamburguesa=200
	pollofrito=200
	agua=20
	jugo=40
	refresco=35
	cerveza=120
	acumula=0
	A=0
	B=0
	C=0
	D=0
	E=0
	F=0
	G=0
	H=0
	I=0
	J=0
	Repetir
		Escribir "Hola ¿Qué tal? ", nombre ", Nuestro menú es: "
		Escribir "------------Menú-----------"
		Escribir "1<Club Sandwich----------------$ 250"
		Escribir "2<Alitas picantes--------------$ 300"
		Escribir "3<Pechuga ala crema------------$ 350"
		Escribir "4<Parrillada mix---------------$ 500"
		Escribir "5<Hamburguesa------------------$ 200"
		Escribir "6<Pollo Frito------------------$ 200"
		Leer Menú
		
	Hasta Que Menú<=6
	
	Repetir
		
		Escribir "------------Bebidas-----------"
		Escribir "1<agua-------------------------$ 20"
		Escribir "2<Refresco---------------------$ 35"
		Escribir "3<Jugo-------------------------$ 40"
		Escribir "4<cerveza----------------------$ 120"
		Leer Bebidas
		
	Hasta Que Bebidas<=4
	
	Segun Menú Hacer
		1:
			Escribir "Haz escogido club Sandwich"
			Escribir "ingrese la cantidad"
			Leer A
			acumula =acumula +ClubSandwich*A
			X=X+A
		2:
			Escribir "Haz escogido Alitas Picante"
			Escribir "ingrese la cantidad"
			leer B
			acumula=acumula +alitaspicante*B
			X=X+B
		3:
			Escribir "Haz escogido Pechuga a la crema"
			Escribir "ingrese la cantidad"
			leer C
			acumula=acumula +pechugaalacrema*C
			X=X+C
		4:
			Escribir "Haz escogido Parrillada mix"
			Escribir "ingrese la cantidad"
			leer D
			acumula=acumula +parrilladamix*D
			X=X+D
		5:
			Escribir "Haz escogido Hambuerguesa"
			Escribir "ingrese la cantidad"
			leer E
			acumula=acumula +Hamburguesa*E
			X=X+E
		6:
			Escribir "Haz escogido Pollo Frito"
			Escribir "ingrese la cantidad"
			leer F
			acumula=acumula +pollofrito*F
			X=X+F
		De Otro Modo:
			Escribir "La opcion es invalida"
	FinSegun
	Segun Bebidas Hacer
		1:
			Escribir "Haz escogido Agua"
			Escribir "Ingrese la cantidad"
			Leer G
			acumula=acumula+agua*G
			X=X+G
		
		2:
			Escribir "Haz escogido Refresco"
			Escribir "Ingrese la cantidad"
			Leer H
			acumula=acumula+refresco*H
			X=X+H
		3:
			Escribir "Haz escogido jugo"
			Escribir "Ingrese la cantidad"
			Leer I
			acumula=acumula+jugo*I
			X=X+I
		4:
			Escribir "Haz escogido cerveza"
			Escribir "Ingrese la cantidad"
			Leer J
			acumula=acumula+cerveza*J
			X=X+J
		De Otro Modo:
			Escribir "La opcion de la bebida no es valida"
	FinSegun
	
	Escribir "Su cuenta es  de : ", acumula
	Escribir "La cantidad de articulos que ordenó es : ", x
	Escribir "Su compra se enviará lo mas pronto posible"
	Escribir "Gracias por su compra"
	
	Escribir "Adam Ramirez sanchez"
	Escribir "21-SIEN-1-024"
FinAlgoritmo
