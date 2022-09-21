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

## Hooks

### ... werden beispielsweise gebaut wie:

```javascript
//useState ist ein Hook
import { useState } from "react";

function ExampleFunction({ param }) {
  const [val, setVal] = useState('defaultVal');

  return (
    <div>{val}</div>
    <button onclick={()=> {
      setVal('anotherVal');
    }}>anotherVal</button>
    <button onclick={()=> {
      setVal('theOtherVal');
    }}>theOtherVal</button>

    //conditional Rendering
    {val === "theOtherVal" && <p>Yes theOtherVal is the one</p>}
  )
}
```
