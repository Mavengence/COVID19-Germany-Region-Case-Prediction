<div style="background-color:white">
  <div align="center">
    <h1 style="color:black">Corona Fallzahl Vorhersage für die 412 Landkreise Deutschlands (Prediction for Corona Cases in every Region of Germany)<h1>
    <img src="https://www.med.fau.de/wp-content/themes/FAU-Medfak/img/logos/logo-med-240x65.gif" width="400">
  </div>
  <hr>
</div>

## Motivation

This was my final assignment for the course Clinical Data Science at the Friedrich Alexander University Department of Health for Master of Computer Science.

I used the common time-series method ARIMA to predict the COVID cases.

### Outline

```

1. Dataset Loading
2. Data Preprocessing
3. Testen & Spielen
3.1 Anzahl Fall Verlauf für Nürnberg
3.2 Anzahl Fall Verlauf für Nürnberg mit Rolling Mean 3
3.3 Anzahl Fall Verlauf für Nürnberg mit Rolling Mean 7
4. Aufgabe 1
4.1 RMSLE Optimierung
4.2 RMSLE Optimierung lt. Aufgabe 2b
4.3 Plots für vorhergesagte Werte März
4.4 Plots für vorhergesagte Werte April
4.5 Results als CSV
5. Model Selektion für das Training
3.1 Beste Werte für ARIMA
6. Aufgabe 2
6.1 Preprocessing für CSV
6.2 Results als CSV            

```

### Prerequisites

```
The dependencies to this project are stored in the file:
   - requirements.txt

I use python version 3.7.4
```

## Author

* **Tim Löhr** - If you have questions you can contact me under timloehr@icloud.com

## License

This project was done during my course Clinical Data Science at the Friedrich Alexander University in Erlangen-Nürnberg.
