# Porównanie klasyfikacji obrazów galaktyk z wykorzystaniem różnych architektur CVV
## Wprowadzenie
Rozwój technologii spowodował, że w wielu dziedzinach życia, to komputery są nieodzownym elementem pracy. Tak samo jest z astronomią, gdzie obecnie dawne sposoby obserwacji wszechświata już nie wystarczają i jedynym sposobem dalszego poznawania otaczających nas gwiazd i galaktyk jest wykorzystanie technologii. Dzięki temu obserwacje wykonane na drugim końcu świata po zakończonej pracy i wstępnym przetworzeniu są udostępniane wszystkim zainteresowanym. Również osobom, które nie są związane z astronomią zawodowo, ale tak jak ja interesują się tą dzienną nauki, na własną rękę pogłębiając swoją wiedzę.

W astronomii, mimo że wydaje się, że mamy już sporą wiedzę na temat gwiazd i galaktyk, jednak jest jeszcze wiele rzeczy do odkrycia. Jednym z nich jest klasyfikacja galaktyk. Teoretycznie spora część z nich jest już sklasyfikowana dzięki projektowi Galaxy Zoo, jednak teleskopy różnego typu dostarczają kolejnych danych i jest ich coraz więcej. Dlatego dobrym sposobem z poradzeniem sobie z tymi danymi jest wykorzystanie do tego celu uczenia maszynowego.
## Artykuł
Na podstawie wykonanego projektu powstał artykuł pod adresem: https://www.linkedin.com/pulse/por%C3%B3wnanie-klasyfikacji-obraz%C3%B3w-galaktyk-z-r%C3%B3%C5%BCnych-cnn-kossakowski-adctf/?trackingId=P3Krg4UmgMLg9cxgB90LSQ%3D%3D
## Organizacja projektu
W projekcie został wykorzystany Jupiter Notebook. Dla każdego modelu został utworzony nowy notebook i wszystkie operacje są wykonywane w jednym notebook. Jedynie otrzymane rezultaty są przechowywane w formie plików CSS do dalszej analizy. Do każdego pliku powstała wersja pdf, aby ułatwić proces analizy. Nazwy plików pdf są identyczne z plikami notebook.
Notebooki zawierają następujące architektury:
- **Model.ipynb** - model głębokiej sieci neuronowej. W tym przypadku nie wykorzystuje architektur CNN.
- **ModelLeNet5.ipynb** -  jest to architektura przedstawiona przez Yann LeCun w 1989 roku.
- **ModelAlexNet.ipynb** - AlexNet jest to architektura CNN z roku 2012. Została stworzona na zawody ImageNet Large Scale Visual Recognition Challenge (ILSVRC)
- **ModelMobileNet.ipynb** - została zaprojektowana przez formę Google i jest przeznaczony na urządzenia mobilne.
## Technilogie
- Anaconda 23.11.0
- Python 3.10.13
- Jupyter notebook 7.0.6
## Uruchomienie
Ja w swoim projekcie wykorzystuje Anaconda. Dobrze jest przy pomocy polecenia cd ustawić się w swoim katalogu projektu. Następnie wykonujemy następujące polecenia i Acaconda uruchamia się w przeglądarce.
```
conda activate [nazwa projektu w Anaconda]
jupyter notebook
````
Gdy chcemy zamknąć projekt, klikamy Ctrl + C, a następnie zgadzamy się i wykonujemy polecenie, aby wyłączyć środowisko, wykonujemy polecenie. 
```
conda deactivate
```

