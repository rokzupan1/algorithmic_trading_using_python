# Course Overview

## 1, Algorithmic Trading Basics
**Algorithmic trading** means using computer to make investment decisions. There are many different types of algorithmic trading. The main difference is their speed of execution. Here are some of the main players in the algorithmic trading landscape:
* Renaissance Technologies: $165B in AUM
* AQR Capital Management: $61B in AUM
* Citadel Securities: $32B in AUM

**Python** is the most popular programming language for algorithmic trading (lot of libraries). However, Python is slow. This means that it is often used as a "glue language" to trigger code that runs in other languages. One example of this is the NumPy library for Python, which we'll be using in this course. It is the most popular Python library for performing numerical computing. Although it's written for use in Python, NumPy underlying functionality is written as such faster language.

The Algorithmic Trading Process:
The process of running a quantitative investing strategy can be broken down into the following steps:
1. Collect data
2. Develop a hypothesis for a strategy
3. Backtest that strategy
4. Implement the stategy in production

Because this is an introductory course, it will differ drom production alogrithmic trading in 3 major ways: 
1. We'll be using random data
2. We will not be executing trades
3. We will be saving recommended trading tricks files

## 2. API Basics and Course Configuration
An API is an Application Programming Interface. API allow you to interact with someone else's software using your own code. In this course we'll be using the IEX Cloud API to gather stock market data to make investment decisions. We will be using GET requests ti gather data from IEX Cloud API. With that said, there are many other ways to interact with an API. 

* POST: Adds data to the database exposed by the APIS. (Create only)
* PUT: Adds and overwrites data in the database exposed by the API. (Create or replace).
* DELETE: Deletes data from the API's database

## 3. Project 1: Equal-Weight S&P 500 Screener
The S&P 500 is the world's most popular stock market index. If you own this fund you own 500 largest companies in the US. This index is market capitalization-weighted. This means that larger companies get a correspondingly larger weight in the index. In the first project of this course, we will build an alternative version of the S&P 500 Index fund where each company has the same weighting. 

## 4. Project 2: Quantitative Momentum Screener
Momentum investing means investing in assets that have increased in price the most.

## 5. Project 3: Quantitatve Value Screener
Value investing means investing in stocks that are trading below their perceived intrinsic value. Creating algorithmic value investing strategies relies on a concept called multiples. Multiples are calculated by dividing a company's stock price by some measure of the company's worth - like earnings or assets. Here are a few examples of common multiple used in value investing:
* Price-to-earnings
* Price-to-book-value
* Price-to-free-cash-flow
Each of the individual multiples used by value investors has its pros and cons. One way to minimize the impact of any specific multiple is by using a composite. We'll use a composite of 5 different value investing metrics in our strategy.



