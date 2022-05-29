## Programas en C++ De Ruano Joseph

- Autor: Ruano Jama Joseph Johan
- Correo: joseph.ruano.jama@utelvt.edu.ec

![image](https://user-images.githubusercontent.com/101407948/170839609-edfc5b2d-16bb-44ba-a235-b48298bfce12.png)

## Fundamentos de Programación

- Actividad-B1
https://youtu.be/rJeX2yuVmHc


## Comparar

- En el siguiente  programa se va a comparar 2 números y saber que número es mayor y si ambos son iguales.

## Especificación Del  Programa

1. Declaramos la libreria de entrada y salida:

		#include <iostream>
		using namespace std;

2. Declararamo las 2  Variables tipo Entero:

		int rj_r1  rj_r2

3.  Agregar un comentario para que el usuario  digite lo solicitado:

		cout<<"Ingrese el primer número: ";
		cin>>rj_r1;
		cout<<"Ingrese el segundo número: ";
		cin>>rj_r2;

4. Declarar la condición para definir si ambos números son iguales si es correcto se enviara un comentario:

		if(rj_r1==rj_r2){
		cout<<"Los números son  iguales";

5.  Al no cumplirse la condicion,indicara que el primer número es mayor e enviara un comentario:

		else if(rj_r1>rj_r2){
		cout<<"El número mayor es: "<<rj_r1<<endl

6. Al no cumplirse la condicion,indicara que el segundo número es mayor e enviara un comentario:

		if(rj_r2>rj_r1){
		cout<<"El número mayor es: "<<rj_r2<<endl;

## Funcionamiento del Programa

1. Ejecutamos el programa en cualquier Embarcadero en mi caso C++ y Presionamos F11:

![hyh](https://user-images.githubusercontent.com/101407948/170883885-d5b1fb7a-4da8-4d24-8ea1-2d29b9f1abc8.png)

2. Ingresamos los valores que queremos comparar.

![gfdsfg](https://user-images.githubusercontent.com/101407948/170883899-c199c0b7-9bf2-44fe-9416-a79a46a861a1.png)

![kyuky](https://user-images.githubusercontent.com/101407948/170883906-ac38c9f2-b1eb-449b-92bb-72e930449a89.png)

3. Nos dara el resultado de que si son iguales o cual es mayor:

![tyty](https://user-images.githubusercontent.com/101407948/170884180-5f012791-34f4-4664-835d-354a10bd2047.png)


![erert](https://user-images.githubusercontent.com/101407948/170884119-a7032a26-7635-4755-a941-df833610125e.png)



## Diagrama de Flujo

![Comparar](https://user-images.githubusercontent.com/101407948/170845442-fce4585b-8155-4836-b22b-70732d947e3f.jpg)




## Cuenta Moneda

-En el siguiente programa se va clasificar monedas de 0.10,0.25,0.50¢ y saber la cantidad total de monedas disponible.

## Especificación Del Programa 

1. Declaramos la libreria de entrada y salida:

		#include<iostream>
		using namespace std;

2.  Declaramos 2 variables tipo  Entero-Flotante:

		int rj_r1,rj_camo=0,rj_mone=0,rj_moda=0,rj_mond=0;
   		float rj_r2,rj_sumto=0,rj_mone1=0,rj_mone2=0,rj_mone3=0,rj_die=0.10, rj_vei=0.25, rj_cin=0.50;
   
3. Agregamos un comentario para que el usuario digite lo solicitado:

		cout<<"Cantidad de monedas a ingresar "<<endl; 
		cin>>rj_r1;

4. Agregamos un comentario para que el usuario digite el tipo de moneda que inserto se de 0.10,0.25,0.50¢ y se realize el proceso :

 		do{
 		cout<<"Inserte la moneda:"<<endl;
		cin>>rj_r2;

5. Despues  relizamos el procesó de la cantida de monedas y total :

 		rj_camo=rj_camo+1;
 		rj_sumto=rj_sumto+rj_r2;

6. Declaramos la decisión de la cantidad de moneda y la suma  total de las monedas de 0.10,0.25,0.50¢ :

 		if(rj_r2==rj_die){
        		rj_mone=rj_mone+1;
        		rj_mone1=rj_mone1+rj_r2;
    		}
      		if(rj_r2==rj_vei){
        		rj_moda=rj_moda+1;
        		rj_mone2=rj_mone2+rj_r2;
    		}
     		if(rj_r2==rj_cin){
        		rj_mond=rj_mond+1;
        		rj_mone3=rj_mone3+rj_r2;
    		}

7. Declaramos la Condición para que se repita el proceso "do":

 		}while(rj_camo<rj_r1);
    
## Funcionamiento del Programa

1. Ejecutamos el programa en cualquier Embarcadero en mi caso C++ y Presionamos F11:

![fw](https://user-images.githubusercontent.com/101407948/170884839-207cc598-af5f-44e0-b728-cadfd50ee628.png)

2. Ingresamos la cantidad de monedas en mi caso 3:

![gerg](https://user-images.githubusercontent.com/101407948/170884844-39e74c95-94e1-4c14-9646-17fc0f1af79a.png)

3. Ingresamos el tipo de moneda  sea de 0.10,0.25,0.50 ¢:

![gdg](https://user-images.githubusercontent.com/101407948/170884849-c18a3fb1-db1c-4de0-96a5-f850eaa11bf0.png)

4. Se clasificará la moneda y total de monedas:

![gdfg](https://user-images.githubusercontent.com/101407948/170884855-7a078797-68a2-49f5-b301-f8c427ba652c.png)


## Diagrama de Flujo

![CuentaMoneda](https://user-images.githubusercontent.com/101407948/170845521-00df371c-3d47-4802-a8ba-86e6f4f0e440.jpg)


## Edad

-En el siguiente programa se va saber nuestra Edad exacta dia mes y año.

## Especificación del Programa

1. Declaramos la libreria de entrada y salida:

 		<iostream> 
 		using namespace std;
 
 2. Declaramos dos variables tipo Entero:
 
    		 int rj_anac,int rj_meac,int rj_diac,int rj_ana,int rj_men,int rj_din);

    		 int rj_anac;  
    		int rj_meac; 
    		int rj_diac; 
    		int rj_ana; 
    		int rj_men; 
    		int rj_din; 

3.  Ingresamos comentarios para que el usuario digite lo solicitado:

		cout<<"Ingresar la fecha actual: "<<endl;
    		cout << "Año Actual: ";   
		cin >> rj_anac;
    		cout << "Mes Actual: ";   
		cin >> rj_meac;
    		cout << "Día Actual: ";  
		cin >> rj_diac;
    		cout<<"Ingresar la fecha de nacimiento: "<<endl;
    		cout << "Año de Nacimiento: ";  
		cin >> rj_ana;
    		cout << "Mes de Nacimiento: ";  
		cin >> rj_men;
    		cout << "Día de Nacimiento: ";  
		cin >> rj_din;

4.  Realizar el procesó qu hay  que relizar para calcular la edad. 

- Primero se realiza la condicion de dia actual con el dia de nacimiento. 

- Luego los dias actuales va aser igual  a la suma de los 30 dias que tiene un mes.

- El mes actual  va ser igual a la suma de 12 meses al cumplira la condicion de mes actual com mes de nacimiento y el año actual y el año de nacimiento asi mismo se restan y los meses. 

 		int rj_dia , rj_mes;
    		if (rj_diac<rj_din)
    		{  
        		rj_diac=rj_diac+30; 
        		rj_meac=rj_meac-1; 
        		rj_diac=rj_diac-rj_din; 
    		}
    		else 
        		rj_dia=rj_diac-rj_din;
    		if(rj_meac<rj_men)
    		{   
        		rj_meac=rj_meac+12; 
        		rj_anac=rj_anac-1 ; 
        		rj_mes=rj_meac-rj_men; 
    		}
    		else
		 rj_mes = rj_meac - rj_men;


## Funcionamiento del Programa

1. Ejecutamos el programa en cualquier Embarcadero en mi caso C++ y Presionamos F11:

![reer](https://user-images.githubusercontent.com/101407948/170885821-d76375d7-62ae-4a0e-9661-cfcf447045f9.png)

2. Ingresamos la fecha actual y el año de nuestro nacimiento:

![ghgh](https://user-images.githubusercontent.com/101407948/170885825-1341a60f-4c51-4977-9ac4-2b408c222931.png)

3. Nos dara el resultado de nuestra edad exacta:

![dfsdf](https://user-images.githubusercontent.com/101407948/170885831-c4442843-25f9-406b-8be9-b4c2e13d3aee.png)



## Diagrama de Flujo

![Edad](https://user-images.githubusercontent.com/101407948/170845566-1c84fdc8-aa30-45e5-830f-9e995adcf4aa.jpg)

## Punto Venta

- En el siguiente Programa se va a realizar la  compra de N-Productos el cual se va obtener una factura que contiene ,descuento e iva.

## Especificacion Del Programa

1. Declaramos la libreria de entrada y salida :

		#include <iostream>
		using namespace std;

2.  Declaramos 2 variables tipo Entero-Flotante:

		int rj_r1=0,rj_r2;
		float rj_pg=0,rj_p;
		float rj_iv=0.15,rj_desc=0.12,rj_iva,rj_des,rj_totp;

3.  Agregamos un comentario al usuario donde digite lo solicitado:

		cout<<"Ingrese todos lo valores que desea sumar: ";
		cin>>rj_r2;

4. Agregamos el bucle y un comentario de los precios del producto y el proceso de la suma de producto:

		do{
		cout<<"Ingrese el valor a sumar"<<rj_r1+1<<endl;
		cin>>rj_p;
		rj_r1=rj_r1+1;
		rj_pg=rj_pg+rj_p;

5. Agregamos la condición y un comentario de su sumatoria y el proceso:

- El iva va a ser  igual  a la cantidad de Productos  multiplicado por   0.15.
- El descuento va a ser igual  a la cantidad de productos multiplicado por 0.12.
- El total a pagar  va aser igual primero a la resta de cantidad de producto y el descuento mas la suma del iva.

		}while (rj_r1<rj_r2);
		cout<<"El resultado final de la sumatoria es de: "<<rj_pg<<endl;
		rj_iva=rj_pg*rj_iv;
		rj_des=rj_pg*rj_desc;
		rj_totp=rj_pg-rj_des+rj_iva;


## Funcionamiento del Programa

1. Ejecutamos el programa en cualquier Embarcadero en mi caso C++ y Presionamos F11:

![p1](https://user-images.githubusercontent.com/101407948/170882773-f1980d3d-66fc-42da-8c50-7b9b7f85191d.png)

2. Ingresamos Cuanto valores deseamos sumar en mi caso 4:

![rr](https://user-images.githubusercontent.com/101407948/170882860-040b4226-0c63-49cf-a494-7a3f95512358.png)

3. Ingresamos los valores de los productos y nos dara nuestra factura .

![rgg](https://user-images.githubusercontent.com/101407948/170882889-479c2b09-11bb-4847-9f91-2e31a08fd4fc.png)


## Diagrama de Flujo

![PuntoVenta](https://user-images.githubusercontent.com/101407948/170878082-14cad9b1-a8d2-41fe-b897-8b1130d4fefb.jpg)


## Suma-N

- En el siginte programa  se va sumar la cantidad de números que desemos.

## Especificación del Programa

1. Declaramos la libreria de entrada y salida:

		#include <iostream>
		using namespace std;

2.  Declaramos 2 variables tipo Entero-Flotante:

		int rj_r1=0, rj_r2; 
		float  rj_res=0, rj_r3;

3. Agregamos un comentario al usuario donde digite lo solicitado:

		cout<<"Ingrese todos lo valores que desa sumar: ";
		cin>> rj_r2

4.  Agregamos el bucle y un comentario al usuario y realizamos el proceso de la suma y la condición:


		do{
		cout<<"Ingrese el valor a sumar"<< rj_r1+1<<endl;
		cin>> rj_r3;
		 rj_r1= rj_r1+1;
		 rj_res= rj_res+ rj_r3;
		}while ( rj_r1< rj_r2);

## Funcionamiento del Programa

1. Ejecutamos el programa en cualquier Embarcadero en mi caso C++ y Presionamos F11:

![ffg](https://user-images.githubusercontent.com/101407948/170883331-1b3df615-3935-4a60-be06-65515307d3be.png)

2. Ingresamos la catidad de números que deseamos sumar en mi caso 3:

![fhgfg](https://user-images.githubusercontent.com/101407948/170883334-f0030937-0474-4015-8297-06dffaec0e7b.png)

3.  Ingresaos los numeros que deseamos sumar y no dara el resultado:

![dfsf](https://user-images.githubusercontent.com/101407948/170883337-d13ad817-71c5-486e-ba04-91ca419adad0.png)

## Diagrama de Flujo

![Suma](https://user-images.githubusercontent.com/101407948/170880905-5b102007-557e-4915-9610-6de67f97445d.jpg)

## Desacargar el Repositorio

## Especificación de la Descarga

1. Ingresar al Termux y a al directorio donde vamos a descargarlo:

2. Clonar el Repositorio con el suiguiente comando:

		 $ git clone https://github.com/RJ-Johan/Actividad-E2.git

3. Como el repositorio es  publico no habra ningun problema al descargarlo:

## Ejecutar lo Programas de mi Repositorio RJ-Johan en Termux

##Especificación

1. Ingresamos a Termux.

2. Ingresamos al directorio donde se encuentra nuestro repositoriocon los siguientes comandos:

		cd RJ-Johan
		cd RuanoJoseph
		cd Actividad-E2

3. Para compilar o ejecutable los programa en el termux  se usa los siguientes comandos:

		g++ RJ-Comparar.cpp o- RJ-Comparar

4. Para ejecutar el programa en el termux usamos el siguiente comando:

		./RJ-Comparar



