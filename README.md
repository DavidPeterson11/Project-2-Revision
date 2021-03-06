# Project-2-Revision
This is a revision of project 2 and should run smoothly and properly.

title: "Project 2"
author: "Annie Kelly and David Peterson"
date: "11/18/2021"
output: html_document
---

## Table of Contents
1. [General Info](#general-info)
2. [Instructions](#installation)
3. [Collaboration](#collaboration)

### General Info
***
Our Project Two downloaded and used the Womanfertility.csv. This data set studies the fertility of women of different countries over the years from 1799. We specifically subsetted the data of the fertility of women from the United States. We created a scatterplot with ggplot2; this highlighted the United States'  fertility in blue, with the other countries in gray. The functions take the data from the data set, and compile them under what our specific interests are when we are looking for the fertilities of the country. We created a loop that is an example to count the number of even numbers in a vector, which makes our data more accurate and smaller over time. Also, a for loop was made, which allowed to single out and better study the data, ensuring that it is more accurate and precise. 

## Instructions
***
* Used  library functions to be able to download and use our csv data file.
    ** library(Womenfertility.csv)
* data("Womanfertility") was opened
                                     
* Created the functions to design to plot the women's fertility of the data set Womanfertility:
      ** plot.circ <- function(cutoff){
          Woman.US$fertility.above <- ifelse(Woman.US$fertility > cutoff, 
                                    Woman.US$fertility, NA) 
          data <- cbind(1:5); 
          data1 <- cbind(15:20)
          data2 <- cbind(25:30)

* A for loop was used to repeat the line of code; this loop was:
      ** for (i in 1:nrow(data)) {
            if (i == 1) {
              print("i is 1")
           } else {
              print("i is not 1")
         }
        for (j in 1:nrow(data1)) {
             print(paste("FOR 2: ", j))
        for (k in 1:nrow(data2)) {
            cat(paste("FOR 3: ", k, "\n"))



## Collaboration
***
Annie Kelly and David Peterson collobarated on this project and did this through a GitHub repository.
