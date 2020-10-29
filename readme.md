# Hópverkefni 1
---
## 1. Upplýsingar um verkefnið
### Hægt er að keyra tvær skipanir með npm
* npm run dev
> Keyrir browser-sync og node-sass samtímis og uppfærir browserinn á meðan það er verið að forrita
* npm run lint
> Athugar hvort að kóðinn sé ekki að fylgja stylelint reglum. Lætur vita hverjar þær eru ef einhverjar finnast.
### Skrám hefur verið raðað skipulega niður
* **Styles** mappan inniheldur allar skrár sem hafa að gera með útlit síðunnar. Þær eru
  - Global - Stílar sem eiga við allt
  - Grid - Skýr beinagrind fyrir staðsetningar
  - Header - Allir stílar sem hafa að gera með hausinn
  - Footer - Allir stílar sem hafa að gera með fótinn
  - Config - Geymir allar breytur fyrir stíl
  - Recipes - Stílar sem tengjast uppskriftunum
  - Book - Stílar sem tengjast bókinni
  - Buttons - Stílar fyrir alla takka
  - Videos - Stílar fyrir video síðuna
  - Grid-overlay - Hugað fyrir viðhald á síðunni
* **IMG** mappan inniheldur allar myndir sem tengjast síðunni
* **HTML** skrárnar eru 4 talsins (Ekki í möppu)
  - Index - forsíðan
  - Latest recipes - yfirlit yfir allar nýlegar uppskriftir
  - Recipes - uppskrift tiltekinnar máltíðar
  - Video - vídeo uppskrift fyrir tiltekna máltíð
* **Styles.scss** skráin tekur síðan allar skrár úr styles möppunni og sameinar þær í nýtt skjal, **Styles.css**
  sem síðan er notað af öllum HTML síðunum
## 2. Upplýsingar um höfunda
| Nöfn                        | Netföng       | GitHub Notendanöfn |
| ----------------------------|:-------------:| ------------------:|
| Karl Andersson Claesson     | kac12@hi.is   | KarlAClaesson |
| Kristján Leó Guðmundsson    | klg12@hi.is   | KristjanLeo   |
| Sigurjón Þorri Þórmundarson | stt27@hi.is   | ThorriThorskur|
| Valdimar Örn Sverrirson     | vos9@hi.is    | Valdi9hi      |
