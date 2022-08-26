# Algoritmo: Proyecto final 1
## Algoritmo Número Secreto

![image](https://user-images.githubusercontent.com/111446231/186941842-42825c6c-7ec7-4c91-872d-f816306860ec.png)

    Inicio
      Declarar num_mist, num_player, vidas
      Asignar num_mist.random (0,10)
      Asignar vidas = 4
      Mostrar "Bienvenido al - Número Secreto -"
      Mostrar "Adivina el número entre 1 y 10"
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
    Fin    
    
![image](https://user-images.githubusercontent.com/111446231/186937771-0e81fa93-ecef-40f1-8179-dc34c41c260b.png)


        
