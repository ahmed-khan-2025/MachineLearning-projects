# MachineLearning-projects
# Fake or Real News
Syftet med detta projekt är att undersöka möjligheterna att automatiskt klassificera nyhetsartiklar som antingen sanna eller falska med hjälp av maskininlärning.
## Problemformulering
•	Typ av problem: Binär klassificering (etiketterna är fake eller real)  
•	Mål: Identifiera mönster i textdata som skiljer falska nyheter från riktiga  
•	Input: rubrik  
•	Output: Klassificering (Fake eller Real)
## Dataundersökning
Valt dataset:  
fake-or-real-news.csv Dataset från Kaggle  
(Källa: https://www.kaggle.com/datasets/jillanisofttech/fake-or-real-news)  
Beskrivning av datasetet:
•	Totalt antal rader: 6335  
•	NaN-Värden : 0  
•   Kolumner:  
         title: Rubriken på artikeln  
         text: Fullständig nyhetstext  
         label: FAKE eller REAL    

Eller dataset:    
WELFake_Dataset.csv Dataset från Kaggle  
(Källa: https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification)  
Beskrivning av datasetet:  
•	Totalt antal rader: 72134   
•	Nan-Värden : 597  
•	Kolumner:  
         title: Rubriken på artikeln  
         text: Fullständig nyhetstext  
         label: 0 = FAKE eller 1= REAL  
# Diabetes
## Problemformulering
Syftet med detta projekt är att analysera patientdata och undersöka möjligheten att förutsäga risken för typ 2-diabetes. Målet är att skapa en grund för en modell som, baserat på demografiska och medicinska variabler, kan uppskatta risken för att en individ utvecklar sjukdomen.
## Val av dataset
Efter att ha undersökt tillgängliga öppna datakällor har jag valt att utgå från PIMA Indians Diabetes Dataset, som är allmänt använt inom medicinsk maskininlärning och finns tillgänglig via exempelvis UCI Machine Learning Repository och Kaggle.  
diabetes.csv Dataset från Kaggle  
(Källa: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)  
Datasetinformation:  
•	Antal rader (datapunkter): 768  
•	Antal kolumner (attribut): 9  
•	Målvariabel: Outcome (1 = diabetes, 0 = ingen diabetes)
