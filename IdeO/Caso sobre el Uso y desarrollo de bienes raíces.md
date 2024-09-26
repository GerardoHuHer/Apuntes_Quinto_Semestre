Tags: [[Investigación de Operaciones]]
# Caso Desarrollo Alpha
Desarrollos Alfa posee 800 acres (1 acre = 4046m2) de terreno en un lago escénico en el corazón de una sierra. Antes se aplicaban pocos o ningún reglamento a los nuevos desarrollos en torno al lago. Las orillas del mismo están ahora pobladas con casas de campo, y debido a la carencia de servicios de alcantarillado, hay muchas fosas sépticas, en su mayor parte mal instaladas. A través de los años , las filtraciones de las fosas sépticas ha ocasionado un grave problema de contaminación de agua.
Para mitigar el degradamiento de la calidad del agua, las autoridades municipales aprobaron reglamentos estrictos para todos los desarrollos en el futuro.
1. Sólo se pueden construir casas para una, dos y tres familias, y las casas unifamiliares deben ser al menos el 50% del total.
2. Para limitar la cantidad de fosas sépticas, se requieren tamaños mínimos de lote de 2, 3 y 4 acres para las casas con una, dos y tres familias, respectivamente.
3. Se deben establecer áreas de recreo de 1 acre cada una, en una proporción de una por 200 familias.
4. Para preservar la ecología el lago, no se debe bombear agua subterránea para uso doméstico ni de riego.
El presidente de Desarrollos Alfa estudia la posibilidad de desarrollar los 800 acres de la empresa. El nuevo desarrollo incluirá casas para una, dos y tres familias. Se estima que el 15% de los acres se debe asignar a calles y servicios comunitarios. Alfa estima que los ingresos por las diversas unidades de habitación serán:

| Unidades de Habitación          | Una   | Dos   | Tres  |
| ------------------------------- | ----- | ----- | ----- |
| Rendimiento neto por unidad ($) | 10000 | 12000 | 15000 |
El costo de conectar el servicio del agua al área es proporcional a la cantidad de unidades construidas. Sin embargo, el municipio cobra un mínimo de $100000 por el proyecto. Además, el aumento de la capacidad actual del sistema de abastecimiento de agua se limita a 200000 galones por día, durante las temporadas pico.
Los datos siguientes resumen el costo de conectar el servicio del agua, y también el consumo del agua, suponiendo familias de tamaño promedio.

| Unidades por Habitación                      | Una | Dos  | Tres | Parques y Jardines |
| -------------------------------------------- | --- | ---- | ---- | ------------------ |
| Costo por el servicio de agua por unidad ($) | 100 | 1200 | 1400 | 800                |
| Consumo de agua por unidad (Gal/ día)        | 400 | 600  | 840  | 450                |
La empresa debe decidir la cantidad de unidades de cada tipo de vivienda que va a construir, y también la cantidad de áreas de recreo que satisfaga el reglamento municipal, de tal manera que maximice su rendimiento total.
## Variables
$$
x_1 = Número \,\, de \,\, Casa \, \, para \,\, 1 \,\,familia
$$
$$
x_2 = Número \,\, de \,\, Casa \, \, para \,\, 2 \,\,familia
$$
$$
x_3 = Número \,\, de \,\, Casa \, \, para \,\, 3 \,\,familia
$$
$$
x_4 = Área \,\, de \,\, Recreo.
$$

## Función Objetivo
$$
Max \, \, z = 10,000x_1 + 12,000x_2 + 15,000x_3
$$
## Restricciones
$$
x_1 \geq 50\% \times(x_1 + x_2 + x_3) => \frac{1}{2}x_1 - \frac{1}{2}x_2 - \frac{1}{2}x_3 \geq 0
$$
$$
2x_1 + 3x_2 + 4x_3 + x_4 \leq 680
$$
$$
	\frac{x_1 + 2x_2 + 3x_3 }{200} \geq x_4 => x_1 + 2x_2 + 3x_3  - 200x_4 \geq 0
$$
$$
	1000x_1 + 1200x_2 + 1400x_3 + 800x_4 \geq 100,000
$$
$$
400x_1 + 600x_2 + 840x_3 + 450x_4 \leq 200,000
$$
$$
x_i \geq 0, \, i \in \{1,2,3,4\}
$$
# Caso "Papelera Moderna"
La Papelera Moderna produce rollos de papel (rollos de ancho estándar; so tal como salen de la máquina de papel) de 20 pies de ancho normal útil, cada uno.
Se atienden los pedidos de los clientes, con anchos distintos, cortando los rollos de ancho estándar. Los pedidos normales, que pueden variar de un día al siguiente, se resumen en la siguiente tabla:
Cliente 1: ancho 5 pies           150 rollos
Cliente 2: ancho 7 pies          200 rollos
Cliente 3: ancho 9 pies          300 rollos
## Variables
Todas las posibles posiciones de las navajas.
Posición 1: 7|9|4 
Posición 2: 5|5|7|2
Posición 3: 5|5|9| 1
Posición 4: 5|5|5|5
Posición 5: 7|7|5|1
Posición 6: 9|9|2
## Función Objetivo
Min z = x1 + x2 + x3 + x4 + x5 + x6
## Restricciones
R1: 5 pies 0x1 + 2x2 + 2x3 + 4x4 + x5 + 0x6 >= 150
R2: 7 pies x1 + x2 + 0x3 + 0x4 + 2x5 + 0x6 >= 200
R3: 9 pies x1 + 0x2 + x3 + 0x4 + 0x5 + 2x6 >= 300
$$
x_i \in \mathbf{Z^{+}}
$$

# Caso de política bancaria préstamos
El Banco Nacional Suizo está desarrollando una política de préstamos por un máximo de Fr$ 12 millones. La siguiente tabla muestra los datos pertinentes acerca de los distintos tipos de préstamo.

| Tipo de Préstamo | Tasa de Interés | % de deuda impagable |
| ---------------- | --------------- | -------------------- |
| Persognal        | 0.140           | 0.10                 |
| Automóvil        | 0.130           | 0.07                 |
| Casa             | 0.120           | 0.03                 |
| Agrícola         | 0.125           | 0.05                 |
| Comercial        | 0.100           | 0.02                 |
Las deudas impagables no se recuperan y no producen ingresos por intereses.
Para competir con otras instituciones financieras se necesita que el banco asigne un mínimo de 40% de los fondos a préstamos agrícolas y comerciales.
==Para ayudar a la industria de la construcción de su región, los préstamos de casa deben ser iguales, cuando menos, al 50% de los préstamos personales, para automóvil y para casa.==
También el banco tiene una política explícita que no permite que la relación general de préstamos impagables entre todos los préstamos sea mayor al 4%.
Uno supuesto importante es que todos los préstamos se otorgan aproximadamente al mismo tiempo. Esta hipótesis permite ignorar diferencias en el tiempo del valor de los fondos asignados a los diversos préstamos.
El objetivo del Banco es maximizar su retorno neto, que es la diferencia entre el retorno por intereses y los préstamos impagables.

## Variables
$$
x_1 = Cantidad \,\, asignada \,\, a \, \, préstamos \, \, Personal.
$$
$$
x_2 = Retorno \, \, de \, \, préstamos \, \, Automóvil.
$$
$$
x_3 = Retorno \,\,  de \,\, préstamos \,\, Casa.
$$
$$
x_4 = Retorno \,\, de \,\, préstamos \,\, Agrícola.
$$
$$
x_5 = Retorno \,\, de \,\, préstamos \,\, Comercial.
$$
## Función Objetivo
La resta [(1-0.1), (1-0.07),...] se hace porque le estoy reduciendo la deuda impagable, es decir solo estoy considerando lo que sé que me van a pagar.
$$
Max \, \, z = ((1-0.1)x_1)0.14 + ((1-0.07)x_2)0.13 + ((1-0.03)x_3)x_3 + ((1-0.05)x_4)0.125 + ((1-0.02)x_5)0.1 - 0.1x_1 - 0.07x_2 - 0.03x_3 - 0.05x_4 - 0.02x_5
$$
$$
Max \,\, z = 0.026x_1 + 0.0509x_2 + 0.086x_3 + 0.06875x_4 + 0.078x_5
$$
## Restricciones
$$
x_1 + x_2 + x_3 + x_4 + x_5 \leq 12,000,000
$$
$$
x_4 + x_5 \geq 12,000,000 \times 0.4
$$
---

$$
\frac{0.1x_1 + 0.07x_2 + 0.03x_3 + 0.05x_4 + 0.02x_5}{x_1+x_2+x_3+x_4+x_5} < 0.4
$$
$$
0.06x_1 + 0.03x_2 - 0.01x_3 + 0.01x_4 - 0.02x_5 \leq 0
$$
---

$$
x_3 \geq 50\%(x_1 + x_2 + x_3) => \frac{1}{2}x_3-\frac{1}{2}x_2-\frac{1}{2}x_1 \geq 0
$$
$$
x_i \geq 0 , i \in \{1,2,3,4,5\}
$$
