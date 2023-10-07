## Trabajo-grupal-Rodriguez-y-Ospina
Jahaira Rodriguez Orué (20201405) Fiorella Ospina Lugo (20211253)


```{r}
library(rio)
data<-import("Variables independientes (1).xlsx")
```

# Diccionario de códigos
Nivel de ingresos (Income group)
* Low income --> Ingreso nacional bruto per cápita de $1,135 o menos 
* Lower middle income --> Ingreso nacional bruto per cápita de $1,136 a $4,465 
* Upper middle income --> Ingreso nacional bruto per cápita de $4,466 a $13,845
* High income --> Ingreso nacional bruto per cápita de $13,846 o más

Nivel de desigualdad económica (Tasa de incidencia de pobreza)
* Va del 0% al 100%, donde el porcentaje que reciba el país significa el porcentaje de la población que vive por debajo del umbral de pobreza

Grado de libertad de prensa (Puntuacion global de libertad de prensa en %)
* Va del 0% al 100%

# Links de la data
* Nivel de ingresos --> https://datatopics.worldbank.org/world-development-indicators/the-world-by-income-and-region.html 
* Nivel de desigualdad económica --> https://www.bancomundial.org/es/topic/poverty/lac-equity-lab1/income-inequality/inequality-trends
* Grado de libertad de prensa --> https://rsf.org/es/clasificacion
