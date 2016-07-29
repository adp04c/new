---
title       : Reproducing Analysis and Additional Findings
subtitle    : 
author      : Austin Peel
job         : 
framework   : revealjs       # {io2012, html5slides, shower, dzslides, ...}
revealjs: {theme: simple}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
github:
  user: adp04c
  repo: new
--- 

## HC cost per employee serviced by HC servicing ratio

<iframe width="600" height="500" frameborder="0" scrolling="no" src="https://plot.ly/~adp04c/0.embed"></iframe>

--- 

## HC cost per employee serviced 

<table style="text-align:center" col width="10" col height="1"><tr><td colspan="4" style="border-bottom: 1px solid black" width=100 height=1></td></tr><tr><td style="text-align:left "font-size: 35px;"></td><td colspan="3"><em>Dependent variable:</em></td></tr>
<tr><td></td><td colspan="3" style="border-bottom: 1px solid black"></td></tr>
<tr><td style="text-align:left"></td><td colspan="3">Cost_per_employee</td></tr>
<tr><td style="text-align:left"></td><td>(1)</td><td>(2)</td><td>(3)</td></tr>
<tr><td colspan="4" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Servicing_Ratio</td><td>-6.075<sup>***</sup></td><td>-6.102<sup>***</sup></td><td>-102.503<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(2.027)</td><td>(2.031)</td><td>(15.456)</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Year_2014</td><td></td><td>265.140</td><td>73.134</td></tr>
<tr><td style="text-align:left"></td><td></td><td>(457.565)</td><td>(426.711)</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">HC_Satisfaction</td><td></td><td></td><td>-381.943</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(338.830)</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Servicing_Ratio_Squared</td><td></td><td></td><td>0.315<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.072)</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Constant</td><td>4,348.709<sup>***</sup></td><td>4,210.562<sup>***</sup></td><td>9,906.134<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(264.005)</td><td>(356.025)</td><td>(1,641.539)</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td></tr>
<tr><td colspan="4" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Observations</td><td>216</td><td>216</td><td>164</td></tr>
<tr><td style="text-align:left">R<sup>2</sup></td><td>0.040</td><td>0.042</td><td>0.254</td></tr>
<tr><td style="text-align:left">Adjusted R<sup>2</sup></td><td>0.036</td><td>0.033</td><td>0.235</td></tr>
<tr><td style="text-align:left">Residual Std. Error</td><td>3,351.100 (df = 214)</td><td>3,356.313 (df = 213)</td><td>2,703.500 (df = 159)</td></tr>
<tr><td style="text-align:left">F Statistic</td><td>8.983<sup>***</sup> (df = 1; 214)</td><td>4.645<sup>**</sup> (df = 2; 213)</td><td>13.538<sup>***</sup> (df = 4; 159)</td></tr>
<tr><td colspan="4" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"><em>Note:</em></td><td colspan="3" style="text-align:right"><sup>*</sup>p<0.1; <sup>**</sup>p<0.05; <sup>***</sup>p<0.01</td></tr>
</table>

--- 

## servicing ratio and satisfaction

<table style="text-align:center"><tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td><em>Dependent variable:</em></td></tr>
<tr><td></td><td colspan="1" style="border-bottom: 1px solid black"></td></tr>
<tr><td style="text-align:left"></td><td>Servicing_Ratio</td></tr>
<tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Cost_per_employee</td><td>-0.015<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.002)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">Year_2014</td><td>-3.558</td></tr>
<tr><td style="text-align:left"></td><td>(4.043)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">HC_Satisfaction</td><td>-17.625<sup>**</sup></td></tr>
<tr><td style="text-align:left"></td><td>(7.227)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">partner</td><td>9.076</td></tr>
<tr><td style="text-align:left"></td><td>(7.711)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">Cost_per_employee_squared</td><td>0.00000<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.00000)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">Constant</td><td>136.000<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(12.843)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Observations</td><td>164</td></tr>
<tr><td style="text-align:left">R<sup>2</sup></td><td>0.397</td></tr>
<tr><td style="text-align:left">Adjusted R<sup>2</sup></td><td>0.378</td></tr>
<tr><td style="text-align:left">Residual Std. Error</td><td>24.384 (df = 158)</td></tr>
<tr><td style="text-align:left">F Statistic</td><td>20.778<sup>***</sup> (df = 5; 158)</td></tr>
<tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"><em>Note:</em></td><td style="text-align:right"><sup>*</sup>p<0.1; <sup>**</sup>p<0.05; <sup>***</sup>p<0.01</td></tr>
</table>

---

## the drivers of human capital satisfaction

<table style="text-align:center"><tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td><em>Dependent variable:</em></td></tr>
<tr><td></td><td colspan="1" style="border-bottom: 1px solid black"></td></tr>
<tr><td style="text-align:left"></td><td>HC_SAT</td></tr>
<tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">TDS_SAT</td><td>0.053<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.006)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">RHS_SAT</td><td>0.588<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.006)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">WLSS_SAT</td><td>0.048<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.006)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">HR_SAT</td><td>0.233<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.007)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">SURVEYOGP Benchmarking Supervisor Survey</td><td>-0.089<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.016)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">Constant</td><td>0.410<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.027)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Observations</td><td>18,944</td></tr>
<tr><td style="text-align:left">R<sup>2</sup></td><td>0.698</td></tr>
<tr><td style="text-align:left">Adjusted R<sup>2</sup></td><td>0.698</td></tr>
<tr><td style="text-align:left">Residual Std. Error</td><td>1.069 (df = 18938)</td></tr>
<tr><td style="text-align:left">F Statistic</td><td>8,752.173<sup>***</sup> (df = 5; 18938)</td></tr>
<tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"><em>Note:</em></td><td style="text-align:right"><sup>*</sup>p<0.1; <sup>**</sup>p<0.05; <sup>***</sup>p<0.01</td></tr>
</table>
