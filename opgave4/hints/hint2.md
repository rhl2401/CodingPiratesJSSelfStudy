# Hint 2 - Split

Du kan lave en liste med hvert bogstav i sætningen ved at bruge fuktionen `.split()` på din string. 

Du kan i funktionen definere, hvad der skal splittes ved. Man kunne fx splitte på alle punktummer i en string, men i vores tilfælde er det bare for hvert enkelt bogstav. Derfor giver vi den bare en tom `''` string - det er **VIGTIGT** at der ikke er mellemrum. 

```js
const string = "hejmeddig"; 
const liste = string.split('');

// liste = ['h', 'e', 'j', 'm', 'e', 'd', 'd', 'i', 'g'];
```