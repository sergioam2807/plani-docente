# Next.js + TypeScript + Tailwind CSS Boilerplate

This is a boilerplate project for Next.js, set up with TypeScript and Tailwind CSS.

## 📘 Usage

This boilerplate project was created to facilitate the development of applications with Next.js, TypeScript, and Tailwind CSS.

## 🚀 Getting Started with Local Development

To build this repo, you will need Node.js 18.17 or later.

1. Clone this repo to your local machine with `git clone`.
2. In your terminal, navigate into this repo using `cd`.
3. Run `npm install` to install dependencies.
4. Once dependencies are installed, you can run `npm run dev` to start the local development server.
5. Open http://localhost:3000 with your browser to see the result.
6. You can start editing the page by modifying app/page.tsx. The page auto-updates as you edit the file.
7. This project uses next/font to automatically optimize and load Inter, a custom Google Font.

## 👀 What You Need to Know

This repo includes a list of tools for local continuous integration:

- Prettier: a code formatter that removes all original styling and ensures that all outputted code conforms to a consistent style.
- ESLint: ESLint statically analyzes your code to quickly find problems.
- Husky: this tool supports all Git hooks, meaning you can execute whatever you want every time a Git hook is triggered. In this case, we have attached:
  - pre-commit: it will run ESLint, which will find and try to fix anything in your code that doesn't match the applied style, including Prettier if you didn't do it.
  - pre-push: it will run unit testing via Jest.

## 💻 Supported Technologies

- Next.js
- TypeScript
- Tailwind CSS
- ESLint
- Prettier
- Husky

## 🤝 Contributing

Eager to contribute to this repo? Check out our Contribution Guidelines!

## 🛠️ Builds, Environments, and Deployments

- Generate a production build via Next.js with `npm run build`.
- For environment variables, create a `.env.example` file so everyone can replicate it in a simple way.
- Support for Github Actions, please consider reaching out to any of the organization's owners to check availability and team budget.
