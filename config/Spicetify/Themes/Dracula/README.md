# text

### Description

a spicetify theme that mimics the look of [spotify-tui](https://github.com/Rigellute/spotify-tui)

### Credits

created by [darkthemer](https://github.com/darkthemer/)

### Notes

-   **IMPORTANT:** Add the following to your `config-xpui.ini` file. Details as to why are explained [here](https://github.com/JulienMaille/spicetify-dynamic-theme#important).

```ini
[Patch]
xpui.js_find_8008 = ,(\w+=)56,
xpui.js_repl_8008 = ,${1}32,
```


### Display Images

##### with images

```css
--display-card-image: block;
--display-coverart-image: block;
--display-header-image: block;
--display-library-image: block;
--display-tracklist-image: block;
```


##### without images

```css
--display-card-image: none;
--display-coverart-image: none;
--display-header-image: none;
--display-library-image: none;
--display-tracklist-image: none;
```

