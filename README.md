# Dynamisk web - data som objekter

Vi har tidligere arbejdet med forskellige datatyper, såsom string, number, boolean og arrays.
Arrays er "smarte" fordi de kan indeholde serier af data.

En datatype vi netop ikke har arbejdet så meget med er objekter. Objekter er gode til at definere lidt mere komplekse datastrukturer

Forestil dig, at vi for eksempel har noget data om en person. Der relaterer sig mange detaljer til personer. Det kan fx være deres for- og efternavn, deres alder, hvor de bor, hvilket husdyr de har, og hvad deres husdyr hedder. 

Et objekt som indeholder de data kunne for eksempel se sådan ud:
```js
let person = {
  firstname: "Ole",
  lastname: "Erling",
  age: 54, 
  hometown: "Roskilde", 
  pet: "Klapperslange", 
  petname: "Holger"
}
```
Ovenfor defineres en variabel "person" som indeholder et objekt. 

Et objekt defineres ved at omkranse de data som objektet indeholder med krølleparenteser. Inde i objektet defineres en række data. Data består af to halvdele, lidt lige som css. En egenskab og en værdi. Når man refererer til data i objektet gøres det ved at referere til objekt navnet og herefter den egenskab (property) man gerne vil have udskrevet. Værdien for den pågældnde egenskab returneres. Denne måde refereres ofte  til som "dot notation". 

```js
console.log(person.firstname) // Ole
console.log(person.lastname) // Erling
```

### Men  krølleparenteser bruges da til...
Ja, krølleparenteser bruges til forskellige ting, afhængig af hvor du er i din kode. Derfor er det er måske ikke den bedst tænkelige syntaks. Du lærer dog ret hurtigt at skelne imellem de måder krølleparenteserne bruges, og dermed til at spotte, om der er tale om en funktion, et objekt eller noget helt tredje.

### En anden måde
Du kan også referere til egenskaber i objekter med firkantparanteser `[]`. Hvis du vil bruge denne metode, skal du først skrive objekt-navnet og derefter navnet på den egenskab du vil referere til, som en string i firkant-paranteser. Denne måde kaldes for "bracket notation", og kunne for eksempel se sådan ud: 

```js
console.log(person["pet"]) // Klapperslange
console.log(person["petname"]) // Holger
```


## Opgave 1 
Opret et objekt som indeholder mindst fire forskellige egenskaber. Udskriv de fire egenskaber i konsollen en ad gangen. Brug begge syntakser til at udskrive egenskaberne med, så du får prøvet både "dot notation" og 


