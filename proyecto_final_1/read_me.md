# Algoritmo: Proyecto final 1
## Algoritmo Número Secreto

![image](https://user-images.githubusercontent.com/111446231/186941842-42825c6c-7ec7-4c91-872d-f816306860ec.png)

### v  1.1

    Inicio
      Declarar num_mist, num_player, vidas(int), repetir(char)
      Asignar num_mist.random (0,10)
      Asignar vidas = 5
      Asignar repetir = "y"
      Mostrar "Bienvenido al - Número Secreto -"
      Mostrar "Objetivo: Adivinar el número entre 1 y 10"
      Mientras repetir =="y" o repetir == "Y"
          Mientras vidas=/=0 o num_mist=/=num_player y 0<=num_player<=10 :
             Mostrar "Ingresa tu número"
             Asignar num_player
             If num_player<num_mist:
                Mostrar "El número es más grande"
             Else:
                Mostrar "El número es más pequeño"
             vidas = vidas-1
             Mostrar (vidas, " vidas restantes")
          If num_mist==num_player
            Mostrar "¡Felicidades! Encontraste el - Número Secreto -"
          Elif vidas==0
            Mostrar "Perdiste."
          Mostrar "El número secreto es ",num_mist
          Mostrar "¿Quieres seguir jugando? y/n"
          Asignar repetir
    Fin    
    
![image](https://user-images.githubusercontent.com/111446231/186937771-0e81fa93-ecef-40f1-8179-dc34c41c260b.png)

 ### v 1.2
    
    
    Inicio
      Declarar num_mist, num_player, vidas(int), repetir(char)
      Asignar num_mist.random (0,10)
      Asignar vidas = 5
      Asignar repetir = "y"
      Mostrar "Bienvenido al - Número Secreto -"
      Mostrar "Objetivo: Adivinar el número entre 1 y 10"
      Mientras repetir =="y" o repetir == "Y"
          Mientras vidas=/=0 o num_mist=/=num_player:
             Mostrar "Ingresa tu número"
             Asignar num_player
             If num_player<num_mist:
                Mostrar "El número es más grande"
             Elif  10<num_player<0:
                Mostrar  "Formato inválido. Intenta otra vez"
                vidas = vidas+1
             Else:
                Mostrar "El número es más pequeño"
             vidas = vidas-1
             Mostrar (vidas, " vidas restantes")
          If num_mist==num_player
            Mostrar "¡Felicidades! Encontraste el - Número Secreto -"
          Elif vidas==0
            Mostrar "Perdiste."
          Mostrar "El número secreto es ",num_mist
          Mostrar "¿Quieres seguir jugando? y/n"
          Asignar repetir
    Fin    
    
![image](https://user-images.githubusercontent.com/111446231/188671156-081c91d1-f9fc-4b4e-b3ce-324fbfe30179.png)


### v  1.1

      import random
      num_sec= random.randint(0,10)
      vidas=5
      repetir="y"
      print ("Bienvenido al - Nùmero Secreto -\nAdivina el nùmero entre 0 y 10")
      num_ply= int(input("Ingresa tu número: "))
      while repetir == "y"or repetir =="Y"
          while ((vidas!=0 or num_ply!=num_sec) and 0<=num_ply<=10):
            vidas = vidas-1
            if num_ply==num_sec:
              break
            elif num_ply<num_sec:
              print ("El número es más grande")
            else:
              print ("El número es más pequeño")
            print (vidas, " vidas restantes")
            num_ply= int(input("Ingresa tu número: "))  
          if num_sec==num_ply:
              print ("¡Felicidades! Encontraste el - Número Secreto -")
          elif vidas==0:
            print ( "Perdiste.")
          else:
            print ("Formato inválido")
          print ("El número secreto es ",num_sec)
          repetir = str(input("¿Quieres seguir jugando? y/n?"))
          
       
       
### v 1.2

    import random
    repetir="y"
    print ("             Bienvenido al\n        === Nùmero Secreto ===\nObjetivo: Adivinar el nùmero entre 0 y 100")
    while repetir == "y" or repetir =="Y":
      vidas=5
      lista = []
      num_sec= random.randint(0,100)
      num_ply= int(input("\nIngresa tu número: "))
      while vidas!=0 and num_ply!=num_sec:
        if num_ply in lista:
          print ("\nYa ingresaste ese número. Intenta de nuevo.")
          vidas = vidas+1
        else:
          if 100<num_ply or num_ply<0:
            print ("\nFormato inválido. Intenta de nuevo")
            vidas = vidas+1
          elif num_ply<num_sec:
            print ("\nEl Nùmero Secreto es más grande")
          elif num_ply==num_sec:
            break
          else:
            print ("\nEl Nùmero Secreto es más pequeño")
        vidas = vidas-1
        print (vidas, " vidas restantes")
        lista.append(num_ply)
        num_ply= int(input("Ingresa tu número: "))  
      if num_sec==num_ply:
        print ("\n¡Felicidades! Encontraste el - Número Secreto -")
      else:
        print ( "\nPerdiste.")
      print ("El número secreto es ",num_sec)
      repetir = str(input("\n¿Quieres seguir jugando? y/n?"))
    print ("\n¡Gracias por jugar!\n Hasta la próxima.")
