# 🗂️ Persoonlijke Mappenstructuur Generator

Deze tool creëert automatisch een overzichtelijke en configureerbare mappenstructuur voor **persoonlijke administratie**. Het helpt je om digitale documenten georganiseerd te bewaren, gericht op particulieren. De structuur wordt gedefinieerd in een `map_structuur.txt` bestand, waardoor je deze eenvoudig kunt aanpassen aan je eigen behoeften.

![Demonstratie Persoonlijke Mappen Generator](https://github.com/RemseyMailjard/PersoonlijkeMappenGenerator/raw/main/PersoonlijkeMappenStructuurGenerator.gif)


**In deze repository vind je:**
*   Een direct bruikbare **.EXE versie** (aanbevolen voor de meeste gebruikers).
*   De originele **.BAT script versie** voor degenen die de code willen inzien of aanpassen.

## 📁 Wat doet deze tool?

*   Vraagt naar een **hoofdlocatie** (standaard `Desktop\Persoonlijke Administratie`) en een **doeljaar**.
*   Detecteert of `map_structuur.txt` aanwezig is:
    *   **Indien aanwezig:** Leest de mappenstructuur uit dit bestand. Placeholders zoals `!TARGET_YEAR!` en `!PREVIOUS_YEAR!` worden vervangen.
    *   **Indien niet aanwezig:** Gebruikt een standaard, uitgebreide ingebouwde mappenstructuur (gedefinieerd in het script/de .exe zelf).
*   Creëert de gekozen mappenstructuur.
*   Genereert een uitgebreide set aan thematische mappen, bijvoorbeeld voor:
    *   Financiën
    *   Belastingen
    *   Verzekeringen
    *   Woning
    *   Gezondheid
    *   ...en vele andere categorieën.
*   Ondersteunt submappen met jaartallen voor eenvoudig archiveren.
*   Bevat een logbestand voor het traceren van de uitgevoerde acties.

## ▶️ Gebruik (.EXE Versie - Aanbevolen)

1.  Download `PersoonlijkeMappenGenerator.exe` uit de [Releases sectie](https://github.com/GEBRUIKERSNAAM/PersoonlijkeMappenGenerator/releases) (of de hoofdmap van deze repository).
2.  Dubbelklik op `PersoonlijkeMappenGenerator.exe`.
3.  Volg de instructies op het scherm om de locatie en het jaartal te kiezen. De standaard ingebouwde structuur wordt nu gebruikt.

**Optioneel: Eigen structuur gebruiken:**
1.  Download (of maak) ook een `map_structuur.txt` bestand. Een voorbeeldbestand (`map_structuur_voorbeeld.txt`) is beschikbaar in deze repository.
2.  Hernoem het voorbeeldbestand of maak je eigen bestand en noem het `map_structuur.txt`.
3.  **Plaats `PersoonlijkeMappenGenerator.exe` en `map_structuur.txt` in dezelfde map.**
4.  Start `PersoonlijkeMappenGenerator.exe`. De tool zal nu automatisch `map_structuur.txt` gebruiken.

> ℹ️ De .EXE is gemaakt voor Windows en vereist geen installatie.

## 🔧 Structuur Aanpassen (`map_structuur.txt`)

Je kunt de mappenstructuur volledig naar wens aanpassen door het `map_structuur.txt` bestand te bewerken:
*   Elke regel definieert een map (relatief aan de hoofdmap).
*   Gebruik `/` als padscheidingsteken.
*   Gebruik `!TARGET_YEAR!` voor het gekozen jaartal en `!PREVIOUS_YEAR!` voor het jaar daarvoor.
*   Regels beginnend met `#` of `rem`, en lege regels, worden genegeerd.

## 🧑‍💻 Gebruik (.BAT Script Versie - Voor gevorderden)

1.  Download `PersoonlijkeMappenStructuurGenerator.bat` (en eventueel `map_structuur_voorbeeld.txt` als basis).
2.  Indien je een eigen structuur wilt: maak/bewerk `map_structuur.txt`.
3.  **Plaats het `.bat` bestand (en `map_structuur.txt` indien gebruikt) in dezelfde map.**
4.  Dubbelklik op het `.bat` bestand of voer het uit via de command prompt.
5.  Volg de instructies.

## ✨ Geavanceerde Bestandsorganisatie met AI

Als je op zoek bent naar een nog krachtigere manier om niet alleen mappenstructuren aan te maken, maar ook je bestaande bestanden **automatisch te laten sorteren en hernoemen met behulp van Kunstmatige Intelligentie**, bekijk dan mijn andere project: **AI File Organizer**.

De **AI File Organizer** is een Windows-applicatie die:
*   Bestandsinhoud analyseert (PDF, DOCX, TXT, MD).
*   Bestanden automatisch classificeert en verplaatst naar relevante categorieën.
*   AI-gegenereerde suggesties doet voor submappen en bestandsnamen.
*   Ondersteuning biedt voor AI-providers zoals Google Gemini, OpenAI en Azure OpenAI.

Dit biedt een geavanceerde oplossing voor het daadwerkelijk organiseren van de *inhoud* van je digitale documenten.

➡️ **Bekijk de [AI File Organizer op GitHub](https://github.com/RemseyMailjard/AI-FileOrganizer2/tree/nieuwStructuur)**
➡️ **Download de nieuwste versie direct: [AIFileOrganizerLinkedIn.zip](https://github.com/RemseyMailjard/AI-FileOrganizer2/raw/nieuwStructuur/AIFileOrganizerLinkedIn.zip)**
*(Let op: de `.zip` link downloadt direct het bestand van de `nieuwStructuur` branch).*

## 📷 Screenshot (Voorbeeld van de standaardstructuur)

> Voeg hier een afbeelding toe van (een deel van) de aangemaakte mappenstructuur voor visuele duidelijkheid. Als je de .GIF in de repo hebt, kun je die hier direct linken:
> `![Voorbeeld Mappenstructuur](PersoonlijkeMappenStructuurGenerator.gif)`

## 📌 Voor wie is dit bedoeld?

*   Iedereen die zijn/haar digitale documenten en administratie overzichtelijk wil organiseren.
*   Personen die een startpunt zoeken voor een goede mappenopzet voor thuisadministratie.
*   Trainers en coaches die digitale vaardigheden aanleren en een praktisch voorbeeld willen geven.

## 💡 Tips

*   Pas `map_structuur.txt` aan om de structuur perfect op jouw situatie af te stemmen.
*   Bewaar de tool en `map_structuur.txt` op een handige plek voor jaarlijks gebruik.

## 📜 Licentie

Dit project is beschikbaar onder de [MIT License](LICENSE). *(Zorg ervoor dat je een LICENSE bestand toevoegt aan je repository).*

## ✍️ Auteur

*   **Remsey Mailjard**
    *   IT-trainer | Power Platform ontwikkelaar
    *   [remsey.nl](https://remsey.nl) • [LinkedIn](https://nl.linkedin.com/in/remseymailjard) • [GitHub](https://github.com/RemseyMailjard)