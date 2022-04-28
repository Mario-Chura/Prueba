# <Programación Web 2>

## Laboratorio 1
## Git y GitHub

### I.	 Objetivos
Aprender a manejar un sistema de control de versiones de manera colaborativa con varios
usuarios.
### II.	Temas a tratar

- •	Git
- •	Git-Hub

### III.	Integrantes

- •	Michael Benjamin Suclle Suca
- •	Daniel Edward Tapia Saenz
- •	Jose Andre Paredes Quispe
- •	Valery Cielo Iquise Mamani
- •	Chura Puma, Mario Franco

### IV.	Ejercicios

1.	Cree una cuenta de usuario en github
2.	Configure su cuenta de estudiante (https://education.github.com/pack).
3.	Creamos un nuevo proyecto en GitHub
4.	Crearemos un repositorio local usando git init
5.	Crearemos un archivo Readme.md con contenido Markup
6.	Agregaremos este archivo al staging area usando git add.
7.	Hacemos un primer commit en nuestro repositorio local git commit -m “mi primer proyecto en github”
8.	Asociamos el repositorio local con el repositorio remoto git remote add origin https://github.com/
9.	Actualizamos el repositorio remoto con git push origin master
10.	Ahora podemos verificar github que nuestro repositorio se actualizó con el archivo local.

### V.	Ejercicios Propuestos
- Se desea crear una clase Calculator en Java, que tenga las siguientes operaciones: add, sub, mul, div, mod; estas operaciones recibirán dos enteros y devolverán un entero.
- Forme grupos de 3 a 5 personas
- Un integrante del grupo deberá crear el proyecto principal, con el nombre de su grupo, con la plantilla base:
- class Calculator {
- int add(int a, int b){ return 0; }
- int sub(int a, int b){ return 0; }
- int mul(int a, int b){ return 0; }
- int div(int a, int b){ return 0; }
- int mod(int a, int b){ return 0; }
- }
- Comparta el proyecto con sus compañeros de grupo y asigne uno o dos métodos distintos a cada integrante del grupo.
- Los integrantes del grupo deberán hacer clone, push y pull según corresponda, de modo que el repositorio contenga la solución final.
- Reportar al profesor que logró culminar la tarea. La tarea debe ser compartida con el profesor (rescobedoq) y entregada usando el mismo url que se usó para clonar el repositorio.

### VI.	Desarrollo del laboratorio
- Código implementado
- class calculator {
- 	int add(int a, int b){
- 		return a + b;
-	}
-	int sub(int a, int b){
-		return a - b; 
-	}
-	int mul(int a, int b){ 
-		return a * b; 
-	}
-	int div(int a, int b){ 
-		try {
-		return a / b; 
-		} catch (Exception exception) {
-			System.out.println ("No puede dividir entre cero\n Error "+ exception.getMessage());
-		} finally {
-			return 0;
-		}
-	}
-	int mod(int a, int b){
-		return a % b;
-	}
- }


- Commit realizados
- se cambio el nombre de la clase a calculator
- @timysuclle3
- timysuclle3 committed 2 hours ago
- se añadio el manejo de la excepcion de la div entre cero
- @timysuclle3
- timysuclle3 committed 2 hours ago
- Función mod añadida (André Paredes)
- @Jerbo03
- Jerbo03 committed 4 hours ago
- agregando operacion division
- @Icielo23
- Icielo23 committed 6 hours ago
- creando un espacio
- @Icielo23
- Icielo23 committed 6 hours ago
- Corriguiendo identacion
- @Franco-Chura
- Franco-Chura committed 12 hours ago
- Añadiendo linea de la operacion de multiplicacion
- @Franco-Chura
- Franco-Chura committed 12 hours ago
- Se modifico los metodos add y sub
- @Daunsa
- Daunsa committed 12 hours ago
- Se agrego la clse Calculator
- @Daunsa
- Daunsa committed 12 hours ago
