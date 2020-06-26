# MHL Thesis Latex Template
The Thesis Latex template used by the Microprocessor & Hardware Lab of Technical University of Crete.

A copy of this template on [Overleaf](https://www.overleaf.com/) can be found [here](https://www.overleaf.com/read/pdmwvypmttkc).

# Offline compilation
Firstly, clone this repository.
```
$ git clone https://github.com/TFotakis/MHL-Latex-Template.git
```

To push it to your repository, first change the origin url and then push it.
```
$ git remote set-url origin http://github.com/YOU/YOUR_REPO
$ git push
```

Or, you can fork this repository and clone it directly from your own.
```
$ git clone http://github.com/YOU/MHL-Latex-Template.git
```

This latex template can be compiled offline with the use of some tools.

## Editing
Any text editor can be used for editing this template, however [VS Code](https://code.visualstudio.com/) comes with the [Latex Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension, which can automate the compilation procedure.

Simply install [VS Code](https://code.visualstudio.com/) and afterwards install [Latex Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) from VS Code's extensions tab. Latex Workshop is just a LaTeX front-end, hence a TeX distribution is needed for compiling the LaTeX source.

## Compiling
For LaTeX compilation a LaTeX distribution is needed. This template is tested using the [TeX Live](https://www.tug.org/texlive/), which is also the recommended distribution. Note that installing TexLive requires some time and a decent internet connection.

### Windows
- Download the [TeX Live Manager](https://www.tug.org/texlive/acquire-netinstall.html) (select install-tl-windows.exe). Install it by selecting "More info" on the "Windows Defender" warning message, and then "Run anyway".
- After the installation is completed, open the TeX Live Manager app from your Start Menu and install all packages.
### Linux
- Arch Linux: download the packages *texlive-most* and *biber* from you package manager (e.g. pacman, yay, etc).
```
$ sudo pacman -S texlive-most biber
```

- Ubuntu Linux (and other debian based): download the packages *texlive-full* and *biber* from you package manager (e.g. apt).
```
$ sudo apt install texlive-full biber
```

- Other distros: There is a high chance the aforementioned packages to exist in your distro's repositories, so search for them using your package manager, or visit [TeX Live](https://www.tug.org/texlive/) for installation instructions.
