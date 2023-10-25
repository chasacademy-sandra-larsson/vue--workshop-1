
# Vue #1: Intro till Vue 
👋 Se föreläsningen i onsdags ✅ 

**Syftet med denna workshop:** Öva på grunderna i Vue med CDN. Workshopen går igenom template syntax, olika direktiv som v-if, v-else-if, v-else, v-for, v-bind samt hur data property, methods, computed properties samt watchers.

Använd dig av orginaldokumentationen [https://vuejs.org/](https://vuejs.org/). Du hittar även bra pedagogiskt material på Vue Mastery [https://www.vuemastery.com/](https://www.vuemastery.com/)

Bra lathund från Vue Mastery [https://www.vuemastery.com/vue-cheat-sheet/](https://www.vuemastery.com/vue-cheat-sheet/)

# CDN

Vi börjar utan build-tools för att få en clean intro :-). Vi hämtar Vue 3 från denna CD:

```
<script src="https://unpkg.com/vue@3.0.0/dist/vue.global.js"></script>

```
# 👩🏽‍💻 Övning 1: Enkel todo-list (endast frontend)

Gör en enkel todo-list i Vue 3. Todo-listan ska kunna:

* Visa en lista över todos
* En input och en button för att lägga till en todo
* Varje todo ska ha en "Remove"-button, så att man kan ta bort en todo
* Input ska clearas efter att man lagt till en todo


# 👩🏽‍💻 Övning 2: Räntekalkylatorn


Det snackas mycket om räntorna nu förtiden, så jag tänkte att du ska göra en enkel räntekalkylator.

Användaren ska mata in huvudbeloppet, räntesatsen och tiden (i år). Kalkylatorn kommer sedan att visa den beräknade enkla räntan. Den beräknade enkla räntas baseras på formeln:

```(Belopp × Ränta × Tid (år) / 100 ```

När användaren ändrar något inmatningsvärde räknar den beräknade egenskapen automatiskt om, och den visade enkla räntan uppdateras i realtid.

Vad är enkel ränta (även kallad periodisk ränta? [https://www.ekonomifakta.se/Ordlista/Enkel-ranta/](https://www.ekonomifakta.se/Ordlista/Enkel-ranta/)

**Exempel:**
Anta att du har placerat 1000 kr på ett bankkonto som ger en årlig ränta på 5% och att denna ränta beräknas som enkel ränta. Efter ett år skulle du ha tjänat:

```Enkel ränta = 1000 x 0,05 x 1 = 50kr ```



# 🏃🏽‍♂️ Extrauppgift: SVG Bar Chart


Skapa en Bar Chart i SVG där höjden ändras beroende på användarens indata. Ungefär så här:

![Exempel på Bar Chart](https://github.com/chasacademy-sandra-larsson/vue--workshop-1/blob/main/svg_bar_chart.png)

Använd dig av watch för att bevaka en förändring från användarens input.


# ✅ Redovisning:
* Du redovisar minst uppgiften för övningen. 
* ***Om du inte kan delta på workshopen, redovisar du ovanstående nästkommande workshop***








