<file name=0 path=/Users/muhammadsodiqmuhammadjonov/Documents/programming/Small-Projects/racfem-react-snippets/README.md># rafcem-react-snippets

## Introduction

Welcome to **rafcem-react-snippets**, a Visual Studio Code extension designed to boost your productivity when developing React applications with TypeScript. This extension provides a collection of handy code snippets to help you write React components, hooks, and utilities faster.

## Snippets Overview

Below are the key snippets included in this extension, along with their prefixes, descriptions, and usage examples.

### `rafcem` - React Functional Component with Memo

- **Prefix:** `rafcem`
- **Description:** Creates a React functional component wrapped with `memo` and PascalCase name.
- **Output when you type `rafcem` and press Tab:**
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

### `rafcemt` - React Functional Component with Typed Props and Memo (TypeScript)

- **Prefix:** `rafcemt`
- **Description:** Creates a React functional component with props interface, `FC`, and `memo` in TypeScript.
- **Output when you type `rafcemt` and press Tab:**
  ```tsx
  import { memo, type FC } from 'react';

  interface MyComponentProps {
    // props go here
  }

  const MyComponent: FC<MyComponentProps> = (props) => {
    return (
      <div>
        <h2>MyComponent</h2>
      </div>
    );
  };

  export default memo(MyComponent);
  ```

### `rame` - React Arrow Function Component with Memo (JavaScript)

- **Prefix:** `rame`
- **Description:** Creates a React functional component using arrow function syntax, wrapped with `memo`.
- **Output when you type `rame` and press Tab:**
  ```jsx
  import { memo } from 'react';

  export const MyComponent = memo(() => {
    return (
      <div>
        <h2>MyComponent</h2>
      </div>
    );
  });
  ```

### `ramet` - React Arrow Function Component with Typed Props and Memo (TypeScript)

- **Prefix:** `ramet`
- **Description:** Creates a typed React arrow function component with props interface, `FC`, and `memo` in TypeScript.
- **Output when you type `ramet` and press Tab:**
  ```tsx
  import { memo } from "react";
  import type { FC } from "react";

  interface MyComponentProps {
    // props go here
  }

  export const MyComponent: FC<MyComponentProps> = memo((props) => {
    return (
      <div>
        <h2>MyComponent</h2>
      </div>
    );
  });

  ```

### `us` - useState Hook Snippet

- **Prefix:** `us`
- **Description:** Generates a `useState` hook declaration with state variable and setter.
- **Output when you type `us` and press Tab:**
  ```tsx
  const [count, setCount] = useState();
  ```

### `ud` - useDispatch Hook Snippet

- **Prefix:** `ud`
- **Description:** Generates a `useDispatch` hook declaration.
- **Output when you type `ud` and press Tab:**
  ```tsx
  const dispatch = useDispatch();
  ```

## Contribution

Contributions are welcome! If you have ideas for new snippets, improvements, or bug fixes, please open an issue or submit a pull request on the [GitHub repository](https://github.com/your-repo/rafcem-react-snippets).

## Support / Donate

If you find this extension helpful, consider supporting the project by starring the repository or donating via [GitHub Sponsors](https://github.com/sponsors/your-profile) or other platforms. Your support helps maintain and improve the extension.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Welcome to rafcem-react-snippets

## Getting Started

To start using **rafcem-react-snippets**, install the extension from the Visual Studio Code Marketplace or clone the repository and install it manually. Once installed, you can trigger snippets by typing their prefixes in a React TypeScript file (`.tsx`).

## Example Usage

For example, typing `rafcem` and pressing `Tab` will generate a React arrow function component with memoization and TypeScript props, saving you time on boilerplate code.

## Adding New Snippets

To add new snippets, edit the `snippets/snippets.code-snippets` file. Define the prefix, description, and body of your snippet in JSON format. Reload the extension or VS Code window to apply changes.

## Contribution

We welcome contributions! Please report issues or suggest new snippets via GitHub issues. Pull requests with improvements or new snippets are highly appreciated.

## Community

Join our growing community of React developers using rafcem-react-snippets. Share your feedback, ideas, and help improve this tool for everyone.
</file>
