# MRT Games

MRT Games is a web application developed by **Lương Chính Quốc** and **Nguyễn Tiến Đạt**. This project is built using modern web technologies to provide a seamless and interactive gaming experience.

## 🚀 Technologies Used

The project is developed using the following technologies:

- **React** - A JavaScript library for building user interfaces.
- **React Query** - A data-fetching and state management library.
- **Ant Design** - A UI framework for building elegant web applications.
- **Redux Toolkit** - A state management solution for React applications.
- **Tailwind CSS** - A utility-first CSS framework for rapid UI development.

## 📥 Installation & Setup

Follow the steps below to set up and run the project locally:

### Step 1: Install Dependencies

```sh
npm install
```

### Step 2: Run the Development Server

```sh
npm run dev
```

The project will be available at `http://localhost:3000/` by default.

## 📜 ESLint Configuration

We use ESLint with TypeScript and React to ensure code quality. If you're working on production-level applications, consider expanding the ESLint configuration:

### Type-Aware Rules

Update the `parserOptions` in your ESLint config:

```js
export default tseslint.config({
    languageOptions: {
        parserOptions: {
            project: ['./tsconfig.node.json', './tsconfig.app.json'],
            tsconfigRootDir: import.meta.dirname,
        },
    },
});
```

### React Plugin Setup

Install `eslint-plugin-react` and update your config:

```js
import react from 'eslint-plugin-react';

export default tseslint.config({
    settings: { react: { version: '18.3' } },
    plugins: {
        react,
    },
    rules: {
        ...react.configs.recommended.rules,
        ...react.configs['jsx-runtime'].rules,
    },
});
```

## 💡 Contributing

If you'd like to contribute to **MRT Games**, feel free to fork the repository and submit a pull request!

## 📄 License

This project is licensed under the MIT License.

---

**Developed by:** Lương Chính Quốc & Nguyễn Tiến Đạt

**Profile Links:**

- [Lương Chính Quốc](https://www.facebook.com/quoc.luongchinh.9/)
- [Nguyễn Tiến Đạt](https://www.facebook.com/sweetcter)
