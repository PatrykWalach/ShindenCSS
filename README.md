# Shinden CSS Style

## Użycie

Z folderu _dist_ należy skopiować porządany styl.
Informacje o sposobie korzystania ze stylów CSS na stronie shinden.pl znajdują się na forum [link](https://forum.shinden.pl/index.php?threads/gotowe-wzory-styli-list-anime-i-mang.19824/).

Opcja `Tryb zgodnosci z myanimelist.com` powinna być odznaczona.

## Dostępne style

<details>
<summary>
Default

</summary>

![](https://i.imgur.com/YP1m7Hx.png)

</details>

<details>
<summary>
Dark Theme

</summary>

![](https://i.imgur.com/n0PRGCB.png)

</details>
<details>
<summary>
High Contrast Theme

</summary>

![](https://i.imgur.com/UvuAaRh.png)

</details>

### Dostosowywanie

W celu dostosowania własnego kodu css można zastosować poniższe przykłady. Kod powinien być dodany na końcu swojego pliku css.

#### Ustawienie własnego zdjęcia jako tło.

```css
.background {
  background-image: url('https://adres_serwera/ścieżka_dostępu');
}
```

#### Zmiana kolorów

Kolor może być podany w dowolnym formacie
Specyfikacja [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value).

##### Zmiana kolorów tła.

```css
:root {
  --background: rgba(31, 35, 45, 1);
  --background-light: rgba(39, 44, 56, 1);
}
```

##### Zmiana kolorów czcionki.

```css
:root {
  --text: #000;
  --text-light: #5e656f;
  --text-lighter: #9299a1;
}
```

##### Zmiana głównego koloru

```css
:root {
  --primary: rgb(18, 172, 253);
  --primary-dark: rgb(85, 144, 208);
}
```

#### Zmiana wielkości odstępu w którym widoczne jest tło

Odstęp może być podany w dowolnej jednostce długości.
Specyfikacja [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/length)

```css
:root {
  --gap: 100vh;
}
```

## Rozwój

Style do edycji znajdują się w folderze `src`.

### Skrypty

Komenda służąca do wygenerowania stylów w katalogu `dist`.

```sh
npm run concat
```

### Struktura plików

```
|- root
|   |- dist
|   |- src
|   |- ...
```

### Git

<https://github.com/PatrykWalach/shindenCSS>

## Licencja

[MIT](https://github.com/PatrykWalach/shindenCSS/blob/master/LICENSE)
