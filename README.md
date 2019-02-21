# CSS Styles

## Użycie / Usage

Z folderu _dist_ należy skopiować porządany styl.
Informacje o sposobie korzystania ze stylów CSS na stronie shinden.pl znajdują się na forum [link](https://forum.shinden.pl/index.php?threads/gotowe-wzory-styli-list-anime-i-mang.19824/).
Opja _Tryb zgodnosci z myanimelist.com_ powinna być odznaczona

---

## Development

Style do edycji znajdują się w folderze src.
Nie należy modyfikować plików _main.css_, znajdujących się w podfolderach, gdyż są one automatycznie generowane przez skrypt i służą do połączenia stylów w całość.

### Do zrobienia / To do

- Zamiana skryptu na niegenerujący dodatkowych plików w folderze _src_

### Skrypty / Scripts

Wygenerowanie stylów w katalogu _dist_.

```bash
npm run concat
```

### Struktura plików / File structure

```
|- root
|   |- dist
|   |- src
|   |- ...
```

### Git

https://github.com/PatrykWalach/shindenCSS

## Licencja / License

MIT
