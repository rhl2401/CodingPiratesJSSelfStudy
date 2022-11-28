# Opgave 2 - palindromtjekker
Et palindrom er et ord eller en sætning, der staves ens både forfra og bagfra. Et eksempel kan være `Skal Eva have laks`. 

## Opgavebeskrivelse
Lav en funktion, der returnerer `true` eller `false` alt efter om det ord, der gives er et palindrom eller ej. 

Skriv derefter et par eksempler i consollen eller på siden, der viser, at det virker. 

```js
function isPalindrome(word) {
    // Skriv kode her

    // Hvis ordet er palindrom
    return true;

    // Hvis ordet ikke er palindrom
    return false;
}

console.log("Er sætningen 'skal eva have laks' et palindrom?", isPalindrome('skal eva have laks'));
```

Vær opmærksom på, at du skal fjerne mellemrum, da det er irrelevant, hvor mellemrummene er placeret, samt gøre alle bogstaver små. Du skal altså tjekke, om tjekke om `skalevahavelaks` kan staves "omvendt". 