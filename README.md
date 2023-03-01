# anaguriaac-

![Calendário 2023 ilustrado aquarela ](https://user-images.githubusercontent.com/105393642/221899803-8526fa22-6ccc-402b-aee6-eb66ff7b7359.jpg)
<div aling-"center">
img src="https://https://user-images.githubusercontent.com/105393642/221899803-8526fa22-6ccc-402b-aee6-eb66ff7b7359.jpg" width="300px" />
</div>

<h1>Código em c# Agenda </h1>
<h3>Status:Developing ⚠️ ⚠️ ⚠️</h3>
 
<h2>It is the developement of an agenda.</h2>😊

## Some Fields in Main Model is 


### Call Variables
* string título;
* string descrição;
* string data;
* string horai;
* string horaf;
* string prioridade;

<h> Propriedade </h2>

* This agende captures the user's main tasks throughout the week
* Like title, job description, date, start and end job hours and what is
  the priority of the job example: High,Medium,Low.📅📅

* This project was created in mobile app. The app name is C#.📱
* However, this project needs to be implemented whit data base .🗃️

I used sytem library to open the code
giving me useful classes like Console and WriteLine.
I also used variables of type string in all commands.

String type: used to store characters and a string must be enclosed in quotes.

Console.WriteLine write the text representation of the especified objetcs. 
(When you want to write something that is seen on the screen. Eg: Hello World)

Console.ReadLine return the value of the entire row.
(when you whant to interact whit the user and he must repond to the 
commands he sees on the screen. For exemple : Enter a number)


⬇️⬇️⬇️ Below you will find the code of the project in progress.⬇️⬇️⬇️


 using System;

public class Test
{
	public static void Main()
	{
		 string título;
		 string descrição;
		 string data;
		 string horai;
		 string horaf;
		 string prioridade;
		
		Console.WriteLine("Bem Vindo Usuário");
		
		Console.WriteLine("título");
		
		Console.WriteLine("descrição");
		Console.WriteLine("data");
		Console.WriteLine("horai");
		Console.WriteLine("horaf");
		Console.WriteLine("prioridade");
		
		
		título = Console.ReadLine ();
		Console.WriteLine("Escreva o Título da Tarefa;" );
		
		descrição = Console.ReadLine();
		Console.WriteLine("Descrição da Tarefa:" );
		
		 data = Console.ReadLine();
		Console.WriteLine("Digite a data:" );
		
		 horai =Console.ReadLine();
		Console.WriteLine("Hora Inicial da Tarefa:" );
		
		horaf =Console.ReadLine ();
		Console.WriteLine("Horario Final da Tarefa:" );
		
		 prioridade= Console.ReadLine();
		Console.WriteLine ("Prioridade Alta, Média ,Baixa:"  );
	}
}
