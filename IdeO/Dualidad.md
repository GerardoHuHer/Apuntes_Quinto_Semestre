Tags: [[Investigación de Operaciones]]
Fecha: 30/09/24

---
# Ejercicios de Dualidad
Es como transponer, cómo pasamos del modelo primal al modelo dual.
Ejemplo:
$$
Max \,\, z = 3x_1 + 5x_2
$$

| Planta 1 | $$x_1 \leq 4$$          |
| -------- | ----------------------- |
| Planta 2 | $$2x_2 \leq 12$$        |
| Planta 3 | $$3x_1 + 2x_2 \leq 18$$ |
|          |                         |
Si maximizo en el dual voy a min y viceversa, por convención Min o Max w y la variable será $$y_n$$
Tenemos las tres restricciones por lo tanto tenemos:
$$
Min \,\, w = 4y_1 + 12y_2 + 18y_3
$$
sa.
$$y_1 + 0y_2 + 3y_3  5$$
$$0+2y_2+2y_3$$
Al ser la tres restricciones menores o igual, entonces las variables se vuelven igual a cero _Ver tabla_
Al ser las variables mayores a cero las restricciones del modelo dual también son mayores. _Ver tabal_
![[Pasted image 20241002175854.png]]
# Ejemplo
_Pregunta de examen plantea el modelo dual a partir del primal._
_Pregunta de examen, calcular el valor de las variables duales a partir del tableau óptimo del primal._
Tengo tantas variables duales cómo restricciones.
