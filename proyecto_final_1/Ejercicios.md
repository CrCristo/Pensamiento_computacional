## Ejercicios extra

### While

Realizar un programa que imprima un nombre mientras tu no me digas que pare.

    Inicio 
    Declarar nombre(str) repetir (char)
    Asignar repetir = ""
    Mostrar ("Ingresa tu nombre: ")
    Asignar nombre
    Mostrar ("¿Quieres que te imprima tu nombre? \n S/N: ")
    Asignar repetir
    Mientras repetir=S o repetir=s hacer
      Mostrar nombre
      Mostrar ("¿Quieres que te imprima tu nombre? ")
      Asignar repetir
    Fin
    
![image](https://user-images.githubusercontent.com/111446231/187950703-a222d880-408f-42c7-b00e-b9c46b13b97f.png)

![image](https://user-images.githubusercontent.com/111446231/187951683-35ee6d48-80df-4ad6-b4ec-3c05bd11fe56.png)

Realizar programa que pida la fecha de nacimiento y calcule su edad para al final preguntar si quiere conocer otra edad

    Inicio
    Declarar Año_Nac, Año_Act, Edad(int), rep("")
    Mostrar "¿Quieres que calcule alguna edad? s/n"
    Asignar repetir
    Mientras repetir=S o repetir=s hacer
        Mostrar "¿Cúal es el año de nacimiento?"
        Asignar Año_Nac
        Mostrar "¿Cúal es el año actual?"
        Asignar Año_Act
        Asignar Edad = Año_Act-Año_Nac
        Mostrar ("La edad es de ", Edad, " años. ", \n, "¿Quieres que calcule alguna edad? s/n")
        Asignar repetir
    Fin

![image](https://user-images.githubusercontent.com/111446231/187957046-e57017f0-3c03-4be6-a11a-3e78d37deb87.png)

![image](https://user-images.githubusercontent.com/111446231/187958759-d4173b6b-e27c-4192-ab55-a15789cd5aac.png)

Realizar una calculadora que pregunte por la operacion que quiere hacer y pregunte si quiere hacer otra

Debe tenr while y switch

    Inicio
    Declarar Operacion, resultado
    fin
    
    Inicio
    Declarar var_1, var_2 , resultado(float) ,repetir("") , operación(int)
    Asignar var_1=0.0
    Asignar var_2=0.0
    Asignar resultado=0.0
    Mostrar ("¿Cúal operación desea realizar?  1 : Suma 2: Resta 3 : Multiplicacion 4 : División 5 : Salir de la calculadora")
    Asignar Operación
    Mientras Operacion !=5 hacer
        Mostrar ("Ingrese su primer número")
        Asignar var_1
        Mostrar ("Ingrese su segundo número")
        Asignar var_2
        En caso de (Operación) haga:
            Caso 1 "1"
                Asignar Resultado = var_1+var_2
                Mostrar (var_1,"+",var_2,"=",resultado
            Caso 2 "2"
                Asignar Resultado = var_1-var_2
                Mostrar (var_1,"-",var_2,"=",resultado
            Caso 3 "3"
                Asignar Resultado = var_1*var_2
                Mostrar (var_1,"x",var_2,"=",resultado
            Caso 4 "4"
                If var_2 != 0:
                    Asignar Resultado = var_1/var_2
                    Mostrar (var_1,"/",var_2, "=" ,resultado)
                else:
                    Mostrar "No se puede dividir entre 0"
             Sino
                Mostrar "Formato inválido"
        Mostrar ("¿Cúal operación desea realizar?  1 : Suma 2: Resta 3 : Multiplicacion 4 : División 5 : Salir de la calculadora")
        Asignar Operación
     Mostrar ("¡Bye! Que tenga buen día."
     Fin
    
    
![image](https://user-images.githubusercontent.com/111446231/188182207-bc44f870-de06-4589-b93b-44e5a87b237f.png)

![image](https://user-images.githubusercontent.com/111446231/188191820-157b529d-961b-4332-a639-8048f93ef162.png)
![image](https://user-images.githubusercontent.com/111446231/188192022-d9fb5e2b-6940-4248-a627-2339a8302f5d.png)

Tarea
Ahcerel número secreto

### Función Fecha
