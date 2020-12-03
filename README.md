<p align="center"><img src="https://i.imgur.com/4D8GNaR.png" alt="React Sceleto" /></p>

# Welcome to React Sceleto

**React Sceleto is the directory structure that I use in my React projects.**

[![license](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](LICENSE)

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
│   │   |   └── [SomePage].css
│   │   |
│   │   ├── [OtherPage]/
│   │   |   ├── index.js
│   │   |   ├── [OtherPage].js
│   │   |   └── [OtherPage].css
│   │   |
│   │   ├── ...
│   │
│   ├── components/
│   │   ├── index.js
│   │   ├── [SomeComponent]/
│   │   |   ├── index.js
│   │   |   ├── [SomeComponent].js
│   │   |   └── [SomeComponent].css
│   │   |
│   │   ├── [OtherComponent]/
│   │   |   ├── index.js
│   │   |   ├── [OtherComponent].js
│   │   |   └── [OtherComponent].css
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
│   ├── assets/
|   │   ├── images/
|   │   │   ├── index.js
|   │   │   ├── [some-image].png
|   │   │   ├── [some-image].svg
|   │   │   ├── ...
|   │   │
|   │   └── styles/
|   │       ├── app.css
|   │       ├── shared.css
|   │       └── shared-colors.css
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
└── yarn.lock
```

## Files and Folders

Files and folders overview.

| File/Folder                                        | Description                                            |
| -------------------------------------------------- | ------------------------------------------------------ |
| **public/**                                        | Build output folder                                    |
| **src/**                                           | The source code of the application                     |
| src/**pages/**                                     | Application pages                                      |
| src/pages/**index.js**                             | Exports all pages                                      |
| src/pages/**SomePage/**                            | Application page folder example                        |
| src/pages/SomePage/**index.js**                    | Re-exports the component                               |
| src/pages/SomePage/**SomePage.js**                 | Application page file example                          |
| src/pages/SomePage/**SomePage.css**                | CSS file for SomePage.js                               |
| src/**components/**                                | React components                                       |
| src/components/**index.js**                        | Exports all components                                 |
| src/components/**SomeComponent/**                  | React component folder example                         |
| src/components/SomeComponent/**index.js**          | Re-exports the component                               |
| src/components/SomeComponent/**SomeComponent.js**  | React component file example                           |
| src/components/SomeComponent/**SomeComponent.css** | CSS file for SomeComponent.js                          |
| src/**hooks/**                                     | Custom hooks                                           |
| src/hooks/**index.js**                             | Exports all custom hooks                               |
| src/hooks/**useSomeHook.js**                       | Custom hook example                                    |
| src/**config/**                                    | Configurations                                         |
| src/config/**routes.js**                           | React Router routes                                    |
| src/**assets/**                                    | Static resources (e.g. images, pdf, stylesheets, etc.) |
| src/assets/images/**index.js**                     | Exports all images                                     |
| src/assets/images/**some-image.png**               | Image file example                                     |
| src/assets/**styles/**                             | CSS styles                                             |
| src/assets/styles/**app.css**                      | Global app styles                                      |
| src/assets/styles/**shared.css**                   | Shared styles (e.g. typography)                        |
| src/assets/styles/**shared-colors.css**            | Shared colors                                          |
| src/**utils/**                                     | Helper files (e.g. error handlers, formatters, etc.)   |
| src/utils/**someUtil.js**                          | Util file example                                      |
| src/**index.js**                                   | JS entry point for the application                     |
| **.gitignore**                                     | Files and directories that Git should ignore           |
| **.editorconfig**                                  | IDE coding style                                       |
| **.eslintrc.js**                                   | ESLint configuration                                   |
| **package.json**                                   | Package configuration                                  |
| **LICENSE**                                        | License document                                       |
| **README.md**                                      | This document                                          |
| **yarn.lock**                                      | Dependencies information for Yarn                      |

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
