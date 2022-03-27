# Delictes contra l'ordenació del territori
Aquesta web tracta de mostrar els delictes contra l'ordenació del territori a Catalunya per a l'any 2021.

---
## Tema i motivació
Els **delictes contra l'ordenació del territori** a Catalunya poden resutar una bona font per conéixer el funcionament legislatiu de les normes d'ordenació al territori català.

El que m'ha motivat a triar aquesta temàtica és la meva orientació cap al camp de l'ordenació i planificació territorial, en combinació amb els SIG. També és un qüestió de curiositat de quines són les normatives que més conflicte generen amb la població.

En aquest cas podrem saber en quina Regió Policial *(límit administratiu format per comarques)* és generen més delictes, quin és el més freqüent, d'entre d'altres comparatives.

![Mapa de Regions policials de Catalunya](/images/mapa_regions_policials.jpg)


---
## Dades i continguts
Les dades de delictes han estat descarregades a partir de la web de la [Generalitat de Catalunya](https://mossos.gencat.cat/ca/els_mossos_desquadra/indicadors_i_qualitat/dades_obertes/cataleg_dades_obertes/dades-delinqueencials/).

> Els Mossos d'Esquadra ➡️ Indicadors i qualitat ➡️ Dades obertes ➡️ Catàleg ➡️ Dades delinqüencials

Posteriorment aquestes dades han estat filtrades per la tipologia de delicte, on únicament es treballen els relacionats amb l'ordenació del territori.


---
## Estructura de la web
L'estrucutura de la web serà molt simple, i ve donada principalment pel tipus de catografia que es veurà representada.

![Estructura de la informació dels mapes](/images/map-diagram.jpg)


---
## Cartografia amb el pluguin QGIS2WEB
El pluguin QGIS2WEB ha estat deenvolupat per [Tom Chadwin](https://github.com/tomchadwin), qui també és usuari de Github on soluciona dubtes als usuaris del pluguin.

Un aspecte a considerar és que el mapa de fons no carrega amb el navegador de Google Chrome, però sí amb Safari. Parlaré en un futur del tema si és que ho puc solucionar.


---
## Dificultats i millores
Com a dificultats he identificat treballar mitjançant el pluguin qgis2web ja que, mostra algunes incompatibilitats amb la simbologia i l'etiquetatge que realitzem amb el QGIS. Veieu [Issue 772.](https://github.com/tomchadwin/qgis2web/issues/772)

Molts d'aquests problemes es podrien solventar coneixent més del SIG, tot i que no és l'objectiu a assolir en aquesta assignatura, pel que la cartografia seria un aspecte a millorar i pulir.

Un altra problemàtica ha estat treballar mitjançant un software iOS, el que en aquest aspecte en concret no tenia altre opció que solucionar els problemes i treballar en paral·el al professor. Derivat del meu sistema operatiu m'ha estat impossible treballar amb geopackage mitjançant QGIS, pel que he optat per treballar de forma "*normal*" amb arxius *.shp* i els seus derivats.

Tot i així, he pogut desenvolupar la meva feina de forma *correcta*.


## Aspectes perifèrics
La llicència escollida ha estat ***General Public License 3.0***. És una llicència de dret d'autor àmpliament usada en el món del programari lliure i codi obert, i garanteix als usuaris finals (persones, organitzacions, companyies) la llibertat d'usar, estudiar, compartir (copiar) i modificar el programari. 

El seu propòsit és doble: 

- Declarar que el programari cobert per aquesta llicència és lliure.
- Protegir-ho (mitjançant una pràctica coneguda com a copyleft) d'intents d'apropiació que restringeixin aquestes llibertats a nous usuaris cada vegada que l'obra és distribuïda, modificada o ampliada.


