# alpine-latex
Docker image for building latex documents

## Requirements
You should add your current user to docker group.

    sudo usermod -aG docker username

It will use user and group id to compile latex documents

## Usage
Download `latexdockercmd.sh` script to your latex project directory

    wget https://raw.githubusercontent.com/dovydasvenckus/alpine-latex/master/latexdockercmd.sh

Make it executable

    chmod +x latexdockercmd.sh

Execute desired latex command with your source

    ./latexdockercmd.sh pdflatex document.tex

## License
[MIT](https://github.com/dovydasvenckus/alpine-latex/blob/master/LICENSE)

This project is based on [latex-docker](https://github.com/blang/latex-docker)
project which is licensed under MIT license.
