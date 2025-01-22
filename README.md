# Repository Purpose

One of the new things I know is GitHub Actions. GitHub Actions is able to automate certain commands. This repository can compile your LaTeX file into a PDF using GitHub Actions. In this repository, we use **push every time** to identify the LaTeX file.

To work with this repository, you just need to add your LaTeX file, create a special tag for your changes, and push it to the repository.

## How to Use

To use this repository, follow these steps:

1. Create a repository.
2. Clone it to your machine.
3. Add your LaTeX file to the repository.
4. Modify the `main.yml` file to be able to compile your LaTeX file (change only the parts that relate to your LaTeX file, not the general operations).
5. Push the tags.
6. After the workflow, your LaTeX file will be released in the "Release" section.
7. After any changes, follow the steps starting from number 5.