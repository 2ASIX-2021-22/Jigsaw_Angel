---
title: Navigation
description: Building a navigation menu for your site
extends: _layouts.documentation
section: content
---

# Jocs del penjat {#navigation}


![enter image description here](https://github.com/angelguerrero-glitch/images_markdown/blob/main/images/0.png)

La idea era primer crear el mític joc del **penjat** amb diversos tipus de categories com per exemple marques, deports, etc. Com no va funciona vaig continuar amb una sola categoria anomenada **marques**. Les bases del joc són fàcils.

El joc inicia de la manera següent imprimeix un arrays de guions concatenats amb un espai de la següent manera:

![enter image description here](https://github.com/angelguerrero-glitch/images_markdown/blob/main/images/1.png)

Seguidament, et demana una lletra, si l'encertes veuràs el següent per pantalla:

![enter image description here](https://github.com/angelguerrero-glitch/images_markdown/blob/main/images/2.png)

I si la falles veuràs que no fa res, però et conta com un intent ja els intents son igual a la llarga de la paraula si són 5 lletres 5 tryes:

![enter image description here](https://github.com/angelguerrero-glitch/images_markdown/blob/main/images/3.png)

Si encertes et donarà un missatge dient **Felicitats has donat amb la paraula**:

![enter image description here](https://github.com/angelguerrero-glitch/images_markdown/blob/main/images/4.png)

Si falles sortirà que un missatge dient **Bon intent prova sort la proxima vegada**

![enter image description here](https://github.com/angelguerrero-glitch/images_markdown/blob/main/images/5.png)


## Problemes i Errors

El primer problema que vaig tindre va ser el moment crear les categories, ja que havia trobat exemples de com fer-ho amb un arrays però ho volia fer amb varis arrays perquè l'usuari seleccioni l'amb el que vol jugar. Vaig provar/pensar de fer-ho de vàries maneres però al moment d'agafar una categoria no em sortia la manera de què tries un array. Tambe vaig pensar en guardar les arrays dins d'una altra array com estiguin totes però no ho vaig aconseguir. Tambe vaig intentar-ho d'una altra manera de què ho  tries per ramdom. La última que sem va acudir és fer un switch amb vàries opcions i dins de cada opció que tingui l'array i al moment de seleccionar-ho que fes un array de còpia fora llavors al moment de seleccionar que aquesta array sigui igual l'array de còpia. *Solucionat amb el switch que he comentat

El següent no es un problema però es una millora vaig fer, el mètode de seprarlletres per poder tindre un mètode que al moment de passar un array i em trie una paraula me la separi exemple **hola h o l a**.

El següent que volia fer era i vaig tindre problemes era que volia tindre un variable estatica de *trys* on aquesta sigui sempre el total d'intents que de lletres d'una paraula. Com no ho faig poder solucionar el que vaig fer és deixar-la com una variable més, però amb la longitud de l'array que *lletraSeparada* que gràcies al mètode *separaParaula* em dona la llargada de la paraula, això i el número d'intents que va sumant cada vegada que fa un em van servir per poder fer la sortida i l'entrada al switch.

Un altre que faig tindre va ser al moment de crear el jar en donava el seguent error.
Vaig fer varios intents de solcionar com moficar el manifest que estroba dins del jar, pero res no va funcionar.


![enter image description here](https://github.com/angelguerrero-glitch/images_markdown/blob/main/images/6.png)

*Solucionat amb el main-class

![enter image description here](https://github.com/angelguerrero-glitch/images_markdown/blob/main/images/8.png)

Al fer els últims retocs al moment de no trobar la lletra no consegeixo que el else em funcione be.

![enter image description here](https://github.com/angelguerrero-glitch/images_markdown/blob/main/images/7.png)

## Intent de cear dibuix

Esta es un part extra que no afecta al codi pero vaig intentar fer un dibuix a partir de una matriu aixi cada cop que la encerti es pleni amb el tipic dibuix del penjat 