Session results
===============

###Previous:
- can import Russian / US time series for future analysis

###Expected result:
- sna/fof: can review relevant economic statistics 
- sa: can elaborate on properties of time series components
- sa: can perform basic seasonal adjustment of selected time series
- system of eq: can select predictors for tiem series based on literature
- business cycle: can suggest and illustrate hypethesis about comovements in time series


1. Follow up on IO tables, SNA and Flow of funds
================================================

Handouts

2. Systems of equations 
=======================

###Systems of equations - Klein I:
 -  <https://github.com/epogrebnyak/systemfit/blob/master/README.md>
 -  <http://www2.hawaii.edu/~gangnes/kleinEViews.pdf>
 -  [systemfit](https://cran.r-project.org/web/packages/systemfit/vignettes/systemfit.pdf) R package 
 
###Model descriptions:
 - Mandatory: Russian economy - [ECFOR/Mikhailenko](http://www.ecfor.ru/pdf.php?id=books/sa2004/mih) 

 - US [Klein model I](http://www2.hawaii.edu/~gangnes/kleinEViews.pdf), 1920-1941 + also resume of Klein III model 
      [here](http://cowles.yale.edu/sites/default/files/files/pub/cdp/e-0241.pdf)
 - US - [Fair model](http://fairmodel.econ.yale.edu/rayfair/pdf/2003APUB.PDF), chapter 2 
 - Russian economy - [Rusoil](http://www.fni.no/russcasp/WP-2009-002-OLO-An-Econometric-Macro-Model-of-the-Russian-Economy_No-Appendix.pdf)  
 

3. Joint movements
===================

Нandout + <https://github.com/epogrebnyak/cmf-comovement-tables/blob/master/README.md>


4.Seasonality and detrending 
============================

Default procedure (for rosstat-kep-data): <https://github.com/epogrebnyak/additional/tree/master/seasonality>

Trend stationary (TS) / difference stationary (DS) time series: story of stable coefficents

"Parts of time series":
1. long trend 
2. cyclical, or business cycle component (see also recession definiton)
3. seasonal component 
4. irregular, random component (very high frequencies)

Different questions in...
- seasonal adjustment:  what is the summ of part 1 + part 2
- detrending: what is part 2?

Frequencies:
1. up to 4-8 years
2. anything between 
3. monthly/quarterly
4. very high frequencies

> The problem of how best to design seasonal adjustment procedures is a very old one and it has generated a 
> considerable literature. Although much progress has been made the problem can hardly be classified as solved.

Time series and spectral methods in econometrics C. W. J. Granger and Mark W. Watson. - Chapter 17. Handbook of Econometrics, Volume II, Edited by Z. Griliches and M.D. Intriligator Elseoier Science Publishers BV, 1984

Traditional clues for seasonal adjustment:
- naive seasonal adjustment: additive/ multiplicative 
- special cases: outliers, breaks, shifts, etc
- X11 vs TRAMO/SEATS
- software and packages
- practical convern: seasonally adjusted tails

Literature
==========

Borrowed slides:
- Heino Bohn Nielsen. [Non-Stationary Time Series and Unit Root Tests](http://www.econ.ku.dk/metrics/Econometrics2_05_II/Slides/08_unitroottests_2pp.pdf), see slides 6 and 9
- [Fourier transforms](https://en.wikipedia.org/wiki/Fourier_series#/media/File:Fourier_series_square_wave_circles_animation.gif)
- [Fourier series visualisation](http://bl.ocks.org/jinroh/7524988)

Good short reading on filtering:
- Kanda Naknoi. [Filtering macroeconomic time series](http://www.krannert.purdue.edu/faculty/knaknoi/Econ635/filter.pdf)

ESS guidelines on seasonal adjustment  
URL: <http://ec.europa.eu/eurostat/documents/3859598/6830795/KS-GQ-15-001-EN-N.pdf/d8f1e5f5-251b-4a69-93e3-079031b74bd3> 

Seasonal Adjustment Methodology at BLS  
URL: <http://www.bls.gov/cpi/cpisahoma.htm>

Default procedure (for rosstat-kep-data): <https://github.com/epogrebnyak/additional/tree/master/seasonality>

X11, Traumo/SEATS

<!--
Business cyles - more reading:
- SW
- Handbook

Seasonal adjustment:
- Handbooks/Manuals
- Software
- Packages
-->

Time series (general)
- Hamilton. [Time series analysis](http://press.princeton.edu/titles/5386.html)
- Granger/Watson. Time series and spectral methods in econometrics C. W. J. Granger and Mark W. Watson
- Лекции Г.Г. Канторовича - Экономический журнал ВШЭ, 2002-2003 
