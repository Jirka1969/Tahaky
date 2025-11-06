# Taháky

Repozitář obsahuje soubor taháků k nejčastěji používaným příkazům v nástrojích **Git**, **Bash (terminál Linuxu)** a dalších.  
Cílem projektu je vytvořit přehledné a didakticky zpracované materiály, které pomohou při studiu základů verzovacích systémů a práce v příkazové řádce.

---

## 📘 Obsah

| Název souboru | Popis |
|---------------|--------|
| `tahakBashterminal.tex` / `.pdf` | Tahák s přehledem příkazů terminálu Bash |
| `tahakBashterminal_mensivarianta.tex` / `.pdf` | Zmenšená (kompaktní) verze taháku Bash |
| `tahakBashterminal_dalsi.tex` / `.pdf` | Rozšířený tahák k dalším příkazům Bash |
| `tahakBashterminal_posledniverze.tex` / `.pdf` | Finální verze taháku k Bashi |
| `Tahák základních příkazů Git (Bash).tex` / `.pdf` | Tahák základních příkazů systému Git |

---

## 🧰 Použité technologie

- **TeX / LaTeX** — sazba a strukturování dokumentů  
- **PDF** — finální formát výstupu  
- **Git & GitHub** — verzování a sdílení materiálů

---

## 🧩 Struktura projektu

```
Tahaky/
├── tahakBashterminal.tex
├── tahakBashterminal.pdf
├── tahakBashterminal_mensivarianta.tex
├── tahakBashterminal_mensivarianta.pdf
├── tahakBashterminal_dalsi.tex
├── tahakBashterminal_dalsi.pdf
├── tahakBashterminal_posledniverze.tex
├── tahakBashterminal_posledniverze.pdf
├── Tahák základních příkazů Git (Bash).tex
├── Tahák základních příkazů Git (Bash).pdf
└── ...
```

---

## 🚀 Kompilace LaTeX souborů

Každý `.tex` soubor lze přeložit do PDF pomocí příkazu:

```bash
pdflatex název_souboru.tex
```

Například:

```bash
pdflatex tahakBashterminal.tex
```

Případně lze použít modernější nástroje (např. **latexmk**):

```bash
latexmk -pdf tahakBashterminal.tex
```

---

## 🎯 Cíl projektu

- Vytvořit stručné, ale přehledné **učební pomůcky** pro studenty a začínající uživatele Gitu a Linuxového terminálu.  
- Usnadnit **opakování příkazů** při zkouškách nebo praktických cvičeních.  
- Umožnit snadnou **aktualizaci** a sdílení materiálů prostřednictvím verzovacího systému Git.

---

## 📄 Licence

Materiály jsou k dispozici pod licencí **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**.  
To znamená, že je můžete volně používat a upravovat pro nekomerční účely, pokud zachováte uvedení autora a ponecháte stejnou licenci.

Více informací: [https://creativecommons.org/licenses/by-nc-sa/4.0/](https://creativecommons.org/licenses/by-nc-sa/4.0/)

---

## ✍️ Autor

Projekt založil **Jirka1969**  
Námět: *vytváření taháků na software (Git, Bash, atd.)*  
Kontakt: *(volitelně doplnit e-mail nebo GitHub profil)*

---

## 🧠 Doporučení do budoucna

- Doplnit **Makefile** nebo **skript** pro automatickou kompilaci všech taháků.  
- Přidat **README** pro každý podtématický tahák (Git, Bash, atd.).  
- Zvážit přidání **verzí v angličtině** pro širší dostupnost.

---

