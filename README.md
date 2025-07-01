<div align="center">
<img src="logo.png" height="90px" width="auto" /> 
<h2>
    <em>Minimalist Résumé</em> designed for web and PDF
</h2>
<p>
CV JSON schema from <a href="https://jsonresume.org/schema/">jsonresume.org</a>
</p>

<p>
Based on the design by <a href="https://github.com/BartoszJarocki/cv">Bartosz Jarocki</a>
</p>
</div>

<div align="center">
    <a href="#🚀-getting-started">
        Getting Started
    </a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="#🧞-commands">
        Commands
    </a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="#🔑-license">
        License
    </a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="https://midu.dev">
        Personal
    </a>
</div>

<p></p>

<div align="center">

![Astro Badge](https://img.shields.io/badge/Astro-BC52EE?logo=astro&logoColor=fff&style=flat)
![GitHub stars](https://img.shields.io/github/stars/midudev/minimalist-portfolio-json)
![GitHub issues](https://img.shields.io/github/issues/midudev/minimalist-portfolio-json)
![GitHub forks](https://img.shields.io/github/forks/midudev/minimalist-portfolio-json)
![GitHub PRs](https://img.shields.io/github/issues-pr/midudev/minimalist-portfolio-json)

</div>

<img src="portada.png"></img>

## 🛠️ Stack

- [**Astro**](https://astro.build/) - The web framework for the new era.
- [**Typescript**](https://www.typescriptlang.org/) - JavaScript with type syntax.
- [**Ninja Keys**](https://github.com/ssleptsov/ninja-keys) - Dropdown menu with keyboard shortcuts made in pure JavaScript.

## 🚀 Getting Started

### 1. Use this [repo](https://github.com/midudev/minimalist-portfolio-json) as an Astro project _template_

- I use [pnpm](https://pnpm.io/installation) as a dependency manager and packager.

```bash
# Enable pnpm on MacOS, WSL & Linux:
corepack enable
corepack prepare pnpm@latest --activate

# Initialize the project
pnpm create astro@latest -- --template midudev/minimalist-portfolio-json
```

### 2. Add your content:

Edit the `cv.json` file to create your own printable Portfolio/CV.

### 3. Start the development server:

```bash
# Enjoy the result
pnpm dev
```

1. Open [**http://localhost:4321**](http://localhost:4321/) in your browser to see the result 🚀

## 🧞 Commands

|     | Command          | Action                                                                  |
| :-- | :--------------- | :---------------------------------------------------------------------- |
| ⚙️  | `dev` or `start` | Launches a local development server at `localhost:4321`.                |
| ⚙️  | `build`          | Checks for possible errors and creates a production build in `./dist/`. |
| ⚙️  | `preview`        | Local preview at `localhost:4321`                                       |

## 🔑 License

[MIT](LICENSE.txt) - Created by Me. Inspired by [**midudev**](https://midu.dev).
