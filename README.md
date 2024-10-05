# Medarbejderafgangsforudsigelse og Klyngeanalyse

## Projektbeskrivelse
Dette projekt analyserer medarbejderafgang ved hjælp af både klassifikations- og klyngeanalysemetoder. Dataene er syntetiske medarbejderdata, som bruges til at forudsige afgang og segmentere medarbejdere i forskellige grupper baseret på deres karakteristika.

### 1. Supervised Machine Learning: Klassifikation
For klassifikation anvendes en **beslutningstræmodel** til at forudsige, om en medarbejder forlader sin stilling. Modellen er evalueret på præcision, recall, F1-score og nøjagtighed.

- **Accuracy**: 97%
- **Precision**: 
   - No: 98%
   - Yes: 93%
- **Recall**: 
   - No: 98%
   - Yes: 93%
- **F1-score**: 
   - No: 98%
   - Yes: 93%
- **Macro average**: 95% for precision, recall og F1-score
- **Weighted average**: 97% for precision, recall og F1-score

### 2. Unsupervised Machine Learning: Klyngeanalyse
Klyngeanalysen bruger **K-means** til at gruppere medarbejdere i 3 klynger baseret på variabler som alder, jobtilfredshed, månedsløn og afstand til arbejde. Klyngernes kvalitet evalueres ved hjælp af silhuetscore.

- **Silhuetscore**: 0.29

#### Visualisering af Klyngeanalyse
I K-means klyngeanalysen blev medarbejderne opdelt i tre klynger baseret på deres attributter. Visualiseringen nedenfor viser, hvordan medarbejderne er grupperet i disse tre klynger ved hjælp af Principal Component Analysis (PCA), som reducerer dimensionerne af dataene for at kunne vise dem på en 2D-graf.

![image](https://github.com/user-attachments/assets/22c5832a-e805-46ac-b34f-58e05b685bd5)


- **Farver** repræsenterer forskellige klynger, hvor hver farve viser en unik gruppe af medarbejdere med lignende karakteristika.
- **X- og Y-akserne** repræsenterer de første to PCA-komponenter, som er de vigtigste faktorer for at skelne mellem medarbejderne i denne analyse.



