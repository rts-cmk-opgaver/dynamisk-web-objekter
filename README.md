# Dynamisk web - data som objekter

Vi har tidligere arbejdet med forskellige datatyper, såsom string, number, boolean og arrays.
Arrays er "smarte" fordi de kan indeholde serier af data.

En datatype vi netop ikke har arbejdet så meget med er objekter. Objekter er gode til at definere lidt mere komplekse datastrukturer

Forestil dig, at vi for eksempel har noget data om en person. Der relaterer sig mange detaljer til personer. Det kan fx være deres for- og efternavn, deres alder, hvor de bor, hvilket husdyr de har, og hvad deres husdyr hedder. 

Et objekt som indeholder de data kunne for eksempel se sådan ud:
```js
var person = {
  firstname: "Ole",
  lastname: "Erling",
  age: 54, 
  hometown: "Roskilde", 
  pet: "Rattlesnake", 
  petname: "Holger"
}
```
Ovenfor defineres en variabel "person" som indeholder et objekt. 

Et objekt defineres ved at omkranse de data som objektet indeholder med krølleparenteser. Inde i objektet defineres en række data. Data består af to halvdele, lidt lige som css. En egenskab og en værdi. Når man refererer til data i objektet gøres det ved at referere til objekt navnet og herefter den egenskab (property) man gerne vil have udskrevet. Værdien for den pågældnde egenskab returneres.

```js
console.log(person.firstname) // Ole
console.log(person.lastname) // Erling
```

### Men  krølleparenteser bruges da til...
Ja, krølleparenteser bruges til forskellige ting, afhængig af hvor du er i din kode. Derfor er det er måske ikke den bedst tænkelige syntaks. Du lærer dog ret hurtigt at skelne imellem de måder krølleparenteserne bruges, og dermed til at spotte, om der er tale om en funktion, et objekt eller noget helt tredje.

## Opgave 1 
Opret et objekt 
