---
title       : Research Plan
subtitle    : QAS PhD Program
author      : Juan-Carlos Quiroz
job         : September, 2014
framework   : io2012                                            # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js                                      # {highlight.js, prettify, highlight}
hitheme     : tomorrow                                          # 
widgets     : [bootstrap, quiz, interactive, shiny]             # {mathjax, quiz, bootstrap} , interactive
mode        : selfcontained                                     # {standalone, draft}
knit        : slidify::knit2slides
logo        : aad.png
biglogo     : utas.jpg
license     : by-nc-sa
ext_widgets : {rCharts: [libraries/nvd3]}
runtime     : shiny
---

--- .quote .smaller

![img](images/c1.png)
<div style="text-align:center">
<img src="images/hr.png" alt="rule" style="width: 450px;"/>
</div>
&nbsp; 
>__Supervisors:__ &nbsp;
&nbsp;   
&nbsp; 
>  - Klaas Hartmann (IMAS)
>  - Caleb Gardner (IMAS)
>  - Dirk Welsford (AAD)
>  - Philippe Ziegler (AAD)
>  - Paul Burch (IMAS - AAD)


--- .segue .nobackground .dark

## Chapter 1

--- .middle  .smaller

<a class='example'>Chapter 1</a>

## Background

__Objetives__:
  * to review, discuss and expound the different TOP management process implemented worldwide
      - <span style="color:red; font-family:Georgia; font-size:1em;">Chapter 2</span>
  * to test the suitability of improve the actual modelling framework of TOP utilized in Kerguelen Plateau and South-America
      - <span style="color:red; font-family:Georgia; font-size:1em;">Chapter 3 & 4</span>
  * to develop a robust MSE approach of TOP consistent with the modelling improvements identified in Kerguelen Plateau and South-America
      - <span style="color:red; font-family:Georgia; font-size:1em;">Chapter 5</span>
  * to examine how the actual harvest policies implemented in Kerguelen Plateau and South-America influences the effectiveness of fishery management on TOP
      - <span style="color:red; font-family:Georgia; font-size:1em;">Chapter 5</span>
      

--- .segue .nobackground .dark

## Chapter 2

--- .middle .smaller

<a class='example'>Chapter 2</a>

## TOP fishery in South-America: Drawing lesson from others Toothfish fisheries
&nbsp;

> - Second major catch area worldwide
>     + <span style="color:green; font-family:Georgia; font-size:1em;">_Brief description of fishery_</span>
> - Management mechanism appears untransparent and inconsistent
>     + <span style="color:green; font-family:Georgia; font-size:1em;">e.g. _Time line of **TAC's** criteria_</span>
> - Recently changes in Fishery Act
>     + <span style="color:green; font-family:Georgia; font-size:1em;">e.g. _by-catch is 'legal'_</span>
> - Explicit management objectives established in 2013 (Chilean case)
>     + <span style="color:green; font-family:Georgia; font-size:1em;">e.g. _MSY-based Reference Points. Pathways?_</span>

--- .middle .smaller

<a class='example'>Chapter 2</a>

## Catches by area
&nbsp;


<div id = 'chart2' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchart2()
    });
    function drawchart2(){  
      var opts = {
 "dom": "chart2",
"width":    800,
"height":    400,
"x": "year",
"y": "C",
"group": "FAO",
"type": "stackedAreaChart",
"id": "chart2" 
},
        data = [
 {
 "FAO": 41,
"year": 1977,
"TOTAL": 25,
"C": 655 
},
{
 "FAO": 41,
"year": 1978,
"TOTAL": 25,
"C": 39 
},
{
 "FAO": 41,
"year": 1979,
"TOTAL": 25,
"C": 64 
},
{
 "FAO": 41,
"year": 1980,
"TOTAL": 25,
"C": 388 
},
{
 "FAO": 41,
"year": 1981,
"TOTAL": 25,
"C": 409 
},
{
 "FAO": 41,
"year": 1982,
"TOTAL": 25,
"C": 54 
},
{
 "FAO": 41,
"year": 1983,
"TOTAL": 25,
"C": 152 
},
{
 "FAO": 41,
"year": 1984,
"TOTAL": 25,
"C": 70 
},
{
 "FAO": 41,
"year": 1985,
"TOTAL": 25,
"C": 195 
},
{
 "FAO": 41,
"year": 1986,
"TOTAL": 25,
"C": 157 
},
{
 "FAO": 41,
"year": 1987,
"TOTAL": 25,
"C": 532 
},
{
 "FAO": 41,
"year": 1988,
"TOTAL": 25,
"C": 936 
},
{
 "FAO": 41,
"year": 1989,
"TOTAL": 25,
"C": 1550 
},
{
 "FAO": 41,
"year": 1990,
"TOTAL": 25,
"C": 2380 
},
{
 "FAO": 41,
"year": 1991,
"TOTAL": 25,
"C": 2234 
},
{
 "FAO": 41,
"year": 1992,
"TOTAL": 25,
"C": 1321 
},
{
 "FAO": 41,
"year": 1993,
"TOTAL": 25,
"C": 5002 
},
{
 "FAO": 41,
"year": 1994,
"TOTAL": 25,
"C": 12719 
},
{
 "FAO": 41,
"year": 1995,
"TOTAL": 25,
"C": 19442 
},
{
 "FAO": 41,
"year": 1996,
"TOTAL": 25,
"C": 15079 
},
{
 "FAO": 41,
"year": 1997,
"TOTAL": 25,
"C": 9635 
},
{
 "FAO": 41,
"year": 1998,
"TOTAL": 25,
"C": 13359 
},
{
 "FAO": 41,
"year": 1999,
"TOTAL": 25,
"C": 11340 
},
{
 "FAO": 41,
"year": 2000,
"TOTAL": 25,
"C": 11128 
},
{
 "FAO": 41,
"year": 2001,
"TOTAL": 25,
"C": 13823 
},
{
 "FAO": 41,
"year": 2002,
"TOTAL": 25,
"C": 12488 
},
{
 "FAO": 41,
"year": 2003,
"TOTAL": 25,
"C": 8871 
},
{
 "FAO": 41,
"year": 2004,
"TOTAL": 25,
"C": 6671 
},
{
 "FAO": 41,
"year": 2005,
"TOTAL": 25,
"C": 4917 
},
{
 "FAO": 41,
"year": 2006,
"TOTAL": 25,
"C": 5899 
},
{
 "FAO": 41,
"year": 2007,
"TOTAL": 25,
"C": 7571 
},
{
 "FAO": 41,
"year": 2008,
"TOTAL": 25,
"C": 5460 
},
{
 "FAO": 41,
"year": 2009,
"TOTAL": 25,
"C": 5396 
},
{
 "FAO": 41,
"year": 2010,
"TOTAL": 25,
"C": 5988 
},
{
 "FAO": 41,
"year": 2011,
"TOTAL": 25,
"C": 7519 
},
{
 "FAO": 41,
"year": 2012,
"TOTAL": 25,
"C": 5210 
},
{
 "FAO": 47,
"year": 1977,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1978,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1979,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1980,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1981,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1982,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1983,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1984,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1985,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1986,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1987,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1988,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1989,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1990,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1991,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1992,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1993,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1994,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1995,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1996,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1997,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1998,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 1999,
"TOTAL": 6,
"C": 0 
},
{
 "FAO": 47,
"year": 2000,
"TOTAL": 6,
"C": 320 
},
{
 "FAO": 47,
"year": 2001,
"TOTAL": 6,
"C": 5 
},
{
 "FAO": 47,
"year": 2002,
"TOTAL": 6,
"C": 924 
},
{
 "FAO": 47,
"year": 2003,
"TOTAL": 6,
"C": 2438 
},
{
 "FAO": 47,
"year": 2004,
"TOTAL": 6,
"C": 728 
},
{
 "FAO": 47,
"year": 2005,
"TOTAL": 6,
"C": 168 
},
{
 "FAO": 47,
"year": 2006,
"TOTAL": 6,
"C": 172 
},
{
 "FAO": 47,
"year": 2007,
"TOTAL": 6,
"C": 192 
},
{
 "FAO": 47,
"year": 2008,
"TOTAL": 6,
"C": 198 
},
{
 "FAO": 47,
"year": 2009,
"TOTAL": 6,
"C": 151 
},
{
 "FAO": 47,
"year": 2010,
"TOTAL": 6,
"C": 82 
},
{
 "FAO": 47,
"year": 2011,
"TOTAL": 6,
"C": 218 
},
{
 "FAO": 47,
"year": 2012,
"TOTAL": 6,
"C": 125 
},
{
 "FAO": 48,
"year": 1977,
"TOTAL": 16,
"C": 502 
},
{
 "FAO": 48,
"year": 1978,
"TOTAL": 16,
"C": 2146 
},
{
 "FAO": 48,
"year": 1979,
"TOTAL": 16,
"C": 363 
},
{
 "FAO": 48,
"year": 1980,
"TOTAL": 16,
"C": 106 
},
{
 "FAO": 48,
"year": 1981,
"TOTAL": 16,
"C": 258 
},
{
 "FAO": 48,
"year": 1982,
"TOTAL": 16,
"C": 354 
},
{
 "FAO": 48,
"year": 1983,
"TOTAL": 16,
"C": 218 
},
{
 "FAO": 48,
"year": 1984,
"TOTAL": 16,
"C": 268 
},
{
 "FAO": 48,
"year": 1985,
"TOTAL": 16,
"C": 530 
},
{
 "FAO": 48,
"year": 1986,
"TOTAL": 16,
"C": 733 
},
{
 "FAO": 48,
"year": 1987,
"TOTAL": 16,
"C": 1953 
},
{
 "FAO": 48,
"year": 1988,
"TOTAL": 16,
"C": 876 
},
{
 "FAO": 48,
"year": 1989,
"TOTAL": 16,
"C": 7060 
},
{
 "FAO": 48,
"year": 1990,
"TOTAL": 16,
"C": 6785 
},
{
 "FAO": 48,
"year": 1991,
"TOTAL": 16,
"C": 1756 
},
{
 "FAO": 48,
"year": 1992,
"TOTAL": 16,
"C": 3839 
},
{
 "FAO": 48,
"year": 1993,
"TOTAL": 16,
"C": 3030 
},
{
 "FAO": 48,
"year": 1994,
"TOTAL": 16,
"C": 658 
},
{
 "FAO": 48,
"year": 1995,
"TOTAL": 16,
"C": 3372 
},
{
 "FAO": 48,
"year": 1996,
"TOTAL": 16,
"C": 3602 
},
{
 "FAO": 48,
"year": 1997,
"TOTAL": 16,
"C": 3812 
},
{
 "FAO": 48,
"year": 1998,
"TOTAL": 16,
"C": 3201 
},
{
 "FAO": 48,
"year": 1999,
"TOTAL": 16,
"C": 3626 
},
{
 "FAO": 48,
"year": 2000,
"TOTAL": 16,
"C": 4939 
},
{
 "FAO": 48,
"year": 2001,
"TOTAL": 16,
"C": 4048 
},
{
 "FAO": 48,
"year": 2002,
"TOTAL": 16,
"C": 5744 
},
{
 "FAO": 48,
"year": 2003,
"TOTAL": 16,
"C": 7528 
},
{
 "FAO": 48,
"year": 2004,
"TOTAL": 16,
"C": 4504 
},
{
 "FAO": 48,
"year": 2005,
"TOTAL": 16,
"C": 3111 
},
{
 "FAO": 48,
"year": 2006,
"TOTAL": 16,
"C": 3654 
},
{
 "FAO": 48,
"year": 2007,
"TOTAL": 16,
"C": 3672 
},
{
 "FAO": 48,
"year": 2008,
"TOTAL": 16,
"C": 3974 
},
{
 "FAO": 48,
"year": 2009,
"TOTAL": 16,
"C": 3473 
},
{
 "FAO": 48,
"year": 2010,
"TOTAL": 16,
"C": 2625 
},
{
 "FAO": 48,
"year": 2011,
"TOTAL": 16,
"C": 1832 
},
{
 "FAO": 48,
"year": 2012,
"TOTAL": 16,
"C": 1868 
},
{
 "FAO": 51,
"year": 1977,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1978,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1979,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1980,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1981,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1982,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1983,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1984,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1985,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1986,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1987,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1988,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1989,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1990,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1991,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1992,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1993,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1994,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1995,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1996,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1997,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1998,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 1999,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 2000,
"TOTAL": 3,
"C": 1628 
},
{
 "FAO": 51,
"year": 2001,
"TOTAL": 3,
"C": 7124 
},
{
 "FAO": 51,
"year": 2002,
"TOTAL": 3,
"C": 4798 
},
{
 "FAO": 51,
"year": 2003,
"TOTAL": 3,
"C": 1112 
},
{
 "FAO": 51,
"year": 2004,
"TOTAL": 3,
"C": 86 
},
{
 "FAO": 51,
"year": 2005,
"TOTAL": 3,
"C": 420 
},
{
 "FAO": 51,
"year": 2006,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 51,
"year": 2007,
"TOTAL": 3,
"C": 31 
},
{
 "FAO": 51,
"year": 2008,
"TOTAL": 3,
"C": 101 
},
{
 "FAO": 51,
"year": 2009,
"TOTAL": 3,
"C": 70 
},
{
 "FAO": 51,
"year": 2010,
"TOTAL": 3,
"C": 136 
},
{
 "FAO": 51,
"year": 2011,
"TOTAL": 3,
"C": 165 
},
{
 "FAO": 51,
"year": 2012,
"TOTAL": 3,
"C": 163 
},
{
 "FAO": 57,
"year": 1977,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1978,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1979,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1980,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1981,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1982,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1983,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1984,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1985,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1986,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1987,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1988,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1989,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1990,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1991,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1992,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1993,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1994,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1995,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1996,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1997,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1998,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 1999,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 2000,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 2001,
"TOTAL": 3,
"C": 450 
},
{
 "FAO": 57,
"year": 2002,
"TOTAL": 3,
"C": 2683 
},
{
 "FAO": 57,
"year": 2003,
"TOTAL": 3,
"C": 1183 
},
{
 "FAO": 57,
"year": 2004,
"TOTAL": 3,
"C": 13 
},
{
 "FAO": 57,
"year": 2005,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 2006,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 2007,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 2008,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 2009,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 2010,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 2011,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 57,
"year": 2012,
"TOTAL": 3,
"C": 0 
},
{
 "FAO": 58,
"year": 1977,
"TOTAL": 13,
"C": 21 
},
{
 "FAO": 58,
"year": 1978,
"TOTAL": 13,
"C": 633 
},
{
 "FAO": 58,
"year": 1979,
"TOTAL": 13,
"C": 32 
},
{
 "FAO": 58,
"year": 1980,
"TOTAL": 13,
"C": 142 
},
{
 "FAO": 58,
"year": 1981,
"TOTAL": 13,
"C": 123 
},
{
 "FAO": 58,
"year": 1982,
"TOTAL": 13,
"C": 138 
},
{
 "FAO": 58,
"year": 1983,
"TOTAL": 13,
"C": 164 
},
{
 "FAO": 58,
"year": 1984,
"TOTAL": 13,
"C": 4738 
},
{
 "FAO": 58,
"year": 1985,
"TOTAL": 13,
"C": 2455 
},
{
 "FAO": 58,
"year": 1986,
"TOTAL": 13,
"C": 2472 
},
{
 "FAO": 58,
"year": 1987,
"TOTAL": 13,
"C": 1819 
},
{
 "FAO": 58,
"year": 1988,
"TOTAL": 13,
"C": 917 
},
{
 "FAO": 58,
"year": 1989,
"TOTAL": 13,
"C": 1348 
},
{
 "FAO": 58,
"year": 1990,
"TOTAL": 13,
"C": 1250 
},
{
 "FAO": 58,
"year": 1991,
"TOTAL": 13,
"C": 3037 
},
{
 "FAO": 58,
"year": 1992,
"TOTAL": 13,
"C": 7758 
},
{
 "FAO": 58,
"year": 1993,
"TOTAL": 13,
"C": 3597 
},
{
 "FAO": 58,
"year": 1994,
"TOTAL": 13,
"C": 5437 
},
{
 "FAO": 58,
"year": 1995,
"TOTAL": 13,
"C": 5711 
},
{
 "FAO": 58,
"year": 1996,
"TOTAL": 13,
"C": 5656 
},
{
 "FAO": 58,
"year": 1997,
"TOTAL": 13,
"C": 8646 
},
{
 "FAO": 58,
"year": 1998,
"TOTAL": 13,
"C": 10168 
},
{
 "FAO": 58,
"year": 1999,
"TOTAL": 13,
"C": 9730 
},
{
 "FAO": 58,
"year": 2000,
"TOTAL": 13,
"C": 11972 
},
{
 "FAO": 58,
"year": 2001,
"TOTAL": 13,
"C": 9098 
},
{
 "FAO": 58,
"year": 2002,
"TOTAL": 13,
"C": 8233 
},
{
 "FAO": 58,
"year": 2003,
"TOTAL": 13,
"C": 8925 
},
{
 "FAO": 58,
"year": 2004,
"TOTAL": 13,
"C": 8776 
},
{
 "FAO": 58,
"year": 2005,
"TOTAL": 13,
"C": 8697 
},
{
 "FAO": 58,
"year": 2006,
"TOTAL": 13,
"C": 8741 
},
{
 "FAO": 58,
"year": 2007,
"TOTAL": 13,
"C": 8345 
},
{
 "FAO": 58,
"year": 2008,
"TOTAL": 13,
"C": 8205 
},
{
 "FAO": 58,
"year": 2009,
"TOTAL": 13,
"C": 8676 
},
{
 "FAO": 58,
"year": 2010,
"TOTAL": 13,
"C": 8486 
},
{
 "FAO": 58,
"year": 2011,
"TOTAL": 13,
"C": 8668 
},
{
 "FAO": 58,
"year": 2012,
"TOTAL": 13,
"C": 8612 
},
{
 "FAO": 81,
"year": 1977,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1978,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1979,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1980,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1981,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1982,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1983,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1984,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1985,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1986,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1987,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1988,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1989,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1990,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1991,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1992,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1993,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1994,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1995,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 1996,
"TOTAL": 2,
"C": 1061 
},
{
 "FAO": 81,
"year": 1997,
"TOTAL": 2,
"C": 5 
},
{
 "FAO": 81,
"year": 1998,
"TOTAL": 2,
"C": 43 
},
{
 "FAO": 81,
"year": 1999,
"TOTAL": 2,
"C": 1 
},
{
 "FAO": 81,
"year": 2000,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 2001,
"TOTAL": 2,
"C": 14 
},
{
 "FAO": 81,
"year": 2002,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 2003,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 2004,
"TOTAL": 2,
"C": 3 
},
{
 "FAO": 81,
"year": 2005,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 2006,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 81,
"year": 2007,
"TOTAL": 2,
"C": 90 
},
{
 "FAO": 81,
"year": 2008,
"TOTAL": 2,
"C": 308 
},
{
 "FAO": 81,
"year": 2009,
"TOTAL": 2,
"C": 746 
},
{
 "FAO": 81,
"year": 2010,
"TOTAL": 2,
"C": 497 
},
{
 "FAO": 81,
"year": 2011,
"TOTAL": 2,
"C": 235 
},
{
 "FAO": 81,
"year": 2012,
"TOTAL": 2,
"C": 386 
},
{
 "FAO": 87,
"year": 1977,
"TOTAL": 2,
"C": 0 
},
{
 "FAO": 87,
"year": 1978,
"TOTAL": 2,
"C": 37 
},
{
 "FAO": 87,
"year": 1979,
"TOTAL": 2,
"C": 120 
},
{
 "FAO": 87,
"year": 1980,
"TOTAL": 2,
"C": 414 
},
{
 "FAO": 87,
"year": 1981,
"TOTAL": 2,
"C": 335 
},
{
 "FAO": 87,
"year": 1982,
"TOTAL": 2,
"C": 607 
},
{
 "FAO": 87,
"year": 1983,
"TOTAL": 2,
"C": 1464 
},
{
 "FAO": 87,
"year": 1984,
"TOTAL": 2,
"C": 2480 
},
{
 "FAO": 87,
"year": 1985,
"TOTAL": 2,
"C": 5032 
},
{
 "FAO": 87,
"year": 1986,
"TOTAL": 2,
"C": 6985 
},
{
 "FAO": 87,
"year": 1987,
"TOTAL": 2,
"C": 4337 
},
{
 "FAO": 87,
"year": 1988,
"TOTAL": 2,
"C": 4300 
},
{
 "FAO": 87,
"year": 1989,
"TOTAL": 2,
"C": 6889 
},
{
 "FAO": 87,
"year": 1990,
"TOTAL": 2,
"C": 9387 
},
{
 "FAO": 87,
"year": 1991,
"TOTAL": 2,
"C": 10969 
},
{
 "FAO": 87,
"year": 1992,
"TOTAL": 2,
"C": 26918 
},
{
 "FAO": 87,
"year": 1993,
"TOTAL": 2,
"C": 20997 
},
{
 "FAO": 87,
"year": 1994,
"TOTAL": 2,
"C": 20902 
},
{
 "FAO": 87,
"year": 1995,
"TOTAL": 2,
"C": 15694 
},
{
 "FAO": 87,
"year": 1996,
"TOTAL": 2,
"C": 8959 
},
{
 "FAO": 87,
"year": 1997,
"TOTAL": 2,
"C": 8077 
},
{
 "FAO": 87,
"year": 1998,
"TOTAL": 2,
"C": 9183 
},
{
 "FAO": 87,
"year": 1999,
"TOTAL": 2,
"C": 11193 
},
{
 "FAO": 87,
"year": 2000,
"TOTAL": 2,
"C": 10951 
},
{
 "FAO": 87,
"year": 2001,
"TOTAL": 2,
"C": 6532 
},
{
 "FAO": 87,
"year": 2002,
"TOTAL": 2,
"C": 6787 
},
{
 "FAO": 87,
"year": 2003,
"TOTAL": 2,
"C": 5376 
},
{
 "FAO": 87,
"year": 2004,
"TOTAL": 2,
"C": 4864 
},
{
 "FAO": 87,
"year": 2005,
"TOTAL": 2,
"C": 5251 
},
{
 "FAO": 87,
"year": 2006,
"TOTAL": 2,
"C": 4469 
},
{
 "FAO": 87,
"year": 2007,
"TOTAL": 2,
"C": 4383 
},
{
 "FAO": 87,
"year": 2008,
"TOTAL": 2,
"C": 4752 
},
{
 "FAO": 87,
"year": 2009,
"TOTAL": 2,
"C": 4851 
},
{
 "FAO": 87,
"year": 2010,
"TOTAL": 2,
"C": 4946 
},
{
 "FAO": 87,
"year": 2011,
"TOTAL": 2,
"C": 4214 
},
{
 "FAO": 87,
"year": 2012,
"TOTAL": 2,
"C": 4209 
},
{
 "FAO": 88,
"year": 1977,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1978,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1979,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1980,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1981,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1982,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1983,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1984,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1985,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1986,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1987,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1988,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1989,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1990,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1991,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1992,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1993,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1994,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1995,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1996,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1997,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 1998,
"TOTAL": 11,
"C": 1 
},
{
 "FAO": 88,
"year": 1999,
"TOTAL": 11,
"C": 1 
},
{
 "FAO": 88,
"year": 2000,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 2001,
"TOTAL": 11,
"C": 34 
},
{
 "FAO": 88,
"year": 2002,
"TOTAL": 11,
"C": 12 
},
{
 "FAO": 88,
"year": 2003,
"TOTAL": 11,
"C": 26 
},
{
 "FAO": 88,
"year": 2004,
"TOTAL": 11,
"C": 12 
},
{
 "FAO": 88,
"year": 2005,
"TOTAL": 11,
"C": 7 
},
{
 "FAO": 88,
"year": 2006,
"TOTAL": 11,
"C": 1 
},
{
 "FAO": 88,
"year": 2007,
"TOTAL": 11,
"C": 12 
},
{
 "FAO": 88,
"year": 2008,
"TOTAL": 11,
"C": 8 
},
{
 "FAO": 88,
"year": 2009,
"TOTAL": 11,
"C": 16 
},
{
 "FAO": 88,
"year": 2010,
"TOTAL": 11,
"C": 0 
},
{
 "FAO": 88,
"year": 2011,
"TOTAL": 11,
"C": 2 
},
{
 "FAO": 88,
"year": 2012,
"TOTAL": 11,
"C": 6 
} 
]
  
      if(!(opts.type==="pieChart" || opts.type==="sparklinePlus" || opts.type==="bulletChart")) {
        var data = d3.nest()
          .key(function(d){
            //return opts.group === undefined ? 'main' : d[opts.group]
            //instead of main would think a better default is opts.x
            return opts.group === undefined ? opts.y : d[opts.group];
          })
          .entries(data);
      }
      
      if (opts.disabled != undefined){
        data.map(function(d, i){
          d.disabled = opts.disabled[i]
        })
      }
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .width(opts.width)
          .height(opts.height)
          
        if (opts.type != "bulletChart"){
          chart
            .x(function(d) { return d[opts.x] })
            .y(function(d) { return d[opts.y] })
        }
          
         
        chart
  .showControls(true)
  .useInteractiveGuideline(true)
          
        

        
        
        
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>

<span style="font-size:0.6em;">
Zone 87 & 41 ----> South America   
Zone 58 ----> Kerguelen Plateau   
Zone 48 ----> South Georgia   
</span>

--- .middle .smaller

<a class='example'>Chapter 2</a>

## TAC in Chile
&nbsp;


![img](images/c2.png)
<div style="text-align:center">
<img src="images/c3.png" alt="rule" style="width: 350px;"/>
</div>


--- &twocol w1:40% w2:60% .middle .smaller

<a class='example'>Chapter 2</a>

## Progress Chapter 2
&nbsp;   
&nbsp;   

*** =left

- __Documents__ (70% Chile - 30% Argentina)
  - Progress 85% (<a href="C:\Users\jcquiroz\Dropbox\CBA_bacalao">see ftp</a>)
- __Target Journal__
  - Marine Policy
  - Marine Resource Economics
  - CCAMLR Science (Paul's suggestion)
- __Milestone / First Draft__
  - January, 2015

*** =right

- __Contingencies__
  - Insufficient Bibliography
  - Possible survey to stakeholders
- __Possible requirements__
  - Include others people as co-authors 


--- .segue .nobackground .dark

## Chapter 3

--- .middle .smaller

<a class='example'>Chapter 3</a>

## Patagonian toothfish population dynamics in a spatially varying simulation framework: The case of Kerguelen Plateau
&nbsp;

In this Chapter I will try develop tools to improve the theoretical population dynamic of Patagonian Toothfish on Kerguelen Plateau, particularly related to demographic traits under a spatially-structured base   

&nbsp;

The research should use a __scenario-based__ analysis, avoiding parallel researches that come from FRDC project    

&nbsp;    

Most of the inputs to setting the different scenarios should be derived from FRDC project


--- .middle .smaller .fill

<a class='example'>Chapter 3</a>

<div style="text-align:center">
<img src="images/c6.png" alt="rule" style="width: 850px;"/>
</div>


--- &twocol w1:40% w2:60% .middle .smaller

<a class='example'>Chapter 3</a>

## Progress Chapter 3
&nbsp;   
&nbsp;   

*** =left

- __Coding__ 
  - Progress 10% 
      - Some processes are finished (<a href="https://github.com/jcquiroz/Southern-Hake-Fishery/blob/master/model_2011/model_msur.tpl">repo</a>)
- __Target Journal__
  - Plos One (California corporation, USA)
- __Milestone / First Draft__
  - November, 2015

*** =right

- __Contingencies__
  - Largely depend on findings from __FRDC__ project
  - Overreaching in this Chapter <a href="comments_PB.pdf">see Paul's Comments</a>


--- .segue .nobackground .dark

## Chapter 4

---  &twocol w1:40% w2:60% .middle .smaller

<a class='example'>Chapter 4</a>

## Impact of misspecification model under a spatially-structured population, the TOP in South-America
A similar population dynamics


---  &twocol w1:40% w2:60% .middle .smaller

<a class='example'>Chapter 4</a>

## Impact of misspecification model under a spatially-structured population, the TOP in South-America
A similar population dynamics   
&nbsp;  

*** =left

__Chile (2012-2013)__
<div style="text-align:center">
<img src="images/c9.png" alt="rule" style="width: 500px;"/>
</div>

*** =right

__Argentina (2004-2012)__
<div style="text-align:center">
<img src="images/c8.png" alt="rule" style="width: 450px;"/>
</div>


---  &twocol w1:50% w2:50%  .middle .smaller 

<a class='example'>Chapter 4</a>

## Many issues remain

*** =left

&nbsp;   
&nbsp;  
&nbsp;   
&nbsp;
- Tag size-overlap
- Voluntary process (enforcement is necessary)
- Spatial and temporal sampling coverage
- Artesanal fleet participation

*** =right

&nbsp;   
&nbsp;   
<div style="text-align:center">
<img src="images/c7.png" alt="rule" style="width: 450px;"/>
</div>


--- .segue .nobackground .dark

## Chapter 5

--- .middle .smaller

<a class='example'>Chapter 5</a>

## Bio-economic management strategy evaluation of TOP in  southern and antarctic oceans
&nbsp;
Still thinking about it !!, but a good start point maybe is Hoshino _et al._ (2010) ...   
&nbsp;  


--- .middle .smaller

<a class='example'>Chapter 5</a>

## Bio-economic management strategy evaluation of TOP in  southern and antarctic oceans
&nbsp;
Still thinking about it !!, but a good start point maybe is Hoshino _et al._ (2010) ...   
&nbsp;  

<div style="text-align:center">
<img src="images/c10.png" alt="rule" style="width: 450px;"/>   

<img src="images/c11.png" alt="rule" style="width: 450px;"/>
</div>

--- .segue .nobackground .dark

## Support, coding and backup

--- .middle .smaller

<a class='example'>Support</a>

## Control version & Reproducible Research
&nbsp;
PhD Repository in __<a href="https://github.com/jcquiroz/utas-aad-git" target="_blank">GitHub</a>__

<div style="text-align:center">
<img src="images/c4.png" alt="rule" style="width: 800px;"/>
</div>


--- .middle .smaller

<a class='example'>Support</a>

## LATEX based

Most of the writing outcomes will be based in Latex. Nevertheless Microsoft version files will also be stored. __Why use LATEX?__  <span style="color:red; font-family:Georgia; font-size:1em;">High typographical quality, time-saving, clean & order</span>.   
E.g.: <a href="thesis.pdf">Thesis Template</a> (Thanks to Paul for sharing his Thesis template)

<div style="text-align:center">
<img src="images/c5.png" alt="rule" style="width: 800px;"/>
</div>


--- .segue .nobackground .dark

## Thank You!!!
