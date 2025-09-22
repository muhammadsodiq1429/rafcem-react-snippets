# rafcem-react-snippets

## Introduction

Welcome to **rafcem-react-snippets**, a Visual Studio Code extension designed to boost your productivity when developing React applications with TypeScript. This extension provides a collection of handy code snippets to help you write React components, hooks, and utilities faster.

## Snippets Overview

Below are the key snippets included in this extension, along with their prefixes, descriptions, and usage examples.

### `rafcem` - React Arrow Function Component with Export and Memoization

- **Prefix:** `rafcem`
- **Description:** Creates a React arrow function component with TypeScript props, exports it as a memoized component.
- **Example:**
  ```tsx
  import React, { memo } from 'react';

  interface Props {
    // define your props here
  }

  const ComponentName: React.FC<Props> = (props) => {
    return (
      <div>
        {/* component implementation */}
      </div>
    );
  };

  export default memo(ComponentName);
  ```

### `rafcemt` - React Arrow Function Component with Export, Memoization, and TypeScript Types

- **Prefix:** `rafcemt`
- **Description:** Similar to `rafcem` but includes explicit TypeScript type annotations for props and component.
- **Example:**
  ```tsx
  import React, { memo } from 'react';

  type Props = {
    // define your props here
  };

  const ComponentName: React.FC<Props> = (props: Props) => {
    return (
      <div>
        {/* component implementation */}
      </div>
    );
  };

  export default memo(ComponentName);
  ```

### `rame` - React Arrow Function Component with Export

- **Prefix:** `rame`
- **Description:** Creates a React arrow function component with props and exports it without memoization.
- **Example:**
  ```tsx
  import React from 'react';

  interface Props {
    // define your props here
  }

  const ComponentName: React.FC<Props> = (props) => {
    return (
      <div>
        {/* component implementation */}
      </div>
    );
  };

  export default ComponentName;
  ```

### `ramet` - React Arrow Function Component with Export and TypeScript Types

- **Prefix:** `ramet`
- **Description:** React arrow function component with explicit TypeScript types and export.
- **Example:**
  ```tsx
  import React from 'react';

  type Props = {
    // define your props here
  };

  const ComponentName: React.FC<Props> = (props: Props) => {
    return (
      <div>
        {/* component implementation */}
      </div>
    );
  };

  export default ComponentName;
  ```

### `us` - React useState Hook Snippet

- **Prefix:** `us`
- **Description:** Generates a React `useState` hook with TypeScript type and initial value.
- **Example:**
  ```tsx
  const [state, setState] = React.useState<Type>(initialValue);
  ```

### `ud` - React useEffect Hook Snippet with Dependency Array

- **Prefix:** `ud`
- **Description:** Creates a React `useEffect` hook with a dependency array.
- **Example:**
  ```tsx
  React.useEffect(() => {
    // effect implementation
  }, [dependencies]);
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
