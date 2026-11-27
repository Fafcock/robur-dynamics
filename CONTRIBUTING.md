# Spolupráce na ROBUR Dynamics

## Od úkolu k pull requestu

1. Založ nebo převezmi GitHub issue, případně se s kolegou domluv v chatu. Ujasněte si, kdo na úkolu pracuje, co se mění a podle čeho poznáte, že je hotovo. Při souběžné práci si řekněte, které soubory budete oba upravovat.
2. Začni z aktuálního `main`. V GitHub Desktopu přepni na `main`, stáhni nové změny a vytvoř větev pro svůj úkol. Používej krátké popisné názvy, například `docs/development-foundation`, `feat/nazev-ukolu` nebo `fix/nazev-opravy`.
3. Uprav jen to, co patří k úkolu. Před commitem zkontroluj seznam změněných souborů a jejich obsah. Lokální nastavení a přihlašovací údaje z commitu vynech.
4. Publikuj větev a otevři pull request do `main`. Popiš důvod změny, co se upravilo a jak jsi výsledek ověřil. Přidej odkaz na issue, pokud existuje, a uveď nevyřešené otázky. Rozpracovanou změnu můžeš zpřístupnit jako draft PR.
5. Požádej druhého člena týmu o kontrolu. Pokud vznikl konflikt, aktualizuj svou větev z `main` a domluv s autorem souběžné změny, jak zachovat práci obou. Po vyřešení připomínek a schválení PR změnu slučte do `main`. Oba si pak stáhněte aktuální `main`.

Do `main` patří změny přes zkontrolované PR. Rozhodnutí, která mění herní směr, kánon nebo technický základ, po společné dohodě zapište do [decision logu](docs/DECISIONS.md) a ve stejném PR upravte související dokumenty.

## Co má obsahovat popis PR

- Účel a rozsah změny.
- Postup ověření a výsledek.
- Související issue nebo rozhodnutí, pokud existuje.
- Otevřený bod pro kontrolu, pokud nějaký zbývá.
