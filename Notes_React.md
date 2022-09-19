# REACT

## Komponenten

### ... - Ordnerstruktur (Beispiel)

```
⩔ src
  ⩔ components
    ⩔ header
      Header.js
      Header.css
```

### ...erstellen mit React (Beispiel)

```javascript
function Header() {
  return {
    <header className="header">
      <h1>This is a Header</h1>
    </header>
  };
}
```

## Unterschiede zwischen HTML & JS X

```html
in HTML
<label for=""></label>
in JS X
<label htmlFor=""></label>

in HTML
<div class="test"></div>
in JS X
<div className="test"></div>
```
