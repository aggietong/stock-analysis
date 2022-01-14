# Challenge #2 (UTOR-VIRT-DATA-PT-12-2021-U-B)
# Student: Agnes Tong

# An Analysis of Stocks 

## Overview of Project 

Steve’s parents have recently invested their money into green energy DAQO (“DQ”). Steve is looking into 2017 and 2018 green energy stock data to help his parents diversify their investments if necessary. Additionally, Steve wants to expand the analysis to include all stocks in the stock market over the last few years. 
The purpose of this exercise was to refactor the original VBA code for stock analysis, so that the code becomes much more efficient if more data is included in the future. The goal of the analysis is to provide the total volume and return rate for each stock. 

## Results

### 1. Analysis of Stock Performance 

The 2017 shows that all twelve stocks with the exception of TERP had positive returns, whereas only two of the twelve stocks had a positive return. The DQ stock in particular had a 199% positive return in 2017, but had a -62.6% return in 2018. By the end of 2018, the best performing stock was RUN, with a 1414% increase in returns between the two years. The worst performing stock was SPWR, with a 293% decrease in returns between 2017 and 2018. 

### 2. Execution Times

The execution times improved significantly for the refactored code. For 2017, execution time decreased from 1.04 seconds to 0.22 seconds. For 2018 data, execution time decreased from 0.88 seconds to 0.22 seconds. 

Execution Times for the Original Code

Execution Times for Refactored Code 

## Summary

Refactoring is intended to improve a programming code’s design, structure, and performance. From a design and structure perspective, refactoring helps to reduce complexity and improve functionality, readability, maintainability, and extensibility. A refactored code may improve performance, so that the program performs faster or use less memory. One of the disadvantages is that it may take a long time to complete the refactoring process. For example, if there is a tight timeline to turn around a programming code, and the analysis will only be done infrequently on a small dataset, refactoring may not be worth the time and effort. 
