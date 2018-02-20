---
title: Template Chapter 1
description: >-
  This is a template chapter.


---
## Calcula la media

```yaml
type: NormalExercise
lang: r
xp: 100
skills: 1
key: 64df524271
```

Para calcular la media solo tienes que utilizar la función c(), asignar ese vector a la variable x  y usar la variable .

`@instructions`
Compone los 5 datos  { 2, 3, 4, 5, 6}  con la función que concatena c(2, 3, 4, 5, 6) y asigna el resultado a la variable x con el operador  <- , utiliza la funcion mean(x) para conseguir la media

`@hint`



`@sample_code`
```{r}
# vamos a calcular la media de 5 datos {2, 3, 4, 5, 6}
```
`@solution`
```{r}
x<-c(2,3,4,5,6)
mean(x)
```





