# **Opis projektu**
Projekt to gra typu space shooter. Gra polega na zdobyciu jak największej ilości punktów, które otrzymujemy za strzelanie do obiektów. W przypadku kolizji z obiektem tracimy punkty zdrowia, gdy zejdą do 0 gra się zakończy.
# **Project description**
This project is a  space shooter type game. The game is about getting as many points as possible for shooting objects. In the event of a collision with an object, we lose health points when they go below 0, the game is over.
# **Instrukcja użytkownika**
Po kompilacji programu rozpoczyna się gra. Za pomocą przycisków WASD poruszamy się samolotem po mapie. Za pomocą spacji możemy strzelać do nadlatujących obiektów.
# **Pliki źródłowe**
Projekt składa się z następujących plików źródłowych:

- *Game.h, Game.cpp* – deklaracja oraz implementacja środowiska gry,
- *Player.h*, *Player.cpp* – deklaracja oraz implementacja postaci,
- *Enemy.h*, *Enemy.cpp* – deklaracja oraz implementacja przeciwników,
- *Bullet.h*, *Bullet.cpp* – deklaracja oraz implementacja pocisku
# **Zależności**
W projekcie wykorzystano następujące dodatkowe biblioteki:

- SFML –  biblioteka programistyczna ułatwiająca tworzenie gier oraz programów multimedialnych\
Strona internetowa: https://www.sfml-dev.org/
# **Opis klas**
W projekcie utworzono następujące klasy:

- Game – klasa odpowiedzialna za przebieg rozgrywki
- Player – klasa zawierająca obsługę samolotu
- Enemy – klasa odpowiedzialna za tworzenie przeciwników
- Bullet – klasa zawierająca obsługę pocisków
# **Zasoby**
W projekcie wykorzystywane są następujące pliki zasobów:

- 04B\_03.TTF – plik zawierający wykorzystywaną czcionkę
- background.jpg – plik zawierający tło gry
- bullet.png – plik zawierający grafikę pocisku
- ship.png – plik zawierający grafikę statku
