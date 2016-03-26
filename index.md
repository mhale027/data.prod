---
title       : EPA MPG database
subtitle    : 
author      : Matt Hale
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---



## Finding the right vehicle can be a read drag.

1. Dozens of makes, hundreds of models, where do I start?
2. Does an electric car meet my daily driving needs?
3. How much displacement do I really need?
4. Does driving a Hybrid really lead to low levels of satisfaction in life?

* These are life's tough questions, folks, and some of them can be answered with this app.

--- .class #id 

## Features

* Easily(ish) sort through all cars in the database to fit your needs.
* Refine the list by:
    + Combined MPG
    + Fuel type: Electricity, gas, hybrid
    + Drive type: Front, rear, or all wheel drive
    + Vehicle type: Car, pickup, SUV
    + Year and some popular makes
* Sort the list by column to see specific features' max and min.

--- .class #id

## Purpose

* This app allows the user to create a detailed list of all vehicles reported on by the EPA, and to then subset that list
to find the vehilces that meet the individual needs selected.

* Narrow down each field with the widgets on the side panel on the left and watch the selection of 33141 vehicles drop down to a more manageable field.

* Year range from 1984 to 2017
* MPG range from 7 to 89.971
* Fuel type selection from Gasoline, Diesel, Natural Gas, Hybrid, Flex-Fuel
* Vehicle types selection from Coupe/Sedan, Minivan, Wagon, Pickup, SUV
* Popular makes like Acura, Alfa Romeo, AM General, Aston Martin, Audi, Bentley, Bugatti, Buick, Cadillac, Chevrolet, Chrysler, Daewoo, Dodge, Eagle, Fiat


--- .class #id

## Special Thanks

* This app is only possible thanks to the kind ladies and gents of the US Environmental Protection Agency.

* The raw dataset is available [here]("https://www.fueleconomy.gov/feg/download.shtml").


