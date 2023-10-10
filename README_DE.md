# PB - Klassen - Grundlagen

In dieser Aufgabe geht es darum, die grundlegenden Konzepte von Klassen zu üben. Wir üben die Verwendung der Klasse `Date`, die in JavaScript eingebaut ist!

Füge deine Antworten direkt in diese Datei ein.

```js
    const now = new Date();
    const test = new Date();
```

1. Was ist die Variable `now` in dem obigen Code?
now ist eine Instanz der Klasse Date

2. Welchen Typ hat die Variable `now`?
Object und Date

3. Was ist in dem obigen Code die Variable `Date`?
Date ist der Constructor der Klasse Date

4. Was ist der Typ von `Date`?
Function

5. Was erhältst du, wenn du `console.log(now)` eingibst?
Umfangreiche Ausgabe für das aktuelle Datum  // => Tue Feb 14 2023 13:41:13 GMT+0100 (Mitteleuropäische Normalzeit)

6. Was erhältst du, wenn du `console.log(Date)` eingibst?
 Den namen des Konstruktors // => Date() { [native code] } 

7. Was erhältst du, wenn du `console.log(new Date())` eingibst?
Object

8. Ist `now` wahrheitsgemäß?
Ja

9. Was bekommst du, wenn du `console.log(now === test)` eingibst? Und warum?
false

10. Was bekommst du, wenn du `console.log(now === Date)` eingibst?
false

11. Was bekommst du, wenn du `console.log(now === new Date())` machst?
false

12. Was bekommst du, wenn du `console.log(new Date() === new Date())` machst? Und warum?
false