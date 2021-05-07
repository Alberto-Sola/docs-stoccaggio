---
description: Introduzione alle funzioni di Hash
---

# Funzioni di Hash

## Introduzione

Il termine **Hash** deriva dal verbo inglese _"to hash",_ che significa sminuzzare, casualizzare, disordinare...

## Cosa sono

Le funzioni di Hash servono per trasformare una stringa **qualsiasi** in una stringa composta da caratteri alfanumerici di dimensione **fissa**

![](.gitbook/assets/hash.png)

Le funzioni di hash sono funzioni _non invertibili,_ ossia funzioni **non** biunivoche \(partendo dal codice generato non è possibile tornare alla stringa originale\)

## Dettagli

> Dato un messaggio **M**; Data una funzione di Hash **h\(\)**;

`d = h(M)`

![](.gitbook/assets/hash_1.png)

{% hint style="success" %}
**d** rappresenta il **Digest**, ossia il risultato di una funzione di Hash
{% endhint %}

## Proprietà

* Resistenza alla preimmagine

  > è impossibile trovare una stringa che dia un hash uguale a un'altro _dato hash_

* Resistenza alla seconda preimmagine

  > è impossibile trovare una stringa che dia lo stesso hash di un'altra _data stringa_

* Resistenza alle collisioni

  > è impossibile trovare una coppia di stringhe che diano lo stesso risultato hash

