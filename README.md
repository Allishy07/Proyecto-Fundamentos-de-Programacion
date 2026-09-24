# Proyecto-Fundamentos-de-Programacion
# Gestor de rutinas de entrenamiento y cargas de entrenamiento 
## Contexto
Para el desarrollo de fuerza y el entrenamiento basado en la hipertrofia es imprescindible llevar un registro riguroso con el objetivo de realizar una sobrecarga progresiva. Esto para que los músculos crezcan y se fortalezcan, es necesario que poco a poco someter a los músculos a estímulos mayores, ya sea incrementando el peso, las repeticiones o las series. También es esencial seguir un entrenamiento estructurado mediante "splits" para llevar una bitácora precisa. Registrar estos datos, además  ayuda a planificar sesiones futuras para asegurar una mejora continua y evitar el estancamiento. 

En este proyecto se espera realizar un gestor de rutinas de levantamiento de pesas diseñado para registrar y analizar el progreso físico del usuario. Este proyecto resulta particularmente interesante porque transforma un registro manual a un modelo computacional estructurado, que se convierte en una utilidad genuina. Cualquier persona enfocada en el acondicionamiento físico puede integrarlo en su día a día para medir y optimizar su progresión real en el gimnasio. 
# Algoritmo
## Entrada
- Ejercicios 
- Peso del ejercicio
- Número de series 
- Número de repeticiones

## Proceso

**Inicio**
1. Iniciar una lista vacía llamada Rutina del dia.
2. Definir variable Continuar = "Sí".
3. Mientras Continua sea igual a "Sí":
   - Insertar nombre del ejercicio.
   - Guardar nombre del ejercicio.
   - Insertar peso del ejercicio.
   - Guardar peso del ejercicio.
   - Insertar número de series.
   - Guardar número de series.
   - Insertar el número de repeticiones.
   - Guardar número de repeticiones.
   - Agrupar los datos (nombre del ejercicio, peso, series, repeticiones) en Registro Actual.
   - Guardar Registro Actual a Rutina del día.
   - Preguntar al usuario si desea agregar otro ejercicio al split de hoy.
     - Si es "Sí": repetir el proceso.
     - Si es "No": continuar.
4. Fin del ciclo.
5. Guardar el contenido de `Rutina del dia`.

Fin
