## PRACTICA-No.-3-ANALISIS-DE-NODOS.
# Informe Laboratorio

- **Integrantes** 

Josue Chavez

Domenica Espin

Henrry Leon

**3.1. OBJETIVO DE LA PRÁCTICA**

- Comprobar experimentalmente el Análisis de Nodos.

**3.2. MARCO TEORICO:**

![Ley de OHM](https://user-images.githubusercontent.com/116777118/203902108-95e6f9c5-a469-42d9-88fb-5ada4a45c035.png)

![image](https://user-images.githubusercontent.com/116777118/203901850-a924c734-82a0-4834-83fc-70e292969ab1.png)

![image](https://user-images.githubusercontent.com/116777118/203901992-ef931b2f-d2b6-4f43-9081-6bcd247c1b26.png)

![MÉTODO DEL VOLTAJE EN NODOS](https://user-images.githubusercontent.com/116777118/203902139-2629adde-431f-4b34-86b3-da185c69171a.png)

**MATERIAL O EQUIPO:**

• *Fuente de Voltaje de C.D.:* Dispositivo que a partir de la tensión de red pueden proporcionar una señal de tensión continúa para alimentar al circuito.

![image](https://user-images.githubusercontent.com/116777118/202655992-b76f28ec-5b39-40c2-972a-ab07f4078448.png)

• *Multímetros Digitales:* Es una herramienta que es usada para medir valores eléctricos, principalmente tensión (voltios), corriente (amperios) y resistencia (ohmios).

![image](https://user-images.githubusercontent.com/116777118/202656052-21cb49c9-117a-46d3-a033-ba19b86a50ed.png)

• *Resistores:* Componente electrónico diseñado para introducir una resistencia eléctrica determinada entre dos puntos de un circuito eléctrico.

![image](https://user-images.githubusercontent.com/116777118/202656190-eb7c02f1-032c-4da9-aa9d-735a50956092.png)

*a) Resistor de 1.8 kΩ:*

*b) Resistores de 470 Ω*

*c) Resistor de 1 kΩ*

*d) Resistor de 1.5 kΩ*

*e) Resistor de 3.9 kΩ*

*f) Resistor de 2.2 kΩ*

• *Protoboard:* Es una placa de pruebas en los que se pueden insertar elementos electrónicos y cables con los que se arman circuitos sin la necesidad de soldar ninguno de los componentes.

![image](https://user-images.githubusercontent.com/116777118/202656481-fff9b413-cfc1-4586-9ab8-bdf0a4e3c9f5.png)

**3.3. PROCEDIMIENTO**

1.	Primero identificamos los nodos presentes en el circuito. 

![image](https://user-images.githubusercontent.com/116777118/203904772-92520688-1329-4909-a3d2-b69936d5476b.png)

2.	Luego identificamos la polaridad y las corrientes presentes. 

![image](https://user-images.githubusercontent.com/116777118/203904862-d4582457-b59b-4213-a263-27b699ba109f.png)

3.	Colocamos etiquetas a los elementos para facilitar los cálculos. 

![image](https://user-images.githubusercontent.com/116777118/203904923-1c735f27-3161-46f0-93ca-1850c8755e49.png)

4.	Analizaremos el nodo A y B ya que son principales, los nodos E y C no, porque estos corresponden a fantasmas o irrelevantes, mientras que el nodo D lo tomaremos como nodo referencial.  

Las intensidades de corriente para cada nodo la analizaremos según la Ley de Corrientes de Kirchhoff, en dónde: 

![image](https://user-images.githubusercontent.com/116777118/203905050-5eed26ad-1e32-43a9-979d-92428452ba40.png)

Entonces tenemos: 

![image](https://user-images.githubusercontent.com/116777118/203905621-928dbcb4-6a3d-4f91-b0d3-45275d9c2d59.png)

Reemplazando por los valores que tenemos como datos. 

![image](https://user-images.githubusercontent.com/116777118/203905725-be62b214-8df8-4c47-ad0a-adc0b25c4d12.png)

Para un mejor entendimiento cambiamos VA por x – VB por y. Resolviendo el sistema de ecuaciones generado, obtenemos. 

![image](https://user-images.githubusercontent.com/116777118/203905840-ca710579-47ec-4b1b-b0a3-90cd6ba17373.png)

![image](https://user-images.githubusercontent.com/116777118/204004498-ff76170d-e985-4efe-8196-a814f9fe8002.png)

![image](https://user-images.githubusercontent.com/116777118/204004551-3e207db7-ffc7-42e1-9239-67d2facccf06.png)

![image](https://user-images.githubusercontent.com/116777118/204004675-d80516fe-a88d-4f0e-b9a7-90a643334f35.png)

![image](https://user-images.githubusercontent.com/116777118/204004904-4e99cfcf-0084-4eae-b1b7-d7627e5f75ce.png)

Tabla correspondiente a las mediciones de voltaje en cada nodo del circuito. 

![image](https://user-images.githubusercontent.com/116777118/204007586-440a59d7-5465-4769-873c-9a0397ac8e37.png)

![image](https://user-images.githubusercontent.com/116777118/204008558-3390157d-4247-41cc-8862-184c5ddb710d.png)

**3.4. VIDEO**

https://youtu.be/QOxjAdnbSPg

**3.5. CONCLUSIONES**

•	La polaridad de la fuente va a determinar el sentido de la corriente.

•	La ley de Ohm nos dice que la intensidad va a ser directamente proporcional al voltaje e inversamente proporcional a la resistencia.

•	Para medir el voltaje en cada nodo debemos colocar la punta positiva en el nodo y la negativa a tierra.

•	La ley de corrientes de Kirchhoff nos dice que la intensidad que entra a un nodo es igual a la que sale del mismo.

•	La ley de voltajes de Kirchhoff nos dice que la suma de todas las caídas de tensión es igual al voltaje de la fuente.

•	Debemos identificar cada voltaje en cada nodo y establecer relaciones con las resistencias existentes en el circuito.


