# Instrukcja budowy prostego obrazu

#### 1. stworzyć folder projektu

#### 2. przejść do folderu

- utowrzyć plik index.html 
dodać do niego nasz kod źródłowy

- utowrzyć plik Dockerfile

**Bez żadnego rozszerzenia**

dodać kod: 
```
From nginx:alpine
Copy . /usr/share/nginx/html
```
#### 3. zbudować obraz

za pomocą komendy:

```
docker build -t app:v1 . 
```


#### 4. Sprawdź czy obraz powstał

za pomocą komendy:

```
docker images

```
