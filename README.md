# Git-uppgift

Individuell examination i Git och GitHub av Emil Uzeirovic.

## Fråga 1: Versionshantering vs vanliga filer

### G
Vad är versionshantering och vad är skillnaden mellan att spara med sparaknappen och att spara i Git?

Versionshantering är att man sparar alla versioner av ett projekt så man kan se vilka ändringar som gjorts. Det är också bra om man samarbetar med andra eftersom alla kan se vad som ändrats. Om man bara sparar med Ctrl+S i VS Code så skrivs filen över och det som stod innan försvinner helt. Men om man sparar i Git med en commit så finns de gamla versionerna kvar och man kan se exakt vad man ändrade.

### VG
Vad betyder det att Git sparar frysta ögonblicksbilder? Vad bevisar det att första commiten fortfarande har kvar alla TODO?

Varje commit är som ett foto av projektet. Fotot ändras aldrig, och när man gör en ny commit blir det ett nytt foto. I min första commit på GitHub finns alla TODO kvar fast de är borta i filen på min dator nu. Det visar att Git sparar alla gamla versioner, så man kan gå tillbaka om något går fel.

## Fråga 2: Arbetsytan, Staging och Commits

### G
Vad gör git status, git add och git commit, och när kör man dem?

git status visar vilka filer som är ändrade och om de är med till nästa commit eller inte. git add lägger till filen så att den blir med i nästa commit. git commit sparar ändringarna som en ny version, och den gamla finns kvar. Jag kör dem i ordningen status, add och commit varje gång jag har ändrat något, och sen push för att ladda upp till GitHub.

### VG
Hur hänger arket, kuvertet och arkivlådan ihop? Varför får man "no changes added to commit" om man hoppar över git add?

Arket är filen jag ändrar i, kuvertet är det jag har lagt till med git add, och arkivlådan är det som sparas med git commit. Man skriver på arket, lägger det i kuvertet och sen hamnar det i arkivlådan. Om man ändrar filen men glömmer git add så är kuvertet tomt. Då har git commit inget att spara, och därför säger Git no changes added to commit.

## Fråga 3: Lådan hemma vs Montern på GitHub

### G
Vad är skillnaden mellan mappen på datorn och repot på GitHub, och vad gör git push?

Mappen på min dator och repot på GitHub är två olika ställen. GitHub är som en kopia av projektet som finns kvar om något skulle hända med min dator. Det uppdateras inte automatiskt när jag ändrar något, utan jag måste köra git add, göra en commit och sen git push. git push skickar mina commits från datorn till GitHub.

### VG
Vad är de två rummen? Varför säger git push "Everything up-to-date" om man glömt add och commit?

Lådan hemma är min dator och montern är GitHub. Det är två olika ställen, och det som finns i lådan hemma syns inte i montern förrän jag pushar. git push skickar bara commits, inte filer. Om jag ändrar i koden men glömmer git add och git commit så finns det inget nytt att skicka. GitHub har redan alla mina commits, och därför svarar Git Everything up-to-date fast filen är ändrad.  