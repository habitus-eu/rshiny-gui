![GitHub Actions R-CMD-check](https://github.com/habitus-eu/HabitusGUI/workflows/R-CMD-check-full/badge.svg)
[![codecov](https://codecov.io/gh/habitus-eu/HabitusGUI/branch/main/graph/badge.svg?token=GPRPJ3IXWC)](https://codecov.io/gh/habitus-eu/HabitusGUI)

# HabitusGUI


## 1 How to use app locally without docker

### 1.1 Install app  in R

```
library("remotes")
remotes::install_github("habitus-eu/HabitusGUI")
```

### 1.2 Install required other dependencies

For example, if you want to work with GGIR:

`install.packages("GGIR")`

### 1.3 Load HabitusGUI package

`library("HabitusGUI")`

### 1.4 Specify a directory that has all relevant data in it or in it's sub-directories

`data_dir = "/home/vincent/projects/fontys"`

### 1.5 Launch HabitusGUI app

`HabitusGUI::myApp(homedir=data_dir)`

## 2 How to use app locally with docker

See https://github.com/habitus-eu/HabitusDocker/blob/main/README.md
