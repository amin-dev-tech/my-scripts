# My Scripts

A collection of useful scripts for various purposes, including automation and development tasks.

## Table of Contents

- [My Scripts](#my-scripts)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
    - [Bash Scripts Description](#bash-scripts-description)
      - [create-sass](#create-sass)
  - [Usage](#usage)
    - [Bash Scripts Usage](#bash-scripts-usage)
  - [Folder Structure](#folder-structure)
    - [1. Bash Scripts](#1-bash-scripts)
  - [Contributing](#contributing)
  - [License](#license)

## Description

This repository contains a set of scripts to streamline various tasks. The scripts are organized by language, e.g. bash scripts stored in the `bash` folder, Python sctipts will be stored in the `python` folder etc. The scripts are already executable so you only need to run the scripts.

### Bash Scripts Description

#### create-sass

This script will generate base SASS folder structure including the necessary `.sass` files with a basic SASS code inside each for a SASS project.

The script will generate the following structure:

- **`styles/`**
  - **`abstracts/`**
    - **`_functions.scss`**
    - **`_mixins.scss`**
    - **`_variables.scss`**
  - **`base/`**
    - **`_animations.scss`**
    - **`_base.scss`**
    - **`_typography.scss`**
    - **`_utilities.scss`**
  - **`components/`**
    - **`_btn.scss_`**
    - **`_nav.scss`**
  - **`layouts/`**
    - **`_footer.scss`**
    - **`_header.scss`**
  - **`pages/`**
    - **`_home.scss`**
  - **`themes/`**
  - **`utilities/`**
  - **`vendors/`**
  - **`main.scss`**

## Usage

### Bash Scripts Usage

Simply copy the desired script into `usr/local/bin` and rin the bashe command according to the script file name.

Example:

```bash
create-sass
```

This will generate the necessary folders and files for a basic SASS project.

## Folder Structure

The repository is organized with a clear structure to accommodate scripts in different languages. Below is an overview of the current organization:

### 1. Bash Scripts

- **`bash/`**: Houses all bash scripts.
  - **`create_sass`**: Bash script that generates a complete SASS folder structure with basic SASS code.

## Contributing

Your contributions are welcome and encouraged! If you have ideas for new scripts, improvements to existing ones, or general suggestions, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/new-script`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add new script'`)
5. Push to the branch (`git push origin feature/new-script`)
6. Open a Pull Request

Your pull requests will be reviewed, and upon approval, they will be merged into the main branch. Thank you for contributing!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

The MIT License is a permissive open-source license that allows you to use, modify, and distribute the code with very few restrictions. Feel free to incorporate these scripts into your projects and build upon them. If you have any questions about the license, please
