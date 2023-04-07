# Next.js Tailwind Starter with Query

This is a minimal Next.js starter project with Tailwind CSS and query set up, so you can easily get started with your own custom project. The setup is simple and straightforward, allowing you to focus on building your application the way you like.

## Features

- Next.js framework for building React applications
- Tailwind CSS for styling
- Basic query setup for fetching data

## Prerequisites

Before you begin, make sure you have the following tools installed on your machine:

- Node.js (>= 16.14.0)
- pnpm (>= 6.0.0)

If you don't have `pnpm` installed, you can install it globally using the following command:

### `npm install -g pnpm`

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository:

#### `https://github.com/Myszczyson/barebone_next_tailwind_query.git`

2. Change to the project directory:

#### `cd barebone_next_tailwind_query`

3. Install dependencies:

#### `pnpm install`

4. Set up precommit command

#### `npx simple-git-hooks`

5. Start the development server:

#### `pnpm run dev`

6. Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to view the app.

## Customizing the Project

Now that you have the project set up, you can start customizing it to suit your needs.

To add new pages, simply create a new `.js` or `.tsx` file inside the `pages` directory.

For fetching data, React Query is set up as a provider, allowing you to use your preferred method of implementation.

## Linting

This project uses the Rome linter to lint JavaScript and TypeScript files. Please note that Rome currently does not support linting HTML, Markdown, or CSS files.

To lint the project, run the following command:

#### `pnpm run lint`

By default, the lint command only checks the `pages` folder. If you want to lint additional folders, simply update the command in the `scripts` section of your `package.json` file.

## Git Hooks and GitHub Workflow

This project includes a GitHub workflow for type checking and linting on push events. Additionally, you can use `simple-git-hooks` to set up a pre-commit hook that runs type checking and linting before committing your changes. For more information on setting up `simple-git-hooks`, refer to [this guide](https://github.com/toplenboren/simple-git-hooks).

## Deployment

To deploy your app, you can use platforms like [Vercel](https://vercel.com), [Netlify](https://www.netlify.com), or [Railway](https://railway.app). Follow their respective documentation to deploy your Next.js application.

- Vercel: [https://vercel.com/docs](https://vercel.com/docs)
- Netlify: [https://www.netlify.com/docs](https://www.netlify.com/docs)
- Railway: [https://docs.railway.app](https://docs.railway.app)

## License

This project is released under the MIT License. See the [LICENSE](LICENSE) file for more information.
