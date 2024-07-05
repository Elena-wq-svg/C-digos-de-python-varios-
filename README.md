# C-digos-de-python-varios-
Trata de las tareas que vi hasta ahora 
1) algoritmo factorial

 definir n,i,fact como entero;
 escribir "digite un número";
leer n;
i<-1;
fact<-1;
mientras i<=n hacer
fact <- fact*i;
i <- i+1;
finmientras
escribir " el factorial de ", n, " es ",fact;
 finalgoritmo

2)  lista de personas 

list_nombres =set()
set_list_nombres={"lily","anto","juan","mica","lucia"}

nombre = input("ingresa el nombre que quieras busacar :   ")
dios=(nombre in set_list_nombres)
if dios== True:
	print(nombre,"si esta en la lista")
else :
	print(nombre," no esta en la lista ")

3) Diccionario 

diccionario={ }
diccionario["nombre"]= input("ingrese nombre:    ")
print(diccionario)
diccionario["apodo"]= input("ingrese apodo")
print(diccionario)
diccionario["telefono"]=int(input("ingrese telefono  :  "))
print (diccionario)

4)  lista de números 

numeros= ["6","8","3","2","1","4","7"]
print(numeros)
pregunta=input("¿queres agregar un elemento a la lista ? si/no    :")
if pregunta == "no":
	print("esta bien,hasta luego")
	print("termino el programa")
elif pregunta == "si":
	a=input("dato a ingresar en la lista:   ")
	b=int(input("ingresa posicion 0/10 :  "))
	numeros.insert(b,a)
	print(numeros)

5)  Promedio

#include <math.h>
#include <stdio.h>

int main()
{
	int n1, n2,n3;
	n1 = 5;
	n2 = 3;
	n3 = 6;
	printf("%d +%d +%d= %d\n", n1, n2,n3, n1+n2+n3);
	int n4, n5,n;
	n4 = 3 ;
	n5 = n1+n2+n3 ;
	n= printf("%d / %d = %d",n4,n5,n5/ n4);
    printf(" es el promedio");
   
    
	return 0;
}


6) Perimetro

#include <math.h>
#include <stdio.h>
int main()
{
    int k;
    
	
	int pi,n1,u,radio;
	pi= 3,14;
	n1=2;
    radio = 4;	
	u=printf("%d*%d*%d=%d\n",n1,pi,radio,n1*pi*radio),printf( "es el perimetro de la circunferencia ");
	return 0;
}

7) Intercambio de valores 


#include <conio.h>
#include <stdio.h>

int main()
{
    int auxiliar, valor1, valor2, valor3,valor4,auxiliar2 ;
   printf( "\n   Introduzca el  valor 1: "  );
   scanf( "%d", &valor1 );
   printf( "\n   Introduzca el valor 2: " );
    scanf( "%d", &valor2 );
  printf( "\n   Introduzca el valor 3: " );
    scanf( "%d", &valor3 );
   printf( "\n   Introduzca el valor 4: " );
    scanf( "%d", &valor4 );
    
    
  
    printf( "   Intercambiando los valores..." );
    
    auxiliar = valor1;
    valor1 = valor2;
    valor2 = auxiliar;
    auxiliar2=valor3;
    valor3=auxiliar2;

    printf( "\n\n   Ahora, el valor de valor 1 es: %d", valor1 );
    printf( "\n\n   Ahora, el valor de valor 2 es: %d", valor2 );
  
       printf( "\n\n   Ahora, el valor de valor 3 es: %d", valor4 );
         printf( "\n\n   Ahora, el valor de valor 4 es: %d", valor3  );
   

    return 0;
}

	
8) euro a pesos

    #include <iostream.h>
    

int main ()
{
    float dolares, euros;
    cout << "Ingresa el valor de dolares: ";
    cin >> dolares;
    cin.get();
    euros=dolares/0.9;
    cout << "Valor de euros: " << euros << endl;
    cout << endl;
   
    
    
    return 0;
}

9) Perimetro 
#include <iostream>
using namespace std;
int main()
{
   float perimetro;
  float radio;
	cout<< "ingresar radio: ";
	cin>> radio;
	perimetro= (2 *3.14)*radio;
	cout<< "el perimetro de su circunferencia es: "<< perimetro;
  return 0;
}

10)  Lista de perros 

a=Nombres_de_perros = [ ]
print ("pilas de nombres de perros : ", a)
for i in range(3):
	b = input("escribe un nombre del perro  : ")
	Nombres_de_perros.append(b)
	print (a)
c= input(("deseas agregar otro nombre? si/ no ~"   ))
if c == 'si' :
	d = input("escribe un nombre del perro  : ")
	Nombres_de_perros.append(d)
	print(a)
else :
	print("weno uwu")
e = input("deseas borrar el ultimo nombre? si/no  ~  ")
if e == 'si':
	Nombres_de_perros.pop()
	print(a)
else :
	print("bueno :c")

11) lista 
Lista=["luciano","mari","manu","ana","nati","marcelo","benja","david","francisco"]
print(Lista)	
pregunta=input("¿queres agregar un elemento a la lista ? si/no    :")
if pregunta == "no":
	print("esta bien,hasta luego")
	print("termino el programa")
elif pregunta == "si":
	a=input("nombre  a ingresar en la lista de espera :   ")
	b=int(input("ingresa posicion :  "))
	Lista.insert(b,a)
	print(Lista)
	if b >=10 :
		print('no existe esa posicion ')
		print('el programa finalizará')
		print(Lista)
	elif b == -1:
		Lista.insert(10,a)
		print(Lista)



12) Tuplas y conjuntos
list_nombres =set()
set_list_nombres={"lily","anto","juan","mica","lucia"}

nombre = input("ingresa el nombre que quieras buscar :   ")
owo=(nombre in set_list_nombres)
if owo== True:
	print(nombre,"si esta en la lista")
else :
	print(nombre," no esta en la lista ")

tupla= (1,2,2,2,2,3,3,3,4,4,4,4) 
conjunto=set(tupla)
print ( conjunto)
conjunto2= tuple(conjunto)


