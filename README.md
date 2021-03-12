# TemplateBeamer
A template for beamer presentation (LaTeX).

## Dependencies
* [listings v1.8](https://www.ctan.org/pkg/listings)

## Usage

To use the template, you just need to add this line after the documentclass definition:

```
\usepackage{beamer-package}
```


## Block

I implemented 2 types of blocks:

### Text

```
\begin{Text}{Title}
    ...
\end{Text}
```

```
\begin{TextColor}{Title}{Color}
    ...
\end{TextColor}
```

### Code

```
\begin{CodeListings}{Language}
    ...
\end{CodeListings}
```


## Image and List

### Image

```
\image{Path}{Title}
```

### List

```
\begin{List}{Color}
    ...
    \item
    ...
\end{List}
```

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)