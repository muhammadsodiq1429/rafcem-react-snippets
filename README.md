# rafcem - React Functional Component Snippets

**rafcem** is a powerful Visual Studio Code extension that helps you create React functional components with `React.memo` quickly and efficiently. It's designed to streamline your workflow and ensure your components are optimized by default.

---

### Features

- **Seamless Snippets:** Generate a full functional component with just a few keystrokes.
- **Intelligent Naming:** The snippet automatically uses the current file name for the component, ensuring naming conventions are followed.
- **CSS Class Naming:** It intelligently converts `PascalCase` file names (e.g., `TeacherView.jsx`) into `kebab-case` class names (e.g., `teacher-view`) for cleaner CSS.
- **TypeScript and JavaScript Support:** Provides specific snippets tailored for both JavaScript (`.js`, `.jsx`) and TypeScript (`.ts`, `.tsx`).

---

### Usage

Simply type `rafcem` in your editor and press `Enter` or `Tab`. The snippet will generate a complete React component based on the file type.

#### Example 1: JavaScript (`.jsx`)

When you type `rafcem` in `MyComponent.jsx`, you get:

```jsx
import React from "react";

const MyComponent = () => {
  return (
    <div className="my-component">
      <h2>MyComponent</h2>
    </div>
  );
};

export default React.memo(MyComponent);
```

#### Example 2: TypeScript (`.tsx`)

When you type rafcem in MyComponent.tsx, you get:

```tsx
import React, { type FC } from "react";

interface IProps {}

const MyComponent: FC<IProps> = ({}: IProps) => {
  return (
    <div className="my-component">
      <h2>MyComponent</h2>
    </div>
  );
};

export default React.memo(MyComponent);
```

### Installation

1.  Open Visual Studio Code.
2.  Go to the Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X`).
3.  Search for **"rafcem"**.
4.  Click **Install**.

---

### Feedback and Contributions

Your feedback is highly valued! If you encounter any bugs or have suggestions for new features, please open an issue on the GitHub repository.

Thank you for using rafcem!
