# IList

Maak voor deze toepassing een Interface ***ListModules*** en een klasse
***Modules*** waarin de eigenschappen van ListModules opgenomen zijn.

![Afbeelding met tekst, schermopname, nummer, Lettertype Automatisch
gegenereerde
beschrijving](./media/image1.png){width="3.3925207786526683in"
height="2.9650448381452317in"}

-   De interface ***Modules*** omschrijft de methode Add(), Indexof() en
    Remove().

-   Klasse ***ListModule*** omvat een List\<string\> dat door de
    methoden bewerkt kan worden.

    -   De methode *Add()* voegt de tekst uit TxtModule toe aan de
        List\<\> en aan de listbox LstModules.

    -   De methode *RemoveAt()* verwijdert de tekst uit de LstModules en
        uit de List\<\> dat opgegeven is in TxtModule.

    -   De methode *Remove()* roept RemoveAt() op om de tekst te
        verwijderen.

    -   De methode *IndexOf()* bepaalt de positie (zie berichtenvenster)
        van de module in de LstModules dat opgegeven is in TxtModule.

    -   De eigenschap *Inhoud* geeft de List\<\> terug.

***List***

![Afbeelding met tekst, software, Webpagina, Computerpictogram
Automatisch gegenereerde beschrijving](./media/image2.png){width="6.3in"
height="3.15in"}

-   *BtnToevoegen* maakt gebruik van ListModules.Add().

-   *BtnZoeken* gebruikt ListModules.IndexOf().

-   *BtnVerwijderen* gebruikt ListModules.Remove().

![Afbeelding met tekst, schermopname, Lettertype, nummer Automatisch
gegenereerde
beschrijving](./media/image3.png){width="3.9484678477690287in"
height="1.5835542432195975in"}

![Afbeelding met tekst, schermopname, Lettertype, nummer Automatisch
gegenereerde
beschrijving](./media/image4.png){width="2.333659230096238in"
height="1.5835542432195975in"}
