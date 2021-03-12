# TemplateBeamer
A template for beamer presentation (LaTeX).

## Dependencies
* [listings v1.8](https://www.ctan.org/pkg/listings)

## Usage

To use the template, you just need to add this line after the documentclass definition:

```
\usepackage{beamer-package}
```

## Image

![Title Frame](https://github.com/Atlanta53/TemplateBeamer/blob/main/res/titlepage.PNG)
![Section Frame](https://github.com/Atlanta53/TemplateBeamer/blob/main/res/sectionpage.PNG)
![Frame](https://github.com/Atlanta53/TemplateBeamer/blob/main/res/page.PNG)

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

> If you want to use the code block, you will need to add the parameter `fragile` in the frame.
> For example : `begin{frame}[fragile]`

```
\begin{CodeListings}{Title}{Language}
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