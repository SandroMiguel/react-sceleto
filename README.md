<p align="center"><img src="http://sandromiguel.com/host/react-sceleto_03.png" alt="React Sceleto" /></p>

# Welcome to React Sceleto
**React Sceleto is a React directory structure with the basic 
[Create React App](https://github.com/facebook/create-react-app) files.**

[![license](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](LICENSE)

The inspirational skeleton in React

Current version: **0.3.1**

## Directory structure
```
your-react-app/
├── public/
│   ├── index.html
│   ├── favicon.ico
│   └── manifest.json
│
├── src/
│   ├── components/
│   │   ├── [SomeComponent/]
│   │   |   └── [SomeComponent].js
│   │   ├── [OtherComponent/]
│   │   |   └── [OtherComponent].js
│   │   ├── ...
│   ├── assets/
│   │   ├── [some_image].png
│   │   ├── [some_image].svg
│   │   ├── ...
│   ├── utils/
│   │   ├── [someUtil].js
│   │   ├── ...
│   ├── index.js
│   ├── index.css
│   ├── App.js
│   ├── App.css
│   ├── App.test.js
│   └── registerServiceWorker.js
│
├── .gitignore
├── .editorconfig
├── .eslintrc.js
├── package.json
├── README.md
└── yarn.lock
```

## Getting Started

### Step 1 - Install this directory structure
#### Option #1 - Clone this repo
Create a new directory and clone the repo.
```
git clone https://github.com/SandroMiguel/react-sceleto.git your-react-app
```

#### Option #2 - Download
Download the [latest release](https://github.com/SandroMiguel/react-sceleto/archive/v.0.2.zip)

### Step 2 - Install the dependencies
Install the dependencies with Yarn or npm.
```
cd your-react-app   # your project name
yarn                # or npm i
```

### Step 3 - Run application
Start the application with hot reload.
```
yarn start          # or npm start
```

## Run ESLint
Run JavaScript syntax check to improve your code quality.
```
yarn eslint          # or npm eslint
```

## Files and Folders
Files and folders overview.

| File/Folder | Description |
| --- | --- |
| **public/** | Build output folder |
| public/**index.html** | HTML entry point for the application |
| public/**favicon.ico** | Favicon |
| public/**manifest.json** | Manifest properties |
| **src/** | The source code of the application |
| src/**components/** | React components |
| src/components/**SomeComponent/** | React component folder example |
| src/components/SomeComponent/**SomeComponent.js** | React component file example |
| src/**assets/** | Static resources eg. images, pdf, etc. |
| src/assets/**some_image.png** | Image file example |
| src/**utils/** | Helper files eg. error handlers, formatters, etc. |
| src/utils/**someUtil.js** | Util file example |
| src/**index.js** | JS entry point for the application |
| src/**index.css** | CSS file for index.js |
| src/**App.js** | Include your main components |
| src/**App.js** | CSS file for App.js |
| src/**App.test.js** | Unit tests for App.js |
| src/**registerServiceWorker.js** | Service Worker API for offline capabilities |
| **.gitignore** | Files and directories that Git should ignore |
| **.editorconfig** | IDE coding style |
| **.eslintrc.js** | ESLint configuration |
| **package.json** | Package configuration |
| **README.md** | This document |
| **yarn.lock** | Dependencies information for Yarn |

## Credits
- Code base - Facebook [Create React App](https://github.com/facebook/create-react-app)
- Linting - [ESLint](https://eslint.org/)
- Javascript specs - [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
- IDE coding style - [EditorConfig](https://editorconfig.org/)
- Logo skeleton - made by [Freepik](http://www.freepik.com) from [www.flaticon.com](https://www.flaticon.com/) is 
licensed by [CC 3.0 BY](http://creativecommons.org/licenses/by/3.0/)

## Contributing
Want to contribute? All contributions are welcome. Read the [contributing guide](CONTRIBUTING.md).

## Questions
If you have questions tweet me at [@SandroMiguel77](https://twitter.com/SandroMiguel77) or [open an issue](https://github.com/SandroMiguel/react-sceleto/issues/new).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

**~ sharing is caring ~**
