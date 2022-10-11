# Beispiel "Hallo Welt"

Das übliche "Hallo Welt!"-Beispiel sieht in C so aus:

	#include <stdio.h>

	int main() {
           printf("Hallo Welt!\n");
	   return 0;
	}

In der ersten Zeile werden Standard-Ein/Ausgabefunktionen importiert, danach folgt die Funktion "main" - es ist dies das Hauptprogramm, das beim Programmstart automatisch aufgerufen wird. Die Funktion hat als Rückgabewert ein int, also einen ganzzahligen Wert.

Die Funktion printf() gibt eine Zeichenkette aus, in diesem Fall "Hallo Welt!", und anschließend noch einen Zeilenumbruch, das "\n". 

Danach wird als Ergebnis der Funktion 0 zurückgegeben, das ist üblicherweise ein Zeichen dafür, dass alles funktioniert hat.

Und das war auch schon das erste Beispiel in C.

Compilieren kann man das Programm mit

	> gcc hello.c

Das fertige Programm wird dann in eine Datei "a.out" geschrieben. Möchte man einen anderen Namen haben, kann man den angeben:

 	> gcc -o hello hello.c 

