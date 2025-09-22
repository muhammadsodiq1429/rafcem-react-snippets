<file name=0 path=/Users/muhammadsodiqmuhammadjonov/Documents/programming/Small-Projects/racfem-react-snippets/README.md># rafcem-react-snippets

A collection of React snippets with `memo` and PascalCase support for faster component creation.

## Features

- React functional components wrapped with `memo`
- PascalCase component naming based on file name
- Support for both **JavaScript (JSX)** and **TypeScript (TSX)**
- Includes commonly used hooks snippets

## Installation

1. Open **Extensions** view in VS Code (`Ctrl+Shift+X` or `Cmd+Shift+X` on Mac).
2. Search for **rafcem-react-snippets**.
3. Click **Install**.

## Usage

Open a `.jsx` or `.tsx` file and type one of the snippet prefixes, then press `Tab`.

## Snippets

### `rafcem` – React Functional Component with Memo (JavaScript/TypeScript)

**Prefix:** `rafcem`  
**Description:** Generates a React functional component wrapped with `memo`. Supports both JavaScript and TypeScript files. The component name is derived from the file name in PascalCase.

**Example:**

```tsx
import { memo } from 'react';

const MyComponent = () => {
  return (
    <div>
      <h2>MyComponent</h2>
    </div>
  );
};

export default memo(MyComponent);
```

---

### `rafcemt` – React Functional Component with Typed Props and Memo (TypeScript)

**Prefix:** `rafcemt`  
**Description:** Generates a typed React functional component with props interface and wrapped with `memo`. Designed for `.tsx` files.

**Example:**

```tsx
import React, { memo } from 'react';

interface MyComponentProps {}

const MyComponent: React.FC<MyComponentProps> = (props) => {
  return (
    <div>
      <h2>MyComponent</h2>
    </div>
  );
};

export default memo(MyComponent);
```

---

### `rame` – React Arrow Function Component with Memo (JavaScript)

**Prefix:** `rame`  
**Description:** Creates a React functional component using arrow function syntax wrapped with `memo` for JavaScript files.

**Example:**

```jsx
import { memo } from 'react';

const MyComponent = () => {
  return (
    <div>
      <h2>MyComponent</h2>
    </div>
  );
};

export default memo(MyComponent);
```

---

### `ramet` – React Arrow Function Component with Typed Props and Memo (TypeScript)

**Prefix:** `ramet`  
**Description:** Creates a typed React arrow function component with props interface wrapped with `memo` for TypeScript files.

**Example:**

```tsx
import React, { memo } from 'react';

interface MyComponentProps {}

const MyComponent: React.FC<MyComponentProps> = (props) => {
  return (
    <div>
      <h2>MyComponent</h2>
    </div>
  );
};

export default memo(MyComponent);
```

---

### `us` – useState Hook Snippet

**Prefix:** `us`  
**Description:** Generates a `useState` hook declaration with state variable and setter.

**Example:**

```tsx
const [state, setState] = useState(initialValue);
```

---

### `ud` – useEffect Hook Snippet with Dependency Array

**Prefix:** `ud`  
**Description:** Generates a `useEffect` hook with an empty dependency array.

**Example:**

```tsx
useEffect(() => {
  // effect logic here
}, []);
```

---

## Contribution

We welcome contributions! If you have ideas for new snippets, bug fixes, or improvements, please open an issue or submit a pull request on the [GitHub repository](https://github.com/muhammadsodiq1429/rafcem-react-snippets). Your feedback and help are highly appreciated.

## Support / Donate

If you find this extension useful and would like to support its development, consider donating or sponsoring the project on GitHub Sponsors or other platforms. Your support helps us maintain and improve the extension.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
