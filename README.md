# npm-react-typescript-template

This repository serves as a base for creating npm packages using React and TypeScript. 
It comes preconfigured with a build process and a set of recommended packages for a modern development workflow.


## Features

- **React & TypeScript**: Write your package in modern React with TypeScript for type safety and better developer experience.
- **CSS Modules**: Style your components in isolation using CSS Modules, avoiding CSS conflicts and enabling modular design.
- **ESLint**: Keep your code clean and adhere to the latest best practices in JavaScript and React.
- **Rollup**: Build your package efficiently with Rollup, bundling your React and TypeScript code into a single file for distribution.
- **PostCSS**: Use next-gen CSS features with PostCSS, and let the build process handle compatibility with older browsers.

## Usage

1. **Clone this repository** into a directory of your choice. You can do this with `git clone https://github.com/<username>/npm-react-typescript-template.git`, replacing `<username>` with your GitHub username.

2. **Navigate into the directory** with `cd npm-react-typescript-template`.

3. **Install the dependencies** with `npm install`.

4. **Start developing** your package! The entry point is `src/index.tsx`.

## Building the Package

* before building, fill the name, version, description and author field in the pacakge.json. 

* if the fields are filled, update the version

* run `npm run build`
The built package will be in the `dist` directory, ready for publishing to npm.

## publishing

* login : `npm login`
* publish : `npm publish`

## Author

* [Maxime Malfilâtre](https://maxime-malfilatre.com)
