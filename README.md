# NodeJs + Typescript w/ superpowers 🚀

This project is used as a template for creating new projects in **NodeJS** with **Typescript**.

Adds Eslint, Prettier, and pre-commit hooks settings.

---

### How to use

---

Since it is a template with the necessary dependencies, the only thing that would be enough to start is to do an `npm install`

---

### Tree Directory

---

```markdown
├── .husky
│ ├── pre-commit
│
├── **test**
│ ├── (Test should be added it here)
│
├── src
│ ├── (App goes here Ts files)
│
├── .eslintrc.json
├── .lintstagedrc.json
├── README.md
├── .prettierrc.json
├── .nodemon.json
├── tsconfig.json
├── package.json
├── package-lock.json
└── .gitignore
```

To create a repository and clone it to your machine using this template using the github CLI run this command

```
gh repo create my-project --public --clone --template=https://github.com/llocon3pg/node-ts
```

If you want to create a PR, please fork it and then request approval of the change.
