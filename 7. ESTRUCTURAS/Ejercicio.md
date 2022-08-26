1. Realiza un algoritmo y diagrama de flujo de un programa que compare dos números e indique cual es mayor.
  
       Inicio
        Declarar num_1,numn_2(int)
        Mostrar "Ingrese el primer número" 
        Asignar num_1(int)
        Mostrar "Ingrese el segundo número" 
        Asignar num_2(int)        
        Si num_1>num_2:
          Mostrar "El primer número es el mayor"
        Elif num_1<num_2:
          Mostrar "El segundo número es el mayor"
        Else:
          Mostrar "Ambos números son equivalentes"
        Fin
      
        Diagrama de flujo: 
        ![image](https://user-images.githubusercontent.com/111446231/186460151-aa71c4bf-ae2a-4eac-8bf6-a7d844352937.png)
        
2. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.


       Inicio
        Declarar cal_1,cal_2,cal_3,cal_4,prom(float)
        Mostrar "Ingrese la primer calificación" 
        Asignar cal_1(float)
        Mostrar "Ingrese la segunda calificación" 
        Asignar cal_2(float)
        Mostrar "Ingrese la tercera calificación" 
        Asignar cal_3(float)
        Mostrar "Ingrese la cuarta calificación" 
        Asignar cal_4(float)
        Asignar prom=( cal_1+cal_2+cal_3+cal_4)/4 
        Si prom>6:
          Mostrar "¡Felicidades! Aprobaste con un promedio de ",prom
        Else:
          Mostrar "Reprobaste. Tu promedio es de ",prom
       Fin
      
      Diagrama de flujo
      ![image](https://user-images.githubusercontent.com/111446231/186464023-4c56f497-78af-4085-9c7b-53bf13d7d090.png)
![image](https://user-images.githubusercontent.com/111446231/186466778-d0c5e1d8-3e83-4af6-ab6a-31140bad3317.png)


3. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.

       Inicio
        Declarar num(int)
        Mostrar "Ingrese el número" 
        Asignar num(int)       
        Si num%mod==0:        o    Si (num/2)=int
          Mostrar num," es par"
        Else:
          Mostrar num," es impar"
       Fin
      
        Diagrama de flujo:
        ![image](https://user-images.githubusercontent.com/111446231/186692687-d68bd01a-5cb7-453c-a79d-a0ca0c975d46.png)
 

problema pedir la estatura de una persona para decir que altura tiene (baja, alto, media)

    inicio
    declarar estatura(float)
    mostrar "Ingresa tu estatura en metros" en rango (0.0,2.5)
    asignar estatura
     Si estatura<1.50:
       mostrar "Eres de estatura baja"
    elif 1.50<=estatura<1.70:
        mostrar "Eres de estatura media"
     else:
       mostrar "Eres de estatura alta"
     fin


    inicio
     declarar estatura(float)
     mostrar "Ingresa tu estatura en metros"
      asignar estatura
    Si 0.0<estatura<2.50:
       Si estatura<1.50:
        mostrar "Eres de estatura baja"
      elif 1.50<=estatura<1.70:
         mostrar "Eres de estatura media"
      else:
         mostrar "Eres de estatura alta"
    Else
      Mostrar "Formato inválido"
    fin

![image](https://user-images.githubusercontent.com/111446231/186699371-e520d5a2-d9f6-4334-bf7b-253d4f4a0d1f.png)
![image](https://user-images.githubusercontent.com/111446231/186706623-e2f86723-bde2-464f-ab81-16281d217967.png)

Problema: pedir tres números y ordenarlos en orden ascendente

    inicio
    declarar num_1,num_2,num_3(float)
    mostrar "Ingrese el primer número"
    asignar num_1
    mostrar "Ingrese el segundo número"
    asignar num_2
    mostrar "Ingrese el tercer número"
    asignar num_3
    
     Si num_1<=num_2 and num_1<=num_3
        Si num_2<=num_3
          mostrar num_1,num_2,num_3
        Else
         mostrar num_1,num_3,num_2      
     Elif num_2<=num_1 and num_2<=num_3
       Si num_1<=num_3
         mostrar num_2,num_1,num_3
       Else
         mostrar num_2,num_3,num_1
     Else:
       Si num_1<=num_2
          mostrar num_3,num_1,num_2
        Else
         mostrar num_3,num_2,num_1
     fin
    
   ![image](https://user-images.githubusercontent.com/111446231/186805333-076f373f-d24e-41e6-8627-293e2f406ae7.png)

   ![image](https://user-images.githubusercontent.com/111446231/186810176-97947d0b-2d9a-4827-a2f6-9baf2592d0bd.png)

### Switch
**Problema**: Ingresar una letra e indicar si es una vocal

      Inicio
        Declarar letra(char)
        Mostrar "Ingresa una letra"
        Asignar vocal
        En caso de (vocal) haga 
          Caso1 "a" or "A" 
            Mostrar letra, " es una vocal"
          Caso2 "e" or "E" 
            Mostrar letra, " es una vocal"
          Caso3 "i" or "I" 
            Mostrar letra, " es una vocal"
          Caso4 "o" or "O" 
            Mostrar letra, " es una vocal"
          Caso5 "u" or "U" 
            Mostrar letra, " es una vocal"
        Sino
          Mostrar letra," no es una vocal"
      Fin
