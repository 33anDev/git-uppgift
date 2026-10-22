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

### VG
Hur hänger arket, kuvertet och arkivlådan ihop? Varför får man "no changes added to commit" om man hoppar över git add?

## Fråga 3: Lådan hemma vs Montern på GitHub

### G
Vad är skillnaden mellan mappen på datorn och repot på GitHub, och vad gör git push?

### VG
Vad är de två rummen? Varför säger git push "Everything up-to-date" om man glömt add och commit?