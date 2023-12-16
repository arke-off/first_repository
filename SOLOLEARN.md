_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _   
Glosario	|
_ _ _ _ _ _	|


# palabras

	busy		-	ocupado
	checkout	-	comprobación/pasar por caja
	fork		-	bifurcación
	branch		-	rama
	header		-	cabecera
	also		-	también
	whole		-	completo
	hint		-	pista/sugerencia	
	cautious	-	cauteloso/precavido
	intent		-	intento/intención
	blank		-	espacio/blanco
	above		-	arriba /anteriormente/brindado
	curly		-	rizado
	does		-	hace
	drag		-	arrastra
	drop		-	suelta
	takeaways	-	aportes/llevados/extraídos
	quote		-	cita	
	insights	-	información
	trends		-	tendencias	
	driven		-	impulsado/dirigido
	dive		-	sumergir
	deeper		-	más profundo
	steps		-	etapas/pasos
	several		-	varios
	retrive		-	recuperar
	clothings	-	prendas/ropa
	shoes		-	zapatos
	either		-	ya sea
	lets		-	permite
	powerful	-	potende/poderosa
	harness		-	aprovechar
	entry		-	entrada/ingresado
	could		-	podría
	passed		-	fue pasado/trasladado
	turn		-	girar/transformar/convertir
	calculation	-	operación
	remainde	-	resto
	solve		-	resolver
	coach		-	entrenador
	almost		-	casi
	perform		-	realizar	
	once		-	una vez
	desired		-	deseado/a
	greeting	-	saludo
	type		-	escriba
	its			-	su
	purpose		-	propósito
	reusable	-	reutilizable
	tuned		-	sintonizado
	baggage		-	equipage
	fee			-	taza/tarifa
	billed		-	facturado
	Foward		-	adelante
	either		-	cualquiera
	avoid		-	evitar
	assign		-	asignar
	instead		-	en cambio
	outputting	-	salida
	fees		-	honorarios/tarifas
	useful		-	útil
	swap		-	intercambio
	accomplish	-	lograr
	below		-	abajo/a continuación
	tells		-	que dice/indica
	accurate	-	precisa
	accurately	-	precisamente
	bold		-	negrita
	made		-	hecho
	statements	-	declaraciones
	easiest		-	más fácil
	both		-	ambos/ambas
	surround 	-	rodear/encerrar
	Labels		-	etiqueta
	budget		-	presupuesto


# frases
	
	that has been				-		eso ha sido
	did you notice				-		Te diste cuenta
	the upstream branch			-		la rama anterior de la cadena
	does not match				-		no coincide con
	is not what it once was		-		ya no es lo que era
	is not what					-		no es lo que
	your findings				-		tus resultados/concluciones
	How would visualize			-		como le gustaría ?
	visual aids					-		apoyos visuales
	at least					-		por lo menos/como mínimo/al menos
	have been					-		han sido
	of orders					-		de pedidos
	you´ll dive					-		te sumergirás
	help us						-		nos ayudan
	a lot of					-		un montón de
	it indicates				-		indica que
	as a						-		como un
	as it						-		ya que
	curly braces				-		llaves rizadas {}
	the function´s body			-		el cuerpo de la función	
	lessons takeaways			-		enseñanzas extraídas
	data insights				-		información sobre los datos
	cleaned data				-		datos depurados
	finding hidden patterns		-		busqueda de patrones ocultos
	spot trends					-		tendencias puntuales
	data storytelling			-		narración de datos
	turn data insights			-		convertis los datos en información
	the need					-		la necesidad
	huge						-		enorme
	lets try to					-		vamos a intentar
	value it hold				-		valor que contiene
	or as we call				-		o como nosotros llamamos
	assign it a value			-		asignarle un valor
	we have seen				-		nosotros hemos visto
	removes any remainder		-		elimina cualquier resto
	that is going to hold		-		lo que va a mantener/contener	
	has some					-		tiene algunas
	it has						-		consta de
	wich tells					-		que dice/indica
	does not have				-		no dispone de
	type its					-		escriba su
	a bag weighting up to		-		una bolsa que pese hasta
	do you mind					-		¿Te importa?/¿Te importaría?
	so far						-		hasta ahora
	so that 					-		de modo que 
	they are					-		ellos son
	we have already				-		ya lo tenemos
	another thing				-		otra cosa
	can accomplish				-		puede lograr
	what would you call?		-		¿Cómo llamarías?
	what would you				-		Qué haría usted
	newspaper					-		periódico
	out there					-		allí afuera
	shouldn't					-		no debería










_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ 							
SQL	|
_ _ |


#4 Data Analysis






	Making Sense of Data

		-	1. Question		2. Collect		3. Clean		4. Insights		5. Communicate 

		- SELECT product, SUM(qty)
		FROM sales
		  WHERE month = 'June'
		  GROUP BY product

		- a boolean

		- The Hobbit , A Game of Thrones

		- a data type with two possible values: True or False

		- one boolean value		->	true + false = True
	
		-True					->	true AND true = True
	
		- SELECT title
		  FROM books
		  WHERE qty >= 5 AND year > 1950
	
		- A Game of Thrones
	
		- False				->	False AND True
	
		- 1 , 5				->	id values meet the multiple conditions
	
		- id , WHERE , AND
	
		- True				->	True OR False = True
	
		- False				->	False OR False = False
	
		- True OR				->	True OR False = True
	
		- The Lord of the Rings , Harry Potter		->	SELECT TITLE
											FROM books
											WHERE year = 1997
											OR qty < 3;
	
		- WHERE , OR						->	SELECT *
											FROM products
											WHERE category 	= "Clothing"
											OR category 	= "Shoes";
							
		- WHERE , OR						->	SELECT *
											FROM users
											WHERE p_number = 854930340
											OR username = "ann88";





		Module 4 Quiz

		- asking questions

		- Data duplication

		- country , Delivered

		- 3

		- The logical operator is missing

		- Querying a database

		- Using APIs , Scraping web pages , Querying a database

		- DISTINCT

		- Frodo Baggins , Oliver Twist

		- AND , 5






_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ 							
C	|
_ _ |


#1 Basic Concepts


	Output Formatting|

		- // printf ("%d", 253);
	
		- |%d|
	
		- // printf ("%f", 3.14);
	
		- // printf ("%c", 'X') 
	
		- |%c| , |'A'|
	
		- // printf ("Score: %f. Level: %d", 42.8 , 4);
	
		- 32z
	
		- |/n| , |/n| , |/n| , |'B'|, |'C'|


		Product Labels

		- L4	printf("Product: %s \n", "LCD Monitor");	// change <d> to <s>

		LESSON TAKEAWAYS
		%d is for whole numbers
		%f is for floating point numbers
		%c is for single characters
		%s is for strings

		NOTES
		You can combine multiple format specifiers in a single printf() statement. Remember to provide the corresponding values for each specifier, separated by commas.


	Variables|

		- next

		- next

		- |int| , |level|

		- next

		- |int| , |=|

		- next

		- |int| , |level| , |%d| , |level|

		- next

		- next

		- |83|


		Practice

		- L5 printf("Price: $%d",price);

		LESSON TAKEAWAYS

		A variable has a name and a type of the value it holds. 
		To declare a variable use the type followed by the name of the variable.
		The int type is used to store whole numbers.
		You can assign a value to the declared variable using the = operator.
		A variable can change its value during the program, by being assigned to a new value.
		We will learn about more variable types in the next lesson! 


		NOTES
		int score;
		score = 253;
		printf ("%d",score);
		We used the %d format specifier, as score is an integer, and passed score to the printf function as the value to be inserted.


	Data Types|

		- next

		- |int| , |=| , |,|

		- next

		- next

		- |%f| , |%lf| , |%d|

		- next

		- next

		- |%c| , |%d| , |,|

		- next

		- next

		- |const| , |float| , |CAPACITY|


		Practice

		- L4 char letter = 'B';
		- L5 int number = 127;

		LESSON TAKEAWAYS
		int is used to hold whole numbers (integers)
		float and double store decimals.
		float is similar to double, but has less precision and requires less memory.
		char holds a single character.
		The const keyword is used to define a constant, which is a variable that cannot be changed (is read-only)


		NOTES
		To store decimals (or floating point numbers), C provides the float and double data types.
		The format specifier for double is %lf.

		float uses less storage in the memory, but is not as precise as the double type.
		This means that calculations that use floats are faster than the ones that use double, however, the results are less accurate in terms of the decimal digits.
		Generally, float is sufficient for storing 7 decimal digits, while double can hold 15 decimal digits.

		The char type is used to store a single character.
		It is similar to declaring a string, but uses single quotes for the value:
		%c is the format specifier for the char type.

		Variables can be defined as constants. This means that they cannot be changed.
		To define a constant, use the const keyword before the data type of the variable, for example:
		const int num = 42;
		Now, num is a constant, and its value is read-only.


	Doing Math

		- next

		- next

		- |6|

		- next

		- next

		- next

		- |2|

		- |4|

		Practice

		- RUN		//int result = (number*perc)/100;	

		LESSON TAKEAWAYS
		Hint: To calculate perc percent of number, multiply number by perc, then divide the result by 100
		Doing math with C is fun! Here are some key takeaways:
		You can use basic math operators to perform calculations with values and variables.
		+ is addition
		- is subtraction
		/ is division
		Dividing integers results in an integer, while dividing floats results in a float.
		% finds the remainder of a division.


		NOTES
		int x = 8;
		int y = 4;
		printf("%d", x+y);

		int won = 8;
		int lost = 3;
		int score = won- lost;

		Left to right order First priority for * / •/• and then Left to right order for + , -
		The division / operator performs differently depending on the data types of the operands. When both operands are integers, integer division, (also called truncated division), removes any remainder to result in an integer.

		For example, let's convert the given kilobytes value to megabytes:
		int kb = 35800;
		int mb = kb/1024;
		printf("%d", mb);
		The result will be an integer.

		The % remainder operator (also called the modulo) is used to find the remainder of a division.
		Let's find out how many of 100 items will be left over if we divide them into boxes of 8:
		int items = 100;
		int per_box = 8;
		int left_over = items % per_box;
		Click to run


#2 Conditionals and Loops


#3 Arrays & strings


	Arrays


	Looping over Arrays (complete)

		- next

		- next

		- |for|,	|i<4|,	|printf|,	|\n|,	|[i]|

		- next

		- next

		- next

		- next

		- |3|

		- next


		Practice

		int f;
		int ganado;
    	for(f=0;    f<28;   f++){
        if (results[f]==1){
        ganado++;
        }
    	}
        printf("%d",ganado);
	

		LESSON TAKEAWAYS

		You can use a for loop to loop over an array.
		For example, for an array called arr of 6 items:

		for(int x=0;x<6; x++) {
		   //current item is arr[x]
		}

		Arrays with multiple dimensions are simply arrays that contain other arrays.

		The number of square brackets match the dimension of the array, for example [][] 		denotes a 2-dimensional array.

		To access the items of the array, specify the row index in the first square 		brackets, followed by the column index in the second.


		NOTES
		We can use a loop to iterate over the items of an array.
		For example, let's simply output all the items using a for loop:

		int ages[] = {31, 18, 24, 55, 29};
		for(int i=0;i<5;i++) {
  		printf("%d \n", ages[i]);
		}

		We used the i variable of the loop as the index for our array. During each iteration of the loop it is incremented and used to access the corresponding item of the array.
		
		That we need to set the condition based on the size of the array, in our case, there are 5 elements, so we used the condition i<5 in the loop, as i starts from 0.
		-
		We can also use loops to perform calculations with arrays.
		For example, let's calculate the sum of all values of the ages array:

		int ages[] = {31, 18, 24, 55, 29};
		int total = 0;
		for(int i=0;i<5;i++) {
		total += ages[i];
		}
		printf("Sum: %d", total);
	
		In the code above, we declared a variable total to store the result and assigned it 0.
		Then, in the for loop, we added the value of each item of the array to it.
		-
		Multidimensional Arrays
		An array can have multiple dimensions (or indices) to represent a grid.
		For example, imagine a ticketing program for a stadium that is storing the seats, which have a row and column number.
		Or a map, where each square has 2 coordinates.
		
		For these cases, our array can have 2 dimensions, one for the row, the other for the column.
		-
		To create multidimensional arrays, place each array within its own set of square brackets:

		int ages[2][4] = {{1, 2, 3, 4}, {5, 6, 7, 8}};

		The array has two dimensions: 2 rows and 4 columns.
		-
		The elements are accessed by using the row index and column index of the array.
		For example, let's output the 3rd item of the 2nd array:
	
		#include <stdio.h>
		int main() {
   		int ages[2][4] = {{1, 2, 3, 4}, {5, 6, 7, 8}};
    	printf("%d", ages[1][2]);
    	return 0;
		}

		|7|

		The first index accesses the 2nd array, while the second index accesses the 3rd item in it.
		-
		When declaring multi-dimensional arrays, the size of each dimension must be defined. 
		Also, we can format the values of each row in the following way, to make the code easier to read:

		#include <stdio.h>
		int main() {
   		int ages[2][4] = {
        {1, 2, 3, 4},
        {5, 6, 7, 8}
   		};
  		printf("%d", ages[1][2]);
		return 0;
		}

		|7|
		-
		We can loop over a two-dimensional array using nested for loops:

		#include <stdio.h>
		int main() {
    	int ages[2][4] = {
        {1, 2, 3, 4},
        {5, 6, 7, 8}
    	};
    	for(int i=0;i<2;i++) {
        for(int j=0;j<4;j++) {
        printf("%d ", ages[i][j]);
        }
        printf("\n");
    	}
    	return 0;
		}

		|1 2 3 4 
		5 6 7 8|

		The first loop iterates over the rows, the second one over their items.


	Strings


	Taking String Input (complete)

		- next

		- next

		- |char|, |scan|, |%s|, |word|

		- |the firsl word|

		- next

		- |fgets|, |desc|, |100|, |stdin|

		- 

		- 

		Practice

		Which Letter?		
		L6 scanf("%s",word);
   		L7 scanf("%d",&position);
    	L8 printf("%c",word[position]);								


		LESSON TAKEAWAYS
		Here is how you take a string from input:
		The %s format specifier can be used to take a string as input using the scanf() 		function.
		However, this method will only store the first word of the input, before the 		first space.
		The fgets() function can be used to take a line of text, that contains spaces. 		Here is the syntax:

		fgets(string, size, stdin);

		string is the variable to store the input, size is the maximum size, stdin is a keyword.
		Also, remember that the variable needs to be a char array.

		Use scanf() to take one word inputs and fgets() to take a line of text.


		NOTES
		You can take string input from the user using the same scanf() function, using the %s format specifier.
		For example:

		char name[50];
		scanf("%s", name);

		Note, that we dont need the & symbol before the variable in scanf(), because the variable is a char array.
		-
		Also, note that we have specified a size for the array, that is going to hold the input.
		We used a large number, which should be able to handle the input.
		
		char name[50];
		
		This method has some limitations when taking input: if the input contains spaces, only the first word will be taken.
		-
		In case we need to take multiple words as input, we can use the fgets() function.
		Here is the syntax:

		fgets(name, 50, stdin);

		It has 3 parts: the variable to store the input, the maximum size, and the stdin keyword, which tells to take the input from the user.
		Now, the input can contain any number of spaces and will be stored entirely.


	Module Quiz

		- |%d|, |x|, |2|

		- |12|

		-|for|, |i|, |arr|,

		-|char|, |"|, |%c|, |4|

		-|char|, |fgets|, |stdin|


#4 Dunctions & Pointers


	Functions

		- next

		- next

		- next

		- |void|, |test|, |{|, |}|,

		- next

		- |login|, |{|, |()|

		Practice

		#include <stdio.h>
		int weight;
		
		//define the function here
		void baggage(int weight){
		
		if (weight <= 23){
		    printf("0");    
		}else{
		    weight=(weight-23)*12;
		    printf("%d",weight);
		}
		
		}
		
		int main() {
		scanf("%d",&weight);
		baggage(weight);
		return 0;
		}

		LESSON TAKEAWAYS

		Functions are reusable; we define them once and can call them multiple times.
		To call a function, use its name, followed by parentheses. 
		The void keyword means that the function does not return a value. 
		We will learn about return values in the next lessons, so stay tuned!

		NOTES

		A function is a block of code designed to perform a particular task.
		For example, your program can have functions like login(), draw(), convert(), calculate(), etc.

		The purpose of a function is to create it once and call it multiple times when needed to perform particular tasks.
		-
		We have seen some functions in the previous lessons, for example, the main() function, the printf() function, the scanf() function.
		You can define your own functions to perform your desired tasks. 
		Here is an example:

		void greeting() {
	 	 printf("Hello! \n");
	  	printf("I am an example function.");
		}

		The code above declares a function called "greeting", which outputs 2 lines of text.
		Note that the name of the function is followed by parentheses ().
		The statements of the function are inside curly braces {}.
		-
		Let's understand how the function is defined:

		void greeting() {
   		printf("Hello! \n");
   		printf("I am an example function.");
		}

		void means that this function does not have a return value. You will learn more about return values later in this module.
		greeting is the name of the function, and is followed by parentheses ().
		The body of the function is enclosed in curly brackets {}.
		-
		Now that we have our function defined, we can use it in our program by "calling" it.
		To call a function, type its name followed by a set of parentheses. 
		For example, let's call our greeting() function in main():

		#include <stdio.h>
		void greeting() {
   		printf("Hello! \n");
   		printf("I am an example function.");
		}
		int main() {
		greeting();
 		return 0;
		}
		-
		You can call a function multiple times. 

		#include <stdio.h>
		void greeting() {
	    printf("Hello! \n");
 	   	printf("I am an example function.");
		}
		int main() {
  		greeting();
  		greeting();
  		greeting();
   		return 0;
		}

		That is the purpose of functions, to declare them once, and use multiple times in our program.


	Function Parameters


	Returning From Functions

		- next

		- next

		- next

		- next

		- |float|

		- next

		- |int|, |if|, |return|, |b|

		Practice

		- #include <stdio.h>
		int weight;
		int total;
		int baggage(int weight) { 
		int total;
		if(weight <= 23) {
		total = 0;
		}
		else {
		total = (weight-23)*12;
		}
		return total;
		}
		int main() {
		scanf("%d", &weight);
		total = baggage(weight);
		printf("Total: $%d", total);
		return 0;
		}

		LESSON TAKEAWAYS

		Thats how you return values from functions!
		Here is a quick summary:
		
		Use the return keyword to return a value from your function.
		The function needs to have its return type specified before its name.
		The void type specifies that the function does not return any value.
		The returned value can be assigned to a variable when calling the function.
		In the next lesson, we will learn about another important concept in C - pointers!
		Thats how you return values from functions!
		
		Here is a quick summary:
		Use the return keyword to return a value from your function.
		The function needs to have its return type specified before its name.
		The void type specifies that the function does not return any value.
		The returned value can be assigned to a variable when calling the function.
		In the next lesson, we will learn about another important concept in C - pointers!

		NOTES

		The functions we have seen so far output their result.
		In some cases we do not need to output the result, but need to assign it to a 	variable to work with it in our program.
		In these cases, we need our function to return the result value, instead of 	outputting it. 
		-
		The Return Type
		Let's have a look at a function that takes two integer parameters and outputs their sum:

		#include <stdio.h>
		void sum(int x, int y) {
		    printf("%d", x+y);
		}
		int main() {
		    sum(12, 56);
		    return 0;
		}

		The void keyword in the definition specifies that the function does not return any value.
		-
		
		Let's change the function and specify the return type to be an int:
		
		int sum(int x, int y) {
		}
		
		This means that now our sum function will return an integer value.
		-
		Returning a Value
		Now, we can return our result using the return keyword:

		int sum(int x, int y) {
 		return (x+y);
		}

		The return keyword stops the function from executing. If there are any statements after return, they won't run.
		Let's see how to use the returned value.
		-
		What is the return type of the following function?

		float test(char a[], int b)

		reutn a float value
		-
		After we have created our function that returns a value, we can call it in our code and assign the result to a variable:

		#include <stdio.h>
		int sum(int x, int y) {
		return (x+y);
		}
		int main() {
		int res = sum(12, 56);
		printf("%d", res);
		return 0;
		}

		Returning is useful when you don't need to output the result of the function, but 
		need to use it in your code.
		For example, a getTotal() function in a shopping app can return the total amount of an order.
		-
		int max(int a, int b){
		if (a<b){
		return a;
		}else{
		return b;
		}
		}


	Pointers
	
		- next

		- next

		- |p|, |&|

		- next

		- next

		- |float*|, |&x|, |%f|, |*p|


		Practice

		- //


		LESSON TAKEAWAYS

		Remember the following:
		The & operator is used to access the memory location of a variable.
		The * operator is used to access the value of a memory address that is stored in a pointer.
		The same * sign is also used to declare a pointer, and it is different from the dereference operator.
		Let's learn where pointers are useful and how they are used in the code.
		

		NOTES
		In this lesson we will learn about pointers - an important concept in C used to efficiently access and manipulate computer memory.
		Each value we use in our program, including variables and arrays, are all stored in the computer memory. 
		-
		Every variable in the memory has its unique address.
		The address of a variable can be accessed using the & operator.
		For example, let's create a sample variable, assign it a value, then output its memory address:

		#include <stdio.h>
		int main() {
		int age = 24;
		printf("%p", &age);
		return 0;
		}

		terminal
		|0x7ffd4056a84c| 

		The code above will output the memory address of the variable, which is a hexadeciimal.
		Note, that the format specifier for hexadecimals is %p.
		-
		A pointer is a variable that stores the memory address of another variable as its value.
		It is defined using the asterisk sign and is defined just like a variable:

		#include <stdio.h>
		int main() {
		int age = 24;
		int* p = &age;
		printf("%p", p);
		return 0;
		}

		terminal
		|0x7ffe48f02604|

		p is a pointer to an int variable, thats why it is declared as int*, which reads as "a pointer to an int".
		p is assigned to the memory address of the age variable, so it holds that address as its value.
		-
		The asterisk * is also used to access the value stored at a memory address. It is called the dereference operator.
		Let's output the value stored at the address to which the pointer p points:

		#include <stdio.h>
		int main() {
		int age = 24;
		int* p = &age;
		printf("%d", *p);
		return 0;
		}

		terminal
		|24|

		Note, that we used %d as the format specifier, as we are outputting the integer value, stored at the address p.


	Using Pointers


		- next

		- next

		- next

		- |8|

		- next

		- next

		- |*(x+2)|

		- 

		Practice

		- RUN		//int result = (number*perc)/100;	


		LESSON TAKEAWAYS

		You did it! Remember:
		Pointers can be used as function parameters. This way the functioncan modify and set the values of multiple variables.
		The name of the array is actually a pointer to its first element.
		We can simply increment the pointer to an array to access its elements. if p is a pointer to the array,
		p+1 is the address of the second element, p+2 is the address of the third element, and so on.


		NOTES

		Let's learn how to use pointers and why they are useful.
		We have already seen a pointer in the scanf() function, when taking input:

		#include <stdio.h>
		int main() {
	 	int age;
	 	scanf("%d", &age);
	 	printf("%d", age);
	 	return 0;
		}

		The scanf() function takes a pointer as its parameter and replaces its value with the value that was used as input.
		-
		Another thing we can accomplish using pointer parameters is to return multiple values from a function.
		As you remember, the return keyword was used to return a value from the function, however it can only return a single value.
		In case of pointer parameters, we can use any number of pointers and set their values from the function.
		For example:

		void divide(int* x, int* y, int by) {
		*x /= by;
		*y /= by;
		}

		The function takes two pointers and another integers, then divides the two pointer values by the integer value.
		This way, two values are changed by the function.
		Note, that the function accesses the values of the pointers using the * operator.
		-
		Here is how we can use our divide() function:

		#include <stdio.h>
		void divide(int* x, int* y, int by) {
		*x /= by;
		*y /= by;
		}
		int main() {
		int x = 4200;
		int y = 670;
		divide(&x, &y, 10);  
		printf("%d %d", x, y);
		return 0;
		}

		terminal
		|420 67|	

		Note, that we pass the memory addresses of the variables to the function, as its parameters.
		The function changes the values of the variables using their pointers.
		This is how you can return multiple values from functions.
		-

		Another use-case of pointers are arrays.
		The name of an array is actually a pointer to its first element.
		For example:

		#include <stdio.h>
		int main() {
		int x[] = {1, 2, 3, 4};
		printf("%d", *x);
		return 0;
		}

		This will output the value of the first element of the array.
		-
		Array values are stored continuously in memory.
		Thus, each next element can be accessed by incrementing the pointer:

		#include <stdio.h>
		int main() {
		int x[] = {1, 2, 3, 4};
		int* p = x;
		for(int i=0;i<4;i++) {
		printf("%d \n", *p);
		p++;
		}
		return 0;
		}

		During each loop iteration, we increment the memory address of the pointer by 1, using p++.
		This sets the pointer to the next element of the array.
		This allows to easily access any array element.


	Module Quiz


#example


	Example(Remplace name to name lesson)


		- next

		- next

		- ||

		- 

		- 

		- 

		- 

		- 

		Practice

		- RUN		//int result = (number*perc)/100;	

		LESSON TAKEAWAYS

		The % remainder operator (also called the modulo)
		Let's find out how many of 100 items will be left

		NOTES
		int x = 8;
		int y = 4;
		printf("%d", x+y);

		The % remainder operator (also called the modulo)
		Let's find out how many of 100 items will be left