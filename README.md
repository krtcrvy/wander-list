# Wander List Project Documentation

## Table of Contents

1. Introduction
2. [Project Structure](#project-structure)
3. Installation
4. Scripts
5. Configuration
6. Components
7. Data
8. Styling
9. Linting
10. [Building and Running](#building-and-running)

## Introduction

Wander List is a React-based project designed to help users manage their packing lists. This documentation provides an overview of the project structure, installation steps, available scripts, and other essential details.

## Project Structure

The project has the following structure:

```
.gitignore
biome.json
data.js
eslint.config.js
index.html
package.json
pnpm-lock.yaml
public/
README.md
src/
	App.jsx
	assets/
	components/
		Form.jsx
		Item.jsx
		Logo.jsx
		PackingList.jsx
		Stats.jsx
	index.css
	main.jsx
vite.config.js
```

### Key Files and Directories

- **src/**: Contains the source code for the application.
  - **App.jsx**: The main application component.
  - **components/**: Contains reusable React components.
    - **Form.jsx**: Component for the form used to add items.
    - **Item.jsx**: Component representing a single item in the list.
    - **Logo.jsx**: Component for the application logo.
    - **PackingList.jsx**: Component for displaying the list of items.
    - **Stats.jsx**: Component for displaying statistics about the packing list.
  - **index.css**: Global CSS styles.
  - **main.jsx**: Entry point for the React application.
- **data.js**: Contains initial data for the application.
- **package.json**: Contains project metadata and dependencies.
- **vite.config.js**: Configuration file for Vite.
- **eslint.config.js**: Configuration file for ESLint.
- **biome.json**: Configuration file for Biome.

## Installation

To install the project dependencies, run the following command:

```sh
pnpm install
```

## Scripts

The following scripts are available in the [`package.json`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fwander-list%2Fpackage.json%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%222a7d248d-4b7e-4036-856b-fb9aeffe9bb6%22%5D "c:\\Users\karbi\Documents\GitHub\wander-list\package.json") file:

- **dev**: Starts the development server.
  ```sh
  pnpm run dev
  ```
- **build**: Builds the project for production.
  ```sh
  pnpm run build
  ```
- **lint**: Runs ESLint to lint the codebase.
  ```sh
  pnpm run lint
  ```
- **preview**: Previews the production build.
  ```sh
  pnpm run preview
  ```

## Configuration

### Vite

The Vite configuration is located in [`vite.config.js`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fwander-list%2Fvite.config.js%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%222a7d248d-4b7e-4036-856b-fb9aeffe9bb6%22%5D "c:\\Users\karbi\Documents\GitHub\wander-list\vite.config.js"). It includes settings for building and serving the application.

### ESLint

The ESLint configuration is located in [`eslint.config.js`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fwander-list%2Feslint.config.js%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%222a7d248d-4b7e-4036-856b-fb9aeffe9bb6%22%5D "c:\\Users\karbi\Documents\GitHub\wander-list\eslint.config.js"). It defines the linting rules for the project.

### Biome

The Biome configuration is located in [`biome.json`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fwander-list%2Fbiome.json%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%222a7d248d-4b7e-4036-856b-fb9aeffe9bb6%22%5D "c:\\Users\karbi\Documents\GitHub\wander-list\biome.json"). It includes various rules for code quality and style.

## Components

### App.jsx

The main application component that renders the entire application.

### Form.jsx

A form component used to add new items to the packing list.

### Item.jsx

A component representing a single item in the packing list.

### Logo.jsx

A component that displays the application logo.

### PackingList.jsx

A component that displays the list of items to be packed.

### Stats.jsx

A component that displays statistics about the packing list, such as the number of items packed and unpacked.

## Data

The initial data for the application is defined in [`data.js`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fwander-list%2Fdata.js%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%222a7d248d-4b7e-4036-856b-fb9aeffe9bb6%22%5D "c:\\Users\karbi\Documents\GitHub\wander-list\data.js"):

```js
export const initialItems = [
  { id: 1, description: "Passports", quantity: 2, packed: false },
  { id: 2, description: "Socks", quantity: 12, packed: true },
  { id: 3, description: "Charger", quantity: 1, packed: false },
];
```

## Styling

Global CSS styles are defined in [`src/index.css`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fwander-list%2Fsrc%2Findex.css%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%222a7d248d-4b7e-4036-856b-fb9aeffe9bb6%22%5D "c:\\Users\karbi\Documents\GitHub\wander-list\src\index.css"). Each component may also have its own styles defined within the component file.

## Linting

ESLint is used to ensure code quality and consistency. The configuration is defined in [`eslint.config.js`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fwander-list%2Feslint.config.js%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%222a7d248d-4b7e-4036-856b-fb9aeffe9bb6%22%5D "c:\\Users\karbi\Documents\GitHub\wander-list\eslint.config.js"). To run the linter, use the following command:

```sh
pnpm run lint
```

## Building and Running

### Development

To start the development server, run:

```sh
pnpm run dev
```

### Production

To build the project for production, run:

```sh
pnpm run build
```

To preview the production build, run:

```sh
pnpm run preview
```
