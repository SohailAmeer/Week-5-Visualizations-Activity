# Week-5-Visualizations-Activity-
Visualization of Bad Drivers Dataset


---
title: "Week 5 Visualizations Activity"
author: Mohammed Sohail Ameer
output: html_document
date: "2022-09-24"
---

```{r}
drivers_data <- read.csv("bad-drivers.csv")
drivers_data
```

```{r}
hist(drivers_data$Number.of.drivers.involved.in.fatal.collisions.per.billion.miles, col="darkred")
```
```{r}
barplot(colSums(drivers_data[,3:6]))
```

