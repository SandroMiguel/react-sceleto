<p align="center"><img src="https://i.imgur.com/4D8GNaR.png" alt="React Sceleto" /></p>

# Welcome to React Sceleto

**React Sceleto is the directory structure that I use in my React projects.**

[![license](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](LICENSE)

## How to Use this Template

To start a new project based on this template, follow these steps:

1. Go to the main page of the repository.
2. Click on the "Use this template" button.
3. Follow the instructions on the page to create a new repository based on this template.
4. Start working on your new project!
5. After creating your new project, don't forget to update the README with relevant information about your project. This will help others understand what your project is about and how to use it.

## Directory structure

```
your-react-app/
├── public/
│   ├── ...
│
├── src/
│   ├── pages/
│   │   ├── index.js
│   │   ├── [SomePage]/
│   │   |   ├── index.js
│   │   |   ├── [SomePage].js
│   │   |   └── [SomePage].scss
│   │   |
│   │   ├── [OtherPage]/
│   │   |   ├── index.js
│   │   |   ├── [OtherPage].js
│   │   |   └── [OtherPage].scss
│   │   ├── ...
│   │
│   ├── components/
│   │   ├── index.js
│   │   ├── [SomeComponent]/
│   │   |   ├── index.js
│   │   |   ├── [SomeComponent].js
│   │   |   └── [SomeComponent].scss
│   │   |
│   │   ├── [OtherComponent]/
│   │   |   ├── index.js
│   │   |   ├── [OtherComponent].js
│   │   |   └── [OtherComponent].scss
│   │   ├── ...
│   │
│   ├── appComponents/
│   │   ├── index.js
│   │   ├── [SomeComponent]/
│   │   |   ├── index.js
│   │   |   ├── [SomeComponent].js
│   │   |   └── [SomeComponent].scss
│   │   |
│   │   ├── [OtherComponent]/
│   │   |   ├── index.js
│   │   |   ├── [OtherComponent].js
│   │   |   └── [OtherComponent].scss
│   │   ├── ...
│   │
│   ├── hooks/
│   │   ├── index.js
│   │   ├── use[SomeHook].js
│   │   ├── ...
│   │
│   ├── config/
│   │   ├── routes.js
│   │   ├── ...
│   │
│   ├── context/
│   │   ├── [someContext]/
│   │   ├── ...
│   │
│   ├── assets/
|   │   ├── images/
|   │   │   ├── index.js
|   │   │   ├── [some-image].png
|   │   │   ├── [some-image].svg
|   │   │   ├── ...
|   │   │
|   │   └── styles/
|   │       ├── theme.css
|   │       └── shared.module.scss
│   │
│   ├── utils/
│   │   ├── [someUtil].js
│   │   ├── ...
│   │
│   └── index.js
│
├── .gitignore
├── .editorconfig
├── .eslintrc.js
├── package.json
├── LICENSE
├── README.md
├── yarn.lock
└── AppRoutes.js
```

## Files and Folders

Overview of files and folders.

| File/Folder                                            | Description                                            |
| ------------------------------------------------------ | ------------------------------------------------------ |
| **public/**                                            | Build output folder                                    |
| **src/**                                               | The source code of the application                     |
| src/**pages/**                                         | Application pages                                      |
| src/pages/**index.js**                                 | Exports all pages                                      |
| src/pages/**SomePage/**                                | Example folder for an application page                 |
| src/pages/SomePage/**index.js**                        | Re-exports the component                               |
| src/pages/SomePage/**SomePage.js**                     | Example file for an application page                   |
| src/pages/SomePage/**SomePage.scss**                   | CSS file for SomePage.js                               |
| src/**components/**                                    | Reusable React components                              |
| src/components/**index.js**                            | Exports all components                                 |
| src/components/**SomeComponent/**                      | Example folder for a React component                   |
| src/components/SomeComponent/**index.js**              | Re-exports the component                               |
| src/components/SomeComponent/**SomeComponent.js**      | Example file for a React component                     |
| src/components/SomeComponent/**SomeComponent.scss**    | CSS file for SomeComponent.js                          |
| src/**appComponents/**                                 | Application-specific React components                  |
| src/appComponents/**index.js**                         | Exports all components                                 |
| src/appComponents/**SomeComponent/**                   | Example folder for an application-specific component   |
| src/appComponents/SomeComponent/**index.js**           | Re-exports the component                               |
| src/appComponents/SomeComponent/**SomeComponent.js**   | Example file for an application-specific component     |
| src/appComponents/SomeComponent/**SomeComponent.scss** | CSS file for SomeComponent.js                          |
| src/**hooks/**                                         | Custom hooks                                           |
| src/hooks/**index.js**                                 | Exports all custom hooks                               |
| src/hooks/**useSomeHook.js**                           | Example custom hook                                    |
| src/**config/**                                        | Configurations                                         |
| src/config/**routes.js**                               | React Router routes                                    |
| src/**context/**                                       | Global state management for React app                  |
| src/context/**someContext**                            | Example folder for specific context management         |
| src/**assets/**                                        | Static resources (e.g. images, PDFs, stylesheets, etc) |
| src/assets/images/**index.js**                         | Exports all images                                     |
| src/assets/images/**some-image.png**                   | Example image file                                     |
| src/assets/**styles/**                                 | CSS styles                                             |
| src/assets/styles/**theme.css**                        | Application-wide theme configuration.                  |
| src/assets/styles/**shared.module.scss**               | Shared styles across components                        |
| src/**utils/**                                         | Helper files (e.g. error handlers, formatters, etc)    |
| src/utils/**someUtil.js**                              | Example utility file                                   |
| src/**index.js**                                       | JavaScript entry point for the application             |
| **.gitignore**                                         | Files and directories that Git should ignore           |
| **.editorconfig**                                      | IDE coding style                                       |
| **.eslintrc.js**                                       | ESLint configuration                                   |
| **package.json**                                       | Package configuration                                  |
| **LICENSE**                                            | License document                                       |
| **README.md**                                          | This document                                          |
| **yarn.lock**                                          | Dependencies information for Yarn                      |
| **AppRoutes.js**                                       | Application routes                                     |

## Credits

- Linting - [ESLint](https://eslint.org/)
- Javascript specs - [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
- IDE coding style - [EditorConfig](https://editorconfig.org/)
- Logo skeleton - made by [Freepik](http://www.freepik.com) from [www.flaticon.com](https://www.flaticon.com/) is
  licensed by [CC 3.0 BY](http://creativecommons.org/licenses/by/3.0/)

## Contributing

Want to contribute? All contributions are welcome. Read the [contributing guide](CONTRIBUTING.md).

## Questions

If you have questions tweet me at [@sandro_m_m](https://twitter.com/sandro_m_m) or [open an issue](https://github.com/SandroMiguel/react-sceleto/issues/new).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

**~ sharing is caring ~**
