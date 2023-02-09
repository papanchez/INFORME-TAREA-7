# INFORME-TAREA-7

UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE

FUNDAMENTOS DE CIRCUITOS ELÉCTRICOS

NRC: 10063

ESTUDIANTE:

PÁNCHEZ GUAMUSHIG PABLO ANDRES

1.OBJETIVOS

OBJETIVO GENERAL:

Comprender y entender lo que son los inductores y transformadores, por medio del análisis de los capítulos 13 y 14 del libro "Principios de circuitos eléctricos" de Thomas Floyd, además de desarrollar correctamente los ejercicios planteados en ambos capítulos y aplicar los conocimientos adquiridos en clase.

OBJETIVOS ESPECÍFICOS:

Identificar los distintos tipos de inductores exitentes y sus características.

Comprender como se dan las formulas exitentes para las diferentes características de los inductores, como por ejemplo la formula para la calcular la inductancia total en serie y paralelo.

Entender el funcionamineto de un transformador y sus características.

2.MARCO CONCEPTUAL


3.RESOLUCIÓN DE EJERCICIOS

SECCIÓN 13–1 El inductor básico

2. Convierta los siguientes valores en microhenries:

(a) 300 mH x 10^3 (uH/mH)=300000 uH 

(b) 0.08 H x 10^6 (uH/H)=80000 uH

(c) 5 mH x 10^3 (uH/mH)=5000uH

(d) 0.00045 mH x 10^3 (uH/mH)=0.45uH

4. Se inducen 50 volts en una bobina de 25 mH. ¿Con qué rapidez cambia la corriente?

Vind= L x I ==> I=Vind/L

I=50V/25mH= 2000 A/s

6. ¿Cuántas vueltas se requieren para producir 30 mH con una bobina enrollada sobre un núcleo cilíndrico cuya área de sección transversal mide 10 x 10^-5 m^2 y tiene longitud de 0.05 m? La permeabilidad del núcleo es de 1.2 x 10^-6 H/m. 

N= √(Ll/uA)

N=√((30mH x 0.05m)/((1.26 x 10^-6)(10x10^-5 m^2)))= 3450 Vueltas

8. Compare la inductancia de dos inductores idénticos excepto que el inductor 2 tiene dos veces la cantidad de vueltas del inductor 1.

Suponiendo que uA/l= z, que las vueltas del inductor 1 es N=1, y las vueltas del inductor 2 es N=2, entonces:

10. Un estudiante enrolla 100 vueltas de alambre sobre un lápiz de 7 mm de diámetro como se muestra en la figura 13-43. El lápiz es un núcleo no magnético de tal suerte que su permeabilidad es igual a la de un vacío (4pi x 10^-6 H/m). Determine la inductancia de la bobina que se formó.

![image](https://user-images.githubusercontent.com/116771507/217122771-3453dc35-286a-4d1f-825d-32a72b52f7f1.png)

l=3.5 cm= 0.035m

A=π r^2

A= π(4x10^-6 m)^2= 5.026 x 10^-9 m^2

L= N^2 uA/l= (100^2)(4x10^-6 H/m)(5.026x10^-9 m^2)/0.035m

L= 5.74 uH

SECCIÓN 13–3 Inductores en serie y en paralelo

12. Usted requiere una inductancia total de 50 mH. Tiene disponibles una bobina de 10 mH y otra de 22 mH.
¿Cuánta inductancia adicional necesita?

Lx= 50mH-10mH-22mH= 18mH

14. En la figura 13-45, ¿cuál es la inductancia total entre los puntos A y B con cada posición del interruptor?

![image](https://user-images.githubusercontent.com/116771507/217122828-d2fab213-f87a-4137-b2b0-309967571979.png)

POSICIÓN 1:

Lt= L1+L2+L4= 300uH+680uH+800uH = 1810uH

POSICIÓN 2:

Lt= L2+L4 = 680uH+800uH = 1480 uH

POSICIÓN 3:

Lt= L4= 800 uH

POSICIÓN 4:

Lt= 1/(1/L2+1/L4)

Lt=1/(1/1.5mH +1/800uH) = 0.52 mH


16. Usted tiene un inductor de 12 mH, y éste es su valor más bajo, pero necesita una inductancia de 8 mH. ¿Qué valor puede utilizar en paralelo con el inductor de 12 mH para obtener 8 mH?

8mH= L1(12mH)/(L1+12mH)

8mH(L1+12mH)= L1(12mH)

96 mH^2= 12mHL1-8mL1

L1= 96 mH^2/ 4mH = 24mH


18. Determine la inductancia total de cada circuito mostrado en la figura 13-47.

![image](https://user-images.githubusercontent.com/116771507/217122874-9688ba4e-bc21-44cf-823c-9317acc6e552.png)

CIRCUITO A

Lt= (100mH x 50mH)/150mH + (60mH x 40mH)/100mh 

CIRCUITO B

Lt= (12mH x 6mH)/18mH= 4mH

CIRCUITO C

Lt= 4mH+ (2mH x 4mH)/6mH = 5.33 mH

20. En un circuito RL en serie, determine cuánto tiempo se lleva la corriente para incrementarse a su valor
total con cada una de las siguientes combinaciones:

a) R= 56Ω, L=50uH

T= 5(50uH/56Ω)= 4.46 us

b)R=300Ω, L=15mH

T= 5(15mH/3300Ω)= 22.7 us

c)R=22kΩ, L=100mH

T= 5(100mH/22kΩ)= 22.7 us

22. Para el inductor ideal de la figura 13-49, calcule la corriente en cada uno de los siguientes instantes:

![image](https://user-images.githubusercontent.com/116771507/217123434-e20a9325-e226-48ea-8a05-a83bb2bfacbf.png)

T= 75mH/8.2kΩ = 9.15 us

If= 10V/8.2kΩ= 1.22mA

a)10 us

i= 1.22mA(1-e^(-10us/9.15us))= 0.811 mA

b)20 us

i= 1.22mA(1-e^(-20us/9.15us))= 1.08 mA

c)30 us

i= 1.22mA(1-e^(-30us/9.15us))= 1.17 mA

24. Repita el problema 22 para los siguientes instantes:

a)65 us

i= 1.22mA(1-e^(-65us/9.15us))= 1.218 mA

b)75 us

i= 1.22mA(1-e^(-75us/9.15us))= 1.219 mA

c)85 us

i= 1.22mA(1-e^(-85us/9.15us))= 1.22 mA

26. (a) ¿Cuál es la polaridad del voltaje inducido en el inductor de la figura 13-49 cuando la onda cuadrada está creciendo?

Dado la polaridad del voltaje inducido es tal que siempre se opne al cambio de corriente, por lo que la polaridad es negativa.

(b) ¿Cuál es la corriente justo antes de que la onda cuadrada se reduzca a cero?

If= Vs/R

If= 10V/8.2 kΩ = 1.22 mA

28. 

![image](https://user-images.githubusercontent.com/116771507/217123643-024ae2cc-8f9b-4e6f-8a81-977ba6a468cc.png)

(a) ¿Cuál es la corriente en el inductor 1.0 ms después de que se cierra el interruptor en la figura 13-50?

Rt= (8KΩ)||(11.5kΩ) = 4.72 kΩ

t= 3.3mH/4.72kΩ= 0.699 us
 
i= (569uA)e^(-1us/0.699us)=136uA


(b) ¿Cuál es la corriente después de que transcurren 5t?

t= 5(3.3mH/4.75kΩ)=3.496 us

i= (569uA)e^(-1us/3.496us)=427uA



SECCIÓN 13–5 Inductores en circuitos de ca

30. Determine la resistencia total para cada circuito de la figura 13-46 cuando se aplica voltaje a una frecuencia de 5 kHz entre las terminales.

![image](https://user-images.githubusercontent.com/116771507/217123768-ac3fc473-74e4-4cb3-af30-9fdde5581ad6.png)

CIRCUITO A

Lt= 1H+ (10H x 5H)/(10H + 5H) = 4.33H

Xl= 2π(5kHz x 4.33H) = 136 kΩ}

CIRCUITOS B

Lt= 100mH/2 = 50 mH

Xl= 2π(5kHz x 50 mH)= 1.57 kΩ


CIRCUITO C

Lt= 1/(1/100uH + 1/200uH+ 1/400uH)= 57uH 

Xl= 2π(5kHz x 57uH)= 1.79 Ω



32. En la figura 13-51, determine la corriente rms total. ¿Cuáles son las corrientes a través de L2 y L3?

![image](https://user-images.githubusercontent.com/116771507/217123836-9aa75053-54e0-4a7e-984b-7fb57fd43852.png)

Lt= 50mH + (20mH x 40mH)/60mH = 63.3 mH

Xl(total)= 2π(2.5kHz x 63.3mH)= 994 Ω

Xl2= 2π(2.5kHz x 20mH)= 314Ω

Xl3= 2π(2.5kHz x 40mH)= 628Ω

It= Vrms/Xl(total) = 10V/994Ω= 10.1 mA

Il2= (628Ω/ 314Ω+328Ω) x 10.1mA = 6.7 mA

Il3= (314Ω/ 314Ω+328Ω) x 10.1mA = 3.37 mA


34. En la figura 13-51, determine la potencia reactiva.

Xl(total)= 2π(52.5kHz x 63.3mH)= 994 Ω

Pr= (10.1 mA)^2 (994Ω)= 101 mVAR

CAPÍTULO 14

SECCIÓN 14–1 Inductancia mutua

2. Determine el coeficiente de acoplamiento cuando LM=1 uH, L1=8 uH, y L2=2 uH.

K= LM/√(L1 x L2) = 1uH/√(8uH x 2uH)= 0.25


SECCIÓN 14–2 El transformador básico

4. Cierto transformador tiene 250 vueltas en su devanado primario. Para duplicar el voltaje, ¿cuántas vueltas debe haber en el devanado secundario?

Nsec= 2Npri= 2 x 250 = 500 vueltas

SECCIÓN 14–3 Transformadores elevadores y reductores

6. Para elevar 240 V de ca a 720 V, ¿cuál debe ser la relación de vueltas?

n= Vsec/Vpri= 720V/ 240V = 3 

8. ¿Cuántos volts primarios se deben aplicar a un transformador que tiene relación de vueltas de 10 para obtener un voltaje secundario de 60 V de ca?

n= Vsec/Vpri= 10

Vpri= (1/n)Vsec = (1/10)60V = 6V


10. El devanado primario de un transformador tiene 1200 V a través de él. ¿Cuál es el voltaje secundario si la relación de vueltas es de 0.2?

Vsec= 0.2 x 1200V= 240V

12. ¿Cuál es el voltaje a través de la carga en cada uno de los circuitos de la figura 14-43?

![image](https://user-images.githubusercontent.com/116771507/217124248-9fc6f3c8-6afb-4bbd-bb93-0cad997733e9.png)

CIRCUITO A

VL= (Nsec/Npri)Vpri= (1/20)120V= 6V

CIRCUITO B

VL= (2/1) x 0V = 0V

CIRCUITO C

VL= (4)x 10V= 40V

SECCIÓN 14–4 Carga del devanado secundario

14. Determine Is en la figura 14-45. ¿Cuál es el valor de RL?

![image](https://user-images.githubusercontent.com/116771507/217124377-f7e3b637-c51f-4c63-96e6-ca6df8e34f48.png)

n= 1/3

Isec= (1/3) x 100mA= 33.3mA


33.2mA= 20V/RL ==> RL= 20V/33.3mA = 600Ω



SECCIÓN 14–5 Carga reflejada

16. ¿Cuál es la resistencia en la carga vista por la fuente en la figura 14-47?

![image](https://user-images.githubusercontent.com/116771507/217124420-9bc64ff6-2ed0-4b54-954d-a9f9acc9a865.png)

Rpri= (1/5)^2 x 680Ω= 27.2Ω

SECCIÓN 14–6 Igualación de impedancia

18. En el circuito de la figura 14-49, encuentre la relación de vueltas requerida para suministrar potencia máxima al altavoz de 4 Ω.

![image](https://user-images.githubusercontent.com/116771507/217124497-12e42fd5-6abf-4b06-8ca9-4b8d4a44d6a7.png)

1/n = √(Rpri/RL) 

1/n = √(16Ω/4Ω) 

1/n = 2

n=1/2 = 0.5


20. Encuentre la relación de vueltas apropiada en cada una de las posiciones mostradas en la figura 14-50 para transferir potencia máxima a cada carga cuando la resistencia de fuente es de 10 Ω. Especifique el número de vueltas requerido para el devanado secundario si el devanado primario tiene 1000 vueltas.

![image](https://user-images.githubusercontent.com/116771507/217124663-68d03ad1-45e3-48f6-8719-8b1beb93422f.png)

POSICIÓN 1

RT= 560Ω+220Ω+1kΩ= 1780 Ω

n=√(RT/Rpri) = √(1780Ω/10Ω) = 13.3

Nsec= 13.3 x 100 = 1300 vueltas

POSICIÓN 2

RT= 220Ω+1KΩ = 1220Ω

n=√(RT/Rpri) = √(1220Ω/10Ω)=11

Nsec= 11 x 100= 1100 Vueltas

POSICIÓN 3

RT= 1kΩ

n=√(RT/Rpri) = √(1000Ω/10Ω)=10

Nsec= 10 x 100 = 1000 vueltas



SECCIÓN 14–7 Características de un transformador no ideal

22. ¿Cuál es la eficiencia del transformador en el problema 21?

PL= Ppri-Pperdido= 100W-5.5W= 94.5W

%eficiencia= (Psalida/Pentrada) x 100%

%eficiencia= (94.5W/100W) x 100%= 94.5%


24. La potencia nominal de cierto transformador es de 1 kVA. El transformador opera a 60 Hz y 120 V de ca. El voltaje secundario es de 600 V.

(a) ¿Cuál es la corriente máxima en la carga?

IL(max)= Pa/Vsec

IL(max)= 1kVA/600V= 1.67A

(b) ¿Cuál es el valor RL más pequeño que puede ser excitado?

RL(min)= Vsec/IL(max) = 600V/1.67A = 359Ω

(c) ¿Cuál es el capacitor más grande que se puede conectar como carga?

Cmax= 1/2πfXc= 1/(2π x 60Hz x 359Ω) = 7.4 uF



26. La potencia nominal de cierto transformador es de 5 kVA, 2400/120 V, a 60 Hz.

(a) ¿Cuál es la relación de vueltas si los 120 V son el voltaje secundario?

Vpri= 2400V

n= Nsec/Npri= 120V/2400= 0.05 

(b) ¿Cuál es la corriente nominal del secundario si los 2400 V son el voltaje primario?

Isec= Pa/Vsec = 5KVA/120V= 41.7A

(c) ¿Cuál es la corriente nominal del devanado primario si los 2400 V son el voltaje primario?

Iprim= n x Isec= 0.05 x 41.7A= 2.09A


SECCIÓN 14–8 Transformadores con tomas y devanados múltiples

28. Con los voltajes indicados en la figura 14-52, determine la relación de vueltas de cada sección de toma del devanado secundario al devanado primario

![image](https://user-images.githubusercontent.com/116771507/217124860-f712e671-86fc-44f1-9d05-a968236bec32.png)

SECUNDARIO 1

n= Vsec/Vpri= 24V/12V = 2

SECUNDARIO 2

n= Vsec/Vpri= 6V/12V = 0.5


SECUNDARIO 3

n= Vsec/Vpri= 3V/12V = 0.25


30. En la figura 14-54, cada primario puede acomodar 120 V de ca. ¿Cómo se deberán conectar los primarios para que operen con 240 V de ca? Determine cada voltaje secundario para operación con 240 V

![image](https://user-images.githubusercontent.com/116771507/217124910-1e94a67a-89f4-40d6-94a2-afcb21a7425e.png)

1) 100 VUELTAS

Vsec= (100/2000)240V= 12V

2) 200 VUELTAS

Vsec= (200/2000)240V= 24V

3) 500 VUELTAS

Vsec= (500/2000)240V= 60V

4) 1000 VUELTAS

Vsec= (1000/2000)240V= 120V



SECCIÓN 14–9 Localización de fallas

32. Cuando se aplican 120 V de ca a través del devanado primario de un transformador y se verifica el voltaje en el devanado secundario, se leen 0 V. Una investigación más a fondo muestra que no hay corriente en el primario ni en el secundario. Enumere las posibles fallas. ¿Cuál es el siguiente paso en la investigación del problema?

El devanado primario está abierto, por lo tanto el siguiente paso es reemplazar el transformador.


34. Mientras usted revisa un transformador, se da cuenta que el voltaje secundario es menor de lo que debería ser aunque no es de cero. ¿Cuál es la falla más probable?

Algunos de los devanados secundarios podrían estar en cortocircuito o quizas el voltaje primario es inferior al esperado.


5. CONCLUSIONES

Gracias a la realización de este informe se puede llegar a la conclusión de que se ha comprendido las funciones y caracteríticas que tiene un inductor y un transformador como por ejemplo los inductores principalmente se dividen en inductores variables y fijos, no obstante, esta clasificación se considera ambigua, por lo que ahora si clasifican según su núcleo, entre los más utilizados se encuentran los inductores con núcleos de aire, hierro y ferrita; o  que entre las principales características de un transformador no ideal están; resistencia de devanado: en este caso la resistencia resulta en menos voltaje a través de una carga secundaria. Pérdidas en el núcleo: las perdidas se dan en las conversiones de energía en el material del núcleo de un transformador práctico.
En conclusión, gracias a lo aprendido durante el analisis de los capítulos 13 y 14 el libro "Principios de circuitos eléctricos" de Thomas Floyd, se llego a obtener y reforzar conocimientos, lo que permitió realizar de la mejor manera los ejercicios propuestos.

6. BIBLIOGRAFÍA

FLOYD, THOMAS L. Principios de circuitos eléctricos. Octava edición. PEARSON EDUCACIÓN, México, 2007.



