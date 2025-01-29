# Makra do Maptoola, Framework dla DnD5e

## Struktura
Każdy katalog to zawartość jednego pliku *.mtmacset lub *.mtprops. Zostały one rozpakowane, aby ułatwić ich wersjonowanie i przeglądanie zawartości. W celu zaimportowania ich do kampanii w Maptoolu, należy je ponownie spakować.
### Zawartość
* campaign - Zawiera makra przypisane do panelu "Campaign / Kampania". Są one ogólnodostępne dla każdego gracza zalogowanego do serwera.
* gm - Zawiera makra przypisane do panelu "GM". Są one dostępne jedynie dla Mistrza Gry i służą głównie do obsługi całego czary mary.
* papaj - Zawiera makra przypisane do tokena "Lib:papaj", który służy jako biblioteka makr, do których odnoszą się inne makra, w tym te z wymienionych wyżej paneli. Powinno do niego trafiać wszystko odpowiedzialne za "backendowe" rozwiązania i nie będące samodzielnymi przyciskami do klikania.
* properties - Zawartość "Campaign Properties", czyli m.in. token properties, lights, bars.

## FAQ
### Czemu nie plik per makro?
Tak wygląda bezpośrednie eksportowanie / importowanie z / do Maptoola. Podział na pojedyncze makra wymagałby dopisania jakiegoś parsera XMLi, który rozkładałby i składał wszystko do plików zdatnych do współpracy z Maptoolem.
### Czemu nazwy niektórych zmiennych są po polsku?
Najstarsze elementy tych makr powstały w okolicach roku 2015. i wciąż służą za bazę do rozwijania dalszych funkcjonalności. Poza tym autor nie spodziewał się, że ktoś to kiedyś zobaczy.
### Jak to zaimportować?
W Maptoolu należy stworzyć swoją własną kampanię testową, spakować zawartości folderów do odpowiednich archiwów, po czym zaimportować je odpowiadających im paneli / tokenów / właściwości. Po edycji / wprowadzeniu ulepszeń, makra i właściwości nalezy wyeksportować. Dla przejrzystości wersjonowania, warto je również następnie rozpakować do odpowiednich katalogów w tym repozytorium.