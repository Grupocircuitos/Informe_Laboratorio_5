# Informe_Laboratorio_5
Integrantes: Cela,  Gutierrez, Manosalvas 

PRÁTICA N°05

Tema : Teorema de Thévenin

1. OBJETIVOS DE LA PRÁCTICA

1.1. OBJETIVO GENERAL

- Compruebe experimentalmente el Teorema de Thévenin, mediante el ensamblado de un circuito lineal con dos terminales, utilizando la plataforma de tinkercad, para emplear los conocimientos adquiridos en clase y verificar el funcionamiento de este.

1.2. OBJETIVOS ESPECÍFICOS

- Determinar que establece el Teorema de Thévenin con respecto a los circuitos líneales de dos terminales.
-  Definir como se le conoce a la fuente de voltaje y la resistencia en serie dentro del Teorema de Thévenin.

2. MARCO TEÓRICO

2.1. TEOREMA DE THÉVENIN

![image](https://user-images.githubusercontent.com/105887502/177910082-3df4b20b-aa92-4893-a0e2-e86584289627.png)

3. EXPLICACIÓN DEL PROCEDIMIENTO

3.1. Arme el circuito que se muestra en la figura 5.1.

![image](https://user-images.githubusercontent.com/105887502/177910149-e78391da-1091-4758-b851-459a06d79a4c.png)

3.2. Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.

![image](https://user-images.githubusercontent.com/105887502/177910170-a0b822f9-7b44-4aa4-8967-c34b051245c3.png)

3.3. Desconecte la resistencia R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla 5.1.

![image](https://user-images.githubusercontent.com/105887502/177910188-fb6458d9-8942-4469-a953-bc215b963f28.png)

3.4. Anule el efecto de las fuentes de alimentacion. Desconectó R5 y desde el circuito abierto resultó mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.

![image](https://user-images.githubusercontent.com/105887502/177910222-1e17e5d1-ac1c-4ef5-b659-a63cfb9a32d2.png)

3.5. Implemente el circuito equivalente de Thévenin, agregue la resistencia R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2.

![image](https://user-images.githubusercontent.com/105887502/177910267-34c53489-f4ce-4664-9220-0fd232f752a4.png)

Cálculos analíticos realizados para la tabla 5.1

![image](https://user-images.githubusercontent.com/105887502/177910291-4c78a480-7282-452e-9996-17dafb2116b3.png)

Hallando el voltaje de Thévenin:

![image](https://user-images.githubusercontent.com/105887502/177910305-570c5220-ed13-4396-9728-ede65f3b00e3.png)

![image](https://user-images.githubusercontent.com/105887502/177910339-a596163e-486e-49bb-9df8-b2ed3f0d0be6.png)

Mediante el uso de la calculadora Symbolab encontramos las soluciones.

![image](https://user-images.githubusercontent.com/105887502/177910365-c6dfa4a1-6d91-4bf1-a5c7-d52b60cfa7cc.png)

Las soluciones para el sistema de ecuaciones son:

![image](https://user-images.githubusercontent.com/105887502/177910466-0e0395b7-09ae-4e06-b2f2-881ba9e1ad8e.png)

I1 corresponde al valor de ae I2 corresponde al valor de b, por lo que:

![image](https://user-images.githubusercontent.com/105887502/177910501-4f6c6b3a-d90f-412e-927d-6d423269a01c.png)

Por tanto, el valor de voltaje de Thévenin es

![image](https://user-images.githubusercontent.com/105887502/177910528-fc6fc913-a963-4014-8de6-991937519706.png)

Explicación:

Para encontrar el voltaje de Thévenin en primer lugar redibujamos el circuito ahora con la resistencia R5 abierta, es así que, el voltaje que hay entre las terminales abiertas va a ser el mismo voltaje que recupera por la resistencia R3. Para lo que, mediante el método de mallas, hallamos la corriente que pasa a través de la resistencia R3 y luego despejamos el voltaje de la ley de ohm y reemplazamos los valores de corriente y resistencia. Finalmente obtenemos el valor del voltaje de Thévenin.

Hallando la resistencia de Thévenin:

![image](https://user-images.githubusercontent.com/105887502/177910556-2a6fc5d8-503b-4a3f-9efd-c21c02730dc9.png)

![image](https://user-images.githubusercontent.com/105887502/177910858-eb19e64f-2d4a-4e87-b3b1-d7880518ad7f.png)

Explicación:

Para encontrar la resistencia de Thévenin en primer lugar redibujamos el circuito teniendo en cuenta que igualamos a cero el voltaje de las dos fuentes. Por lo que ya con el nuevo circuito, identificamos cuáles son las resistencias que están en paralelo y cuáles, en serie, para posterior así ir desarrollando la suma de las resistencias o ir encontrando las resistencias equivalentes. Finalmente se encontró la resistencia de Thévenin.

Cálculos analíticos realizados para la tabla 5.2

![image](https://user-images.githubusercontent.com/105887502/177911089-ad2c4084-2def-4729-8b37-83f55230dbbb.png)

Hallando voltaje y corriente de circuito original:

![image](https://user-images.githubusercontent.com/105887502/177911120-bb774e25-093c-4d9a-9a11-3a48ed282003.png)

![image](https://user-images.githubusercontent.com/105887502/177911138-647ce813-774a-4bc4-8eba-a12d306da22d.png)

![image](https://user-images.githubusercontent.com/105887502/177911194-cd997ddb-55b8-44d5-b3dc-99dab64dd19d.png)








