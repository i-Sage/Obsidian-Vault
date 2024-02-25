---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
Bivariate Statistics ^0MYYEvxa

Linear Regression is part of a special area of statistics called Bivariate Statistics
 ^6ZBX8Dzo

Bivariate means two variables
 ^24hKGY1C

CORRELATION ^3cDdD2WE

ANOVA ^k4xHBbcM

LINEAR REGRESSION
 ^BJvw8Sw3

variable 1 ^jSOKQkXQ

variable 2 ^Y49x0C3C

correlation and regression also have something
in common, and that is the data points are
plotted on a coordinate plane
 ^1OTa5eqY

y ^xMH7hQo3

x ^SdIArAJ7

The value of  ^yP4IQvrQ

one variable, ^IA8dWgoJ

is a function of ^JbarKNFb

the other variable ^ii63WRqb

The value of y, is a function of x; y = f(x) ^DlvWq1dT

the value of the dependent variable, is a function of the independent variable. ^6Kle8atZ

Algebra Review: Lines ^s9rKJBkI

slope-intercept from of a line:  ^hOAWFAJH

y = mx + b ^Ky4AwPGy

x ^fJlOhyPh

y ^zxDaGaMs

x = random variable

m = slope of the line rise ^k4U2xipY

run ^kc7mqCoe

b = y-intercept (crosses y-axis) ^3I21eu6P

y-intercept is where x = 0 ^IxcIVO3g

y = 2x + 3 ^gueIRIIp

y = mx + b ^itBLVecu

m = slope = 2 ^YRObfc7C

y-intercept = y = (0) = 3
y = 3
(0, 3) ^fyUhjoOx

comparing
 ^5rW0wRSp

(0,3) ^Zi7iPxHd

But we need two points to draw a line ^GstWn8Zt

we can use x = 1, and plug that into the equation of the line ^rILWGE0m

y = 2(1) + 3 = 5
 ^tq0cqCiW

(1, 5) ^9YzbM89I

/1 ^hLYoxXtV

1 ^AZpptPer

2 ^DA0wOrWq

linear regression model ^jiwMJG5B

The goal of linear regression is to find a line of best fit that reduces the overall squared sum error (SSE) ^x7tq6iKA

y = mx + b ^V7At6pYL

y = Bo + B1x + e ^olckQGJx

Bo = y-intercept population parameter ^XbfX7Cou

B1 = slope of population parameter ^OFnpSW7U

Simple Linear Regression Equation ^U7Tuvel0

E(y) = Bo + B1x ^C9RPoMUl

E(y) is the mean or expected value of y, for a given value of x ^te8GILNY

x ^jKAoCKbw

y ^JUIhwbKi

E(y) ^E9H3t3Y4

Lets say we pick a value of x, that corresponds to an expected value of y
it is really not that simple, there is actually a distribution of ys for that x.
Remember our regression model is not perfect, so any expected value of y we
come up with, is at best going to be an approximation. So when we say the 
expected value, we mean is that it is the mean of a small distribution for that
y. We want to have the expected value of our y in a narrower range ^spsB73kd

x ^bAjPI1xq

y ^AH39xiUt

E(y) ^JNy64mO1

smaller range of expected y values, better model ^rFv08jFd

Larger range of expected y values, bad model ^BUrOvFDl

But note that the expected value of y is really just the mean of the distribution of those y values. ^dMv8519p

GENERAL REGRESSION LINES ^x2KoVwEz

E(y) = Bo + B1x ^4NnthU52

E(y) ^hm4wrne3

x ^3FXfr5cR

E(y) = Bo + 0(x) ^jDlCHll9

Bo ^e49jrSyA

case 1 ^6lALi02Y

E(y) ^stw5KyrT

x ^CN9SiFyS

E(y) = Bo + B1(x) ^VKNOKml4

Bo ^2H2UaQGI

case 2 ^DVu2q8Gf

slope B1 is +ive ^L9NxpG7l

E(y) ^sCNNXOdU

x ^4zwc5Z95

E(y) = Bo - B1(x) ^wDT2W6o4

Bo ^de2vAC3S

case 3 ^mPXNuUyX

slope B1 is -ive ^UifyREAi

These are the general types of simple linear regression
lines that are based on the sign and the value of B1
which is the slope ^kYO7Kysq

REGRESSION EQUATION WITH ESTIMATES ^95ZAlc12

If we actually knew the population parameters, Bo and B1, we could use the simple linear regression equation ^6CA0lzIQ

E(y) = Bo + B1x ^WCCL60S4

In reality we almost never have the population parameters. Therefore we will estimate them using sample data. When using
sample data, we have to change our equation a little bit. ^hmnCsreq

y = bo + b1x ^cu8X5kXh

y is the point estimator of E(y) ^pqnhKhSS

y is the mean value of y for a given value of x ^m8eMYSB2

GETTING READY FOR LEAST SQUARES ^vAsqGVEj

Going back to our previous example, we now add the bill price of the meal to our data. ^69tOxX0j

Bill($)       Tip($)
34.00        5.00
108.00       17.00
64.00        11.00
88.00       8.00
99.00        14.00
51.00         5.00 ^EYQCjqvR

tip amount ($) ^Rkyl10kw

Bill amount($) ^JH5GhhbR

20 ^mvTGKhgY

40 ^863WO49I

60 ^QP9CTFit

80 ^VqcXtv1p

100 ^zDqdM3Xz

120 ^iQUnCBM0

4 ^cZegTbor

6 ^uWkh5c2A

8 ^exeZe884

10 ^1JCiIpdW

12 ^8Hxpjr79

16 ^FZ3Ym0xe

18 ^zv6I2mG0

Graphing the data on a scatter plot, 
The tip dollar amount depends on the original
bill amount. This is what we think and hypothesizing.
so general, a lower bill will result in a lower tip and 
a more expensive meal will result in a higher tip.

Looking at the scatter plot, it appears there is some 
kind of linear relationship that goes form left to right.

So if we drew a line it would probably start at the lower left
and go to the upper right.

And most importantly, if that line reduces the residual sum of 
square significantly from the model where we only used the mean
of the tip, that is when we say our regression model is "good" in 
a qualitative sense. ^1NjZEn3x

Meal bill vs Tip amount($) ^vMmhIJWR

Bill($)       Tip($)
34.00        5.00
108.00       17.00
64.00        11.00
88.00       8.00
99.00        14.00
51.00         5.00 ^nuaouPHT

tip amount ($) ^49a7GpK3

Bill amount($) ^dUskGHd9

20 ^Q6KUE03I

40 ^LfPYnlnR

60 ^TkKRCQTw

80 ^5979Vyeg

100 ^TyfkQHW9

120 ^XV6jJaa0

4 ^Hirf10gl

6 ^GqdAol0X

8 ^xjAseuOW

10 ^iAK5F53F

12 ^LdVLEWQF

16 ^x1kYrmox

18 ^SzP27wqn

Meal bill vs Tip amount($) ^i5BL9Cmk

Bill($)       Tip($)
34.00        5.00
108.00       17.00
64.00        11.00
88.00       8.00
99.00        14.00
51.00         5.00
x' = 74       y' = 10 ^Q7mWfKNj

tip amount ($) ^gPSYMw9c

Bill amount($) ^tBqCMSqR

20 ^p1pmuQGw

40 ^K9xM1hcJ

60 ^LmRkDPAn

80 ^KYLnrTZX

100 ^jZqfJJiA

120 ^Pp4PPtI3

4 ^Rx1xjBvU

6 ^dn1lxczk

8 ^izGtj9OR

10 ^jPricv6b

12 ^eSshjiAc

16 ^KgDo8O1m

18 ^8I6yu8Hh

Meal bill vs Tip amount($) ^xwCfkNLU

x' = 74 ^DbDDwq35

y' = 10 ^r65ymO7U

(74, 10) CENTROID ^301OhoAx

The best-fit regression line will / must 
pass through the centroid ^txKSANZz

tip amount ($) ^z7n0BAXG

Bill amount($) ^3nHYMXxF

20 ^93H2LN79

40 ^9DvJf9bH

60 ^KCLKfUya

80 ^aQwvZbXk

100 ^RcEHtayJ

120 ^OquOd6ys

4 ^JEdJX5bt

6 ^YmiqVVlR

8 ^A6VN8U1r

10 ^DE5dRc6S

12 ^1eZbAgmu

16 ^WTriv1Tk

18 ^OBdimM66

Meal bill vs Tip amount($) ^UhF6dzns

y = 0.1462x - 0.8188 ^hp7dP8N5

(74,10) CENTROID ^JnMdqxs3

y'i = 0.1462x - 0.8188 ^4YSUBR8r

QUICK INTERPRETATION ^AjH9DqAm

For every $1 the bill amount(x) increases, we wold expect the tip
amount to increase by $0.1462 or about 15-cents. ^K12MoOo9

if the bill amount (x) is zero, then the expected / predicted tip 
amount is $-0.8188 or negative 82-cents! Does this make snese
? No. The intercept may or may not make sense in the "real world". ^agipPV7j

BUT IS THIS REGRESSION LINE MODEL ANY GOOD ???!!!! ^uWBKfzH1

The difference between the observed value of y and the
straight line (Bo + B1x) be an error e. It is convenient to think
of e as a statistical error; that is, it is a random variable
that accounts for the failure of the model to fit the data
exactly. The error may be made up of the effects of other
variables on delivery time, measurnment errors, and so forth ^fj6US580

e =  ^lvmP7Qhb

SST ^u0ae1u8u

SSR ^G2UE7Oo6

SSE ^4MB2WzQW

If SSR is large, it uses up more SST and therefore SSE is smaller
relative to SST. The coefficient of determination quantifies this ratio
as a percentage. ^KzC6HUz5

coefficient of determination r^2 = SSR / SST ^LvqAerMC

r ^2 = 89.925 / 120
coefficient of determination = r^2 = 0.7493 or 74.93%

We can conclude that 74.93% of the total sum of squares can be explained by
using the estimated regression equation to predict the tip amount. The remainder is error
 ^dZG5KMGI

Good Fit! ^xVWLhubj

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.0.20",
	"elements": [
		{
			"type": "text",
			"version": 258,
			"versionNonce": 33218800,
			"isDeleted": false,
			"id": "uWBKfzH1",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1742.5065771677741,
			"y": 1608.1704024925052,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1596.55908203125,
			"height": 66.62689208984376,
			"seed": 296718659,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703960486510,
			"link": null,
			"locked": false,
			"fontSize": 53.301513671875014,
			"fontFamily": 1,
			"text": "BUT IS THIS REGRESSION LINE MODEL ANY GOOD ???!!!!",
			"rawText": "BUT IS THIS REGRESSION LINE MODEL ANY GOOD ???!!!!",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "BUT IS THIS REGRESSION LINE MODEL ANY GOOD ???!!!!",
			"lineHeight": 1.25,
			"baseline": 46
		},
		{
			"type": "text",
			"version": 492,
			"versionNonce": 18811120,
			"isDeleted": false,
			"id": "0MYYEvxa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -511.7477767794742,
			"y": -169.95132790359798,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 429.279541015625,
			"height": 53.35269703584559,
			"seed": 1055756412,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"fontSize": 42.68215762867647,
			"fontFamily": 1,
			"text": "Bivariate Statistics",
			"rawText": "Bivariate Statistics",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Bivariate Statistics",
			"lineHeight": 1.25,
			"baseline": 37
		},
		{
			"type": "text",
			"version": 602,
			"versionNonce": 654696399,
			"isDeleted": false,
			"id": "6ZBX8Dzo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -947.1541979172653,
			"y": -72.63827469769643,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 980.1083374023438,
			"height": 57.732579848345615,
			"seed": 1580512580,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055083,
			"link": null,
			"locked": false,
			"fontSize": 23.093031939338246,
			"fontFamily": 1,
			"text": "Linear Regression is part of a special area of statistics called Bivariate Statistics\n",
			"rawText": "Linear Regression is part of a special area of statistics called Bivariate Statistics\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Linear Regression is part of a special area of statistics called Bivariate Statistics\n",
			"lineHeight": 1.25,
			"baseline": 49
		},
		{
			"type": "text",
			"version": 252,
			"versionNonce": 480512161,
			"isDeleted": false,
			"id": "24hKGY1C",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -968.5199439104866,
			"y": -18.253000147202414,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 300.31964111328125,
			"height": 50,
			"seed": 1486303300,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Bivariate means two variables\n",
			"rawText": "Bivariate means two variables\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Bivariate means two variables\n",
			"lineHeight": 1.25,
			"baseline": 42
		},
		{
			"type": "rectangle",
			"version": 62,
			"versionNonce": 241594096,
			"isDeleted": false,
			"id": "ZhEJmLfR37JOc73ICHC_e",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -995.2987480163574,
			"y": 162.56743621826172,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 232.23435974121094,
			"height": 51.485931396484375,
			"seed": 526523204,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "608k4gJPAjLLC965yibYq",
					"type": "arrow"
				}
			],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 108,
			"versionNonce": 1978364656,
			"isDeleted": false,
			"id": "IA-7v4bjndR-_ask7ByHm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -943.812801361084,
			"y": 306.07076263427734,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 176.36666870117188,
			"height": 35,
			"seed": 1590961148,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "k4xHBbcM"
				},
				{
					"id": "XMpxtXV5iyb4NtWZANMm-",
					"type": "arrow"
				}
			],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 45,
			"versionNonce": 989820656,
			"isDeleted": false,
			"id": "k4xHBbcM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -887.6194496154785,
			"y": 311.07076263427734,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 63.97996520996094,
			"height": 25,
			"seed": 1477859068,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "ANOVA",
			"rawText": "ANOVA",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "IA-7v4bjndR-_ask7ByHm",
			"originalText": "ANOVA",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 105,
			"versionNonce": 198383856,
			"isDeleted": false,
			"id": "B39vfMNwWnwhq9AspbliJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -605.3202171325684,
			"y": 284.16182708740234,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 331.91986083984375,
			"height": 92.01739501953125,
			"seed": 1427703548,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "XMpxtXV5iyb4NtWZANMm-",
					"type": "arrow"
				},
				{
					"id": "608k4gJPAjLLC965yibYq",
					"type": "arrow"
				},
				{
					"id": "cX9LNhm5SlgCPjUEruk9O",
					"type": "arrow"
				}
			],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 93,
			"versionNonce": 1979125231,
			"isDeleted": false,
			"id": "3cDdD2WE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -956.7565116882324,
			"y": 181.2939682006836,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 147.47987365722656,
			"height": 25,
			"seed": 1785911804,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055088,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "CORRELATION",
			"rawText": "CORRELATION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CORRELATION",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 197,
			"versionNonce": 1272002447,
			"isDeleted": false,
			"id": "XMpxtXV5iyb4NtWZANMm-",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -756.4916954040527,
			"y": 327.9796371459961,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 143.50332641601562,
			"height": 5.47723388671875,
			"seed": 861750596,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1708260037520,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "IA-7v4bjndR-_ask7ByHm",
				"gap": 10.954437255859375,
				"focus": 0.02995261921899986
			},
			"endBinding": {
				"elementId": "B39vfMNwWnwhq9AspbliJ",
				"gap": 7.66815185546875,
				"focus": -0.18939249531627034
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					143.50332641601562,
					5.47723388671875
				]
			]
		},
		{
			"type": "arrow",
			"version": 192,
			"versionNonce": 35024400,
			"isDeleted": false,
			"id": "608k4gJPAjLLC965yibYq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -747.7281455993652,
			"y": 189.95357513427734,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 129.26254272460938,
			"height": 99.68548583984375,
			"seed": 1392798276,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399771,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ZhEJmLfR37JOc73ICHC_e",
				"focus": -0.8650454058323415,
				"gap": 15.33624267578125
			},
			"endBinding": {
				"elementId": "B39vfMNwWnwhq9AspbliJ",
				"focus": -0.5608911031109866,
				"gap": 13.1453857421875
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					129.26254272460938,
					99.68548583984375
				]
			]
		},
		{
			"type": "text",
			"version": 77,
			"versionNonce": 1396460673,
			"isDeleted": false,
			"id": "BJvw8Sw3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -553.9473533630371,
			"y": 314.67134857177734,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 218.3997802734375,
			"height": 50,
			"seed": 1402263676,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055089,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "LINEAR REGRESSION\n",
			"rawText": "LINEAR REGRESSION\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "LINEAR REGRESSION\n",
			"lineHeight": 1.25,
			"baseline": 42
		},
		{
			"type": "line",
			"version": 131,
			"versionNonce": 360130800,
			"isDeleted": false,
			"id": "DzAHzSHpJL9uUEcXjKgX7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -96.90139389038086,
			"y": 92.60863494873047,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.19085693359375,
			"height": 300.1520080566406,
			"seed": 577335420,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.19085693359375,
					300.1520080566406
				]
			]
		},
		{
			"type": "line",
			"version": 92,
			"versionNonce": 1619299056,
			"isDeleted": false,
			"id": "4adK8OlaRpVWexxKS3IWZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -135.24197006225586,
			"y": 376.32894134521484,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 425.03271484375,
			"height": 3.28631591796875,
			"seed": 888080324,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					425.03271484375,
					-3.28631591796875
				]
			]
		},
		{
			"type": "text",
			"version": 75,
			"versionNonce": 684789665,
			"isDeleted": false,
			"id": "jSOKQkXQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 42.04819107055664,
			"y": 384.76680755615234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 81.99189758300781,
			"height": 22.31800301888622,
			"seed": 1278206916,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260065019,
			"link": null,
			"locked": false,
			"fontSize": 17.854402415108975,
			"fontFamily": 1,
			"text": "variable 1",
			"rawText": "variable 1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "variable 1",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 93,
			"versionNonce": 1413609199,
			"isDeleted": false,
			"id": "Y49x0C3C",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -185.0927391052246,
			"y": 218.03850536672317,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80.97000122070312,
			"height": 20.105743595679172,
			"seed": 1542143172,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260065020,
			"link": null,
			"locked": false,
			"fontSize": 16.08459487654334,
			"fontFamily": 1,
			"text": "variable 2",
			"rawText": "variable 2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "variable 2",
			"lineHeight": 1.25,
			"baseline": 13
		},
		{
			"type": "text",
			"version": 675,
			"versionNonce": 703809288,
			"isDeleted": false,
			"id": "1OTa5eqY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -619.0761501087862,
			"y": 104.74032458137066,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 411.8969421386719,
			"height": 89.70748800686792,
			"seed": 437865596,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1704129676346,
			"link": null,
			"locked": false,
			"fontSize": 17.941497601373584,
			"fontFamily": 1,
			"text": "correlation and regression also have something\nin common, and that is the data points are\nplotted on a coordinate plane\n",
			"rawText": "correlation and regression also have something\nin common, and that is the data points are\nplotted on a coordinate plane\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "correlation and regression also have something\nin common, and that is the data points are\nplotted on a coordinate plane\n",
			"lineHeight": 1.25,
			"baseline": 82
		},
		{
			"type": "text",
			"version": 53,
			"versionNonce": 1188919311,
			"isDeleted": false,
			"id": "xMH7hQo3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -103.66109848022461,
			"y": 58.385032653808594,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 9.379989624023438,
			"height": 25,
			"seed": 1522569980,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055097,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "y",
			"rawText": "y",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 56,
			"versionNonce": 971052129,
			"isDeleted": false,
			"id": "SdIArAJ7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 300.67087173461914,
			"y": 356.7169418334961,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.239990234375,
			"height": 25,
			"seed": 1989752188,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x",
			"rawText": "x",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 102,
			"versionNonce": 1061039120,
			"isDeleted": false,
			"id": "cX9LNhm5SlgCPjUEruk9O",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -254.4589500427246,
			"y": 330.92977142333984,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 155.55316162109375,
			"height": 46.00872802734375,
			"seed": 606613956,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399774,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "B39vfMNwWnwhq9AspbliJ",
				"focus": 0.5830816108169874,
				"gap": 18.94140625
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					155.55316162109375,
					-46.00872802734375
				]
			]
		},
		{
			"type": "arrow",
			"version": 164,
			"versionNonce": 772487408,
			"isDeleted": false,
			"id": "gvquvaaU7AQMd-IysZUI9",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -740.8366355895996,
			"y": 176.47200775146484,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 627.6900634765625,
			"height": 6.572662353515625,
			"seed": 902596164,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					627.6900634765625,
					6.572662353515625
				]
			]
		},
		{
			"type": "diamond",
			"version": 34,
			"versionNonce": 1813420784,
			"isDeleted": false,
			"id": "CBnuqVkuqhK59ge2fcJlJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -51.80160140991211,
			"y": 306.8299789428711,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62249755859375,
			"height": 20.8134765625,
			"seed": 1288681468,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 39,
			"versionNonce": 1449508080,
			"isDeleted": false,
			"id": "JiTHZCZLqxMN2Bu1m2Koi",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -11.27016830444336,
			"y": 325.4525375366211,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 924283132,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 41,
			"versionNonce": 780181232,
			"isDeleted": false,
			"id": "slitqtmG_XNLGuKxv8sTF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 33.83676528930664,
			"y": 184.17354583740234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 888334844,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 41,
			"versionNonce": 1156530416,
			"isDeleted": false,
			"id": "JmUF9bcfcm_LdcRuUx0F4",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 24.83676528930664,
			"y": 249.17354583740234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 437312380,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 41,
			"versionNonce": 423207664,
			"isDeleted": false,
			"id": "0cWETjO2TyD6GngMto_ii",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 151.83676528930664,
			"y": 294.17354583740234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 1234320636,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 41,
			"versionNonce": 2045232368,
			"isDeleted": false,
			"id": "0RMxkaIySoyByhK1IsHe9",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 111.83676528930664,
			"y": 226.17354583740234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 451743356,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 41,
			"versionNonce": 612476656,
			"isDeleted": false,
			"id": "gZW7mzkJAXdkLAIzJt_sQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 80.83676528930664,
			"y": 275.17354583740234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 1364676604,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 41,
			"versionNonce": 1703889136,
			"isDeleted": false,
			"id": "xOFfdox0UHmjrqnYkDiZF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 44.83676528930664,
			"y": 309.17354583740234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 868680060,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 41,
			"versionNonce": 949529328,
			"isDeleted": false,
			"id": "dxFajkLQSpaLJ1Tw74qtg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -32.16323471069336,
			"y": 244.17354583740234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 619848444,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 41,
			"versionNonce": 1747307760,
			"isDeleted": false,
			"id": "vGqZhK5YVJ9x1EAmlz0jn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 143.83676528930664,
			"y": 174.17354583740234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 995013756,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 41,
			"versionNonce": 767471344,
			"isDeleted": false,
			"id": "Acm9B95tGIKtAQOvBJSGS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 179.83676528930664,
			"y": 238.17354583740234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 1494398460,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 41,
			"versionNonce": 1374376176,
			"isDeleted": false,
			"id": "ESa13nikw37zTPvJ6v77k",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 218.83676528930664,
			"y": 298.17354583740234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 1144268668,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 41,
			"versionNonce": 1278456560,
			"isDeleted": false,
			"id": "4wNWW0dYB8ztV8ga72mjJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 254.83676528930664,
			"y": 195.17354583740234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 1047070972,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 41,
			"versionNonce": 1663030512,
			"isDeleted": false,
			"id": "EXU0rjZLsjg1IHLwBaAFQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 203.83676528930664,
			"y": 135.17354583740234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 795777860,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 41,
			"versionNonce": 1278719728,
			"isDeleted": false,
			"id": "B4x_oFrkWdIilds0r6Amy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 268.83676528930664,
			"y": 242.17354583740234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 1271378372,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 41,
			"versionNonce": 1275287792,
			"isDeleted": false,
			"id": "btkCNUqA3Fk0Qv98zdtKn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 67.83676528930664,
			"y": 120.17354583740234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 1340685820,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 41,
			"versionNonce": 1443543792,
			"isDeleted": false,
			"id": "Our8xpF_yQByagGtkId6u",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 81.83676528930664,
			"y": 174.17354583740234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.62255859375,
			"height": 18.62255859375,
			"seed": 302800892,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 531734063,
			"isDeleted": false,
			"id": "yP4IQvrQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -892.2309597239775,
			"y": 432.3219927619485,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139.05982971191406,
			"height": 25,
			"seed": 1600836676,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055100,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The value of ",
			"rawText": "The value of ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The value of ",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 102,
			"versionNonce": 610394177,
			"isDeleted": false,
			"id": "IA8dWgoJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -743.10756817986,
			"y": 428.3970013786763,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 122.9798583984375,
			"height": 25,
			"seed": 1615661564,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "one variable,",
			"rawText": "one variable,",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "one variable,",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 103,
			"versionNonce": 861667407,
			"isDeleted": false,
			"id": "JbarKNFb",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -609.9521224078011,
			"y": 431.86767578125006,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 155.93980407714844,
			"height": 25,
			"seed": 59931332,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055103,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "is a function of",
			"rawText": "is a function of",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "is a function of",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 117,
			"versionNonce": 1084108833,
			"isDeleted": false,
			"id": "ii63WRqb",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -442.648224774529,
			"y": 430.9056181066175,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 180.3997802734375,
			"height": 25,
			"seed": 1264630084,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055105,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "the other variable",
			"rawText": "the other variable",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "the other variable",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 1135943279,
			"isDeleted": false,
			"id": "DlvWq1dT",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -873.7238078397869,
			"y": 468.45566693474285,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 433.6595458984375,
			"height": 25,
			"seed": 431414396,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055106,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The value of y, is a function of x; y = f(x)",
			"rawText": "The value of y, is a function of x; y = f(x)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The value of y, is a function of x; y = f(x)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 142,
			"versionNonce": 1418036225,
			"isDeleted": false,
			"id": "6Kle8atZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -901.2369124468642,
			"y": 503.4077722886032,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 782.5991821289062,
			"height": 25,
			"seed": 1738449732,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055108,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "the value of the dependent variable, is a function of the independent variable.",
			"rawText": "the value of the dependent variable, is a function of the independent variable.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "the value of the dependent variable, is a function of the independent variable.",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 202,
			"versionNonce": 36729729,
			"isDeleted": false,
			"id": "s9rKJBkI",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -569.2910039565152,
			"y": 670.6376737706806,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 493.2043762207031,
			"height": 59.795453348362784,
			"seed": 401110396,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260065028,
			"link": null,
			"locked": false,
			"fontSize": 47.83636267869023,
			"fontFamily": 1,
			"text": "Algebra Review: Lines",
			"rawText": "Algebra Review: Lines",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Algebra Review: Lines",
			"lineHeight": 1.25,
			"baseline": 41
		},
		{
			"type": "text",
			"version": 101,
			"versionNonce": 1008163809,
			"isDeleted": false,
			"id": "hOAWFAJH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -834.9114652331317,
			"y": 761.4923641817163,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 303.879638671875,
			"height": 25,
			"seed": 1257082564,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055112,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "slope-intercept from of a line: ",
			"rawText": "slope-intercept from of a line: ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "slope-intercept from of a line: ",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 138,
			"versionNonce": 987619848,
			"isDeleted": false,
			"id": "Ky4AwPGy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -503.2477384264911,
			"y": 753.8654110567163,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 174.60113525390625,
			"height": 40.33624267578132,
			"seed": 378484988,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1704129676367,
			"link": null,
			"locked": false,
			"fontSize": 32.268994140625054,
			"fontFamily": 1,
			"text": "y = mx + b",
			"rawText": "y = mx + b",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y = mx + b",
			"lineHeight": 1.25,
			"baseline": 28
		},
		{
			"type": "arrow",
			"version": 223,
			"versionNonce": 1019095568,
			"isDeleted": false,
			"id": "_q_DdgCygyIX4nsONCipx",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -228.85912758664733,
			"y": 1062.8549130098413,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.2962925487006487,
			"height": 286.52703247293334,
			"seed": 960327876,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399782,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "zxDaGaMs",
				"focus": 0.1644932914602491,
				"gap": 3.0307678200354076
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					1.2962925487006487,
					-286.52703247293334
				]
			]
		},
		{
			"type": "arrow",
			"version": 180,
			"versionNonce": 1166960656,
			"isDeleted": false,
			"id": "16Ze9lfUSipUK9dAv523f",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -269.3905606921161,
			"y": 1052.9958737032007,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 346.16064453125,
			"height": 2.19085693359375,
			"seed": 1777077316,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399783,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "fJlOhyPh",
				"focus": 0.06501293461571214,
				"gap": 11.6329345703125
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					346.16064453125,
					-2.19085693359375
				]
			]
		},
		{
			"type": "text",
			"version": 96,
			"versionNonce": 948276911,
			"isDeleted": false,
			"id": "fJlOhyPh",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 88.40301840944642,
			"y": 1039.0107967989038,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.239990234375,
			"height": 25,
			"seed": 909878084,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "16Ze9lfUSipUK9dAv523f",
					"type": "arrow"
				}
			],
			"updated": 1708260055114,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x",
			"rawText": "x",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 90,
			"versionNonce": 660813761,
			"isDeleted": false,
			"id": "zxDaGaMs",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -231.40179116086608,
			"y": 748.2971127168726,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 9.379989624023438,
			"height": 25,
			"seed": 1937118788,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "_q_DdgCygyIX4nsONCipx",
					"type": "arrow"
				}
			],
			"updated": 1708260055114,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "y",
			"rawText": "y",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 86,
			"versionNonce": 1566433487,
			"isDeleted": false,
			"id": "k4U2xipY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -817.0980191882098,
			"y": 822.9652340547632,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 250.6196746826172,
			"height": 75,
			"seed": 513625724,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055116,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x = random variable\n\nm = slope of the line rise",
			"rawText": "x = random variable\n\nm = slope of the line rise",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x = random variable\n\nm = slope of the line rise",
			"lineHeight": 1.25,
			"baseline": 67
		},
		{
			"type": "text",
			"version": 61,
			"versionNonce": 411604897,
			"isDeleted": false,
			"id": "kc7mqCoe",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -600.9071012194598,
			"y": 895.6289913789819,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 29.299972534179688,
			"height": 25,
			"seed": 1027312708,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055117,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "run",
			"rawText": "run",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "run",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "line",
			"version": 65,
			"versionNonce": 1763237616,
			"isDeleted": false,
			"id": "P5Gyp1SOqNtMzMUUknGht",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -605.2213712389911,
			"y": 897.0347836153101,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 44.91326904296875,
			"height": 1.095458984375,
			"seed": 699446468,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					44.91326904296875,
					1.095458984375
				]
			]
		},
		{
			"type": "text",
			"version": 91,
			"versionNonce": 61271791,
			"isDeleted": false,
			"id": "3I21eu6P",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -821.3843656237567,
			"y": 935.8697750703882,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 312.51959228515625,
			"height": 25,
			"seed": 674955772,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055119,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "b = y-intercept (crosses y-axis)",
			"rawText": "b = y-intercept (crosses y-axis)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "b = y-intercept (crosses y-axis)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 101,
			"versionNonce": 565640065,
			"isDeleted": false,
			"id": "IxcIVO3g",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -778.7205777819598,
			"y": 967.4381039278101,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 259.419677734375,
			"height": 25,
			"seed": 383066620,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055120,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "y-intercept is where x = 0",
			"rawText": "y-intercept is where x = 0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y-intercept is where x = 0",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 96,
			"versionNonce": 1080558832,
			"isDeleted": false,
			"id": "gueIRIIp",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 135.00171225710267,
			"y": 722.8155758516382,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 157.93943786621094,
			"height": 34.85900878906246,
			"seed": 1519800132,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "BVTBUwFZ0S63kAmhYyvuA",
					"type": "arrow"
				}
			],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"fontSize": 27.887207031249968,
			"fontFamily": 1,
			"text": "y = 2x + 3",
			"rawText": "y = 2x + 3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y = 2x + 3",
			"lineHeight": 1.25,
			"baseline": 24
		},
		{
			"type": "text",
			"version": 79,
			"versionNonce": 1443861880,
			"isDeleted": false,
			"id": "itBLVecu",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 139.27942221804017,
			"y": 773.1062252657007,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 146.15030392108903,
			"height": 33.76354980468749,
			"seed": 1005853892,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "eTqrNcEKQp95zFMAUm5ub",
					"type": "arrow"
				}
			],
			"updated": 1704129676418,
			"link": null,
			"locked": false,
			"fontSize": 27.010839843749995,
			"fontFamily": 1,
			"text": "y = mx + b",
			"rawText": "y = mx + b",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y = mx + b",
			"lineHeight": 1.25,
			"baseline": 23
		},
		{
			"type": "arrow",
			"version": 55,
			"versionNonce": 1283853552,
			"isDeleted": false,
			"id": "Yi2t1z_BMicgKpEBIDEfH",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 316.95434897585267,
			"y": 733.7528317110132,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 92.01739501953125,
			"height": 54.77227783203125,
			"seed": 261655108,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					92.01739501953125,
					-54.77227783203125
				]
			]
		},
		{
			"type": "text",
			"version": 62,
			"versionNonce": 904476943,
			"isDeleted": false,
			"id": "YRObfc7C",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 432.1882967297589,
			"y": 661.9153378145288,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139.57981872558594,
			"height": 25,
			"seed": 1509822204,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055123,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "m = slope = 2",
			"rawText": "m = slope = 2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "m = slope = 2",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 100,
			"versionNonce": 1262194928,
			"isDeleted": false,
			"id": "BrXSaaU07ydRVhepmgXLP",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 314.7634920422589,
			"y": 753.4708187715601,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.10845947265625,
			"height": 36.149688720703125,
			"seed": 1967165436,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					70.10845947265625,
					36.149688720703125
				]
			]
		},
		{
			"type": "text",
			"version": 129,
			"versionNonce": 1663951713,
			"isDeleted": false,
			"id": "fyUhjoOx",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 411.28381674929017,
			"y": 761.8155453340601,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 253.13967895507812,
			"height": 75,
			"seed": 863209340,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055125,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "y-intercept = y = (0) = 3\ny = 3\n(0, 3)",
			"rawText": "y-intercept = y = (0) = 3\ny = 3\n(0, 3)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y-intercept = y = (0) = 3\ny = 3\n(0, 3)",
			"lineHeight": 1.25,
			"baseline": 67
		},
		{
			"type": "text",
			"version": 85,
			"versionNonce": 429735727,
			"isDeleted": false,
			"id": "5rW0wRSp",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -23.056820457741082,
			"y": 757.0107967989038,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 89.31990051269531,
			"height": 50,
			"seed": 1274222972,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "eTqrNcEKQp95zFMAUm5ub",
					"type": "arrow"
				}
			],
			"updated": 1708260055127,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "comparing\n",
			"rawText": "comparing\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "comparing\n",
			"lineHeight": 1.25,
			"baseline": 42
		},
		{
			"type": "arrow",
			"version": 80,
			"versionNonce": 94823952,
			"isDeleted": false,
			"id": "BVTBUwFZ0S63kAmhYyvuA",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 82.85022299929017,
			"y": 764.9762203828882,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 47.1041259765625,
			"height": 20.8134765625,
			"seed": 1110918140,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399788,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "gueIRIIp",
				"focus": 0.6346371128551429,
				"gap": 5.04736328125
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					47.1041259765625,
					-20.8134765625
				]
			]
		},
		{
			"type": "arrow",
			"version": 99,
			"versionNonce": 9478672,
			"isDeleted": false,
			"id": "eTqrNcEKQp95zFMAUm5ub",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 81.75476401491517,
			"y": 777.0261166231226,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 46.00872802734375,
			"height": 19.718017578125,
			"seed": 520386044,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399789,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "5rW0wRSp",
				"focus": -0.6969633289629362,
				"gap": 15.491683959960938
			},
			"endBinding": {
				"elementId": "itBLVecu",
				"focus": -0.8923178733333912,
				"gap": 11.51593017578125
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					46.00872802734375,
					19.718017578125
				]
			]
		},
		{
			"type": "ellipse",
			"version": 143,
			"versionNonce": 2096504048,
			"isDeleted": false,
			"id": "eF7NuOlZObibui5h8hci6",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -241.18017250852233,
			"y": 945.5468380586694,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 24.713684082031246,
			"height": 25.995666503906254,
			"seed": 405478724,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 49,
			"versionNonce": 1228721985,
			"isDeleted": false,
			"id": "Zi7iPxHd",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -293.19347817258483,
			"y": 950.1062252657007,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 47.5799560546875,
			"height": 25,
			"seed": 899035004,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055128,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(0,3)",
			"rawText": "(0,3)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(0,3)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 122,
			"versionNonce": 288063823,
			"isDeleted": false,
			"id": "GstWn8Zt",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -272.1522794421161,
			"y": 1089.1973202364038,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 385.4395751953125,
			"height": 25,
			"seed": 138839236,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055129,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "But we need two points to draw a line",
			"rawText": "But we need two points to draw a line",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "But we need two points to draw a line",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 138,
			"versionNonce": 172179233,
			"isDeleted": false,
			"id": "rILWGE0m",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -230.14355141477233,
			"y": 1127.4880001680444,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 613.2394409179688,
			"height": 25,
			"seed": 1721103812,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055131,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "we can use x = 1, and plug that into the equation of the line",
			"rawText": "we can use x = 1, and plug that into the equation of the line",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "we can use x = 1, and plug that into the equation of the line",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 84,
			"versionNonce": 502038383,
			"isDeleted": false,
			"id": "tq0cqCiW",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 401.37488120241517,
			"y": 1126.3426754610132,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 167.25978088378906,
			"height": 50,
			"seed": 1933025148,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055133,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "y = 2(1) + 3 = 5\n",
			"rawText": "y = 2(1) + 3 = 5\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y = 2(1) + 3 = 5\n",
			"lineHeight": 1.25,
			"baseline": 42
		},
		{
			"type": "ellipse",
			"version": 120,
			"versionNonce": 1154877168,
			"isDeleted": false,
			"id": "VAoqHcYqYGw8fyft7QoJ4",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -91.47088295774108,
			"y": 873.6118405000757,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 20.8134765625,
			"height": 20.813446044921875,
			"seed": 706054980,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 70,
			"versionNonce": 1689301761,
			"isDeleted": false,
			"id": "9YzbM89I",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -104.86590248899108,
			"y": 899.7244503633569,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 47.979949951171875,
			"height": 25,
			"seed": 810578372,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055134,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(1, 5)",
			"rawText": "(1, 5)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(1, 5)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 120,
			"versionNonce": 1465191152,
			"isDeleted": false,
			"id": "aMlSeo0_YQJS_ysnxve6B",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -228.40151650266296,
			"y": 961.2474300996851,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 265.0976867675781,
			"height": 136.93063354492188,
			"seed": 1019004484,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					265.0976867675781,
					-136.93063354492188
				]
			]
		},
		{
			"type": "arrow",
			"version": 48,
			"versionNonce": 810953968,
			"isDeleted": false,
			"id": "59a4rLUBHtNH8NdkauAqm",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -158.37742753714053,
			"y": 919.2863595091353,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 0,
			"height": 70.59536404079859,
			"seed": 1877729276,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "DA0wOrWq"
				}
			],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-70.59536404079859
				]
			]
		},
		{
			"type": "text",
			"version": 26,
			"versionNonce": 1357057776,
			"isDeleted": false,
			"id": "DA0wOrWq",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -165.49742265432803,
			"y": 871.488677488736,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 14.239990234375,
			"height": 25,
			"seed": 747878908,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "59a4rLUBHtNH8NdkauAqm",
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 60,
			"versionNonce": 36223375,
			"isDeleted": false,
			"id": "hLYoxXtV",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 575.2351077276162,
			"y": 662.6893916000641,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 15.41998291015625,
			"height": 25,
			"seed": 1111279684,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055136,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "/1",
			"rawText": "/1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "/1",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 72,
			"versionNonce": 2042630896,
			"isDeleted": false,
			"id": "QCE3SkS7rkRm8PI-dSrSt",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -153.5087887567587,
			"y": 847.4738527274512,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 124.15045844184033,
			"height": 2.4343193901909217,
			"seed": 177532156,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "AZpptPer"
				}
			],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					124.15045844184033,
					-2.4343193901909217
				]
			]
		},
		{
			"type": "text",
			"version": 28,
			"versionNonce": 1612723440,
			"isDeleted": false,
			"id": "AZpptPer",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -94.14355862031118,
			"y": 833.7566930323558,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 916878844,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "QCE3SkS7rkRm8PI-dSrSt",
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 256,
			"versionNonce": 170661616,
			"isDeleted": false,
			"id": "x7tq6iKA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1078.238534808624,
			"y": 580.1589738523169,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 1524.662353515625,
			"height": 35.31005859374999,
			"seed": 1993606724,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"fontSize": 28.248046874999996,
			"fontFamily": 1,
			"text": "The goal of linear regression is to find a line of best fit that reduces the overall squared sum error (SSE)",
			"rawText": "The goal of linear regression is to find a line of best fit that reduces the overall squared sum error (SSE)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The goal of linear regression is to find a line of best fit that reduces the overall squared sum error (SSE)",
			"lineHeight": 1.25,
			"baseline": 24
		},
		{
			"type": "rectangle",
			"version": 121,
			"versionNonce": 208386288,
			"isDeleted": false,
			"id": "v8IW3yCdhqDWFTZ1Cte9_",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1108.3032590015237,
			"y": 574.8816588247432,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 1601.92751716165,
			"height": 47.68407485064341,
			"seed": 1636224324,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 178,
			"versionNonce": 1863018224,
			"isDeleted": false,
			"id": "uPOQeWmWAgY8y6Y4Xg7xF",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1143.9241824639603,
			"y": -178.85805273133928,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 1829.8313395182292,
			"height": 1424.9550374348955,
			"seed": 1539555568,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "lnCk9_L6Ll5CVJ-Wa9IVZ",
					"type": "arrow"
				}
			],
			"updated": 1703960467132,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 58,
			"versionNonce": 1990606064,
			"isDeleted": false,
			"id": "Xwrp0qksBxTuDBPQXJKB9",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -555.0128462009391,
			"y": -121.01854467469866,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 510.0390625,
			"height": 0,
			"seed": 968400912,
			"groupIds": [
				"DdFnhLLlywqp1TamrG8aJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960399718,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					510.0390625,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 301,
			"versionNonce": 486845153,
			"isDeleted": false,
			"id": "x2KoVwEz",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3460.923984547094,
			"y": 272.58531207495764,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 562.1529541015625,
			"height": 45.620117187500014,
			"seed": 1202113604,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055140,
			"link": null,
			"locked": false,
			"fontSize": 36.496093750000014,
			"fontFamily": 1,
			"text": "GENERAL REGRESSION LINES",
			"rawText": "GENERAL REGRESSION LINES",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "GENERAL REGRESSION LINES",
			"lineHeight": 1.25,
			"baseline": 32
		},
		{
			"type": "text",
			"version": 380,
			"versionNonce": 588820399,
			"isDeleted": false,
			"id": "4NnthU52",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3651.6318456219733,
			"y": 345.8158065661503,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 159.57981872558594,
			"height": 25,
			"seed": 509038716,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055141,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "E(y) = Bo + B1x",
			"rawText": "E(y) = Bo + B1x",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "E(y) = Bo + B1x",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 118,
			"versionNonce": 17116688,
			"isDeleted": false,
			"id": "tiMExHeR8QUV7P_eFUXWu",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2998.692418141997,
			"y": 783.413097374563,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 1.288775275735361,
			"height": 278.37194106158086,
			"seed": 120476100,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960415598,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "hm4wrne3",
				"focus": 0.4139645806128341,
				"gap": 1.5307617187504547
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					1.288775275735361,
					-278.37194106158086
				]
			]
		},
		{
			"type": "arrow",
			"version": 151,
			"versionNonce": 1593633296,
			"isDeleted": false,
			"id": "wYX2qs2Aao6jQTnJleJ0H",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2980.6498156029347,
			"y": 773.103038780813,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 376.31760541130507,
			"height": 3.8662540211398664,
			"seed": 1746045180,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960415600,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "3FXfr5cR",
				"focus": 0.13477938816305773,
				"gap": 8.349752987130614
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					376.31760541130507,
					-3.8662540211398664
				]
			]
		},
		{
			"type": "text",
			"version": 76,
			"versionNonce": 1003398849,
			"isDeleted": false,
			"id": "hm4wrne3",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2988.9588904535763,
			"y": 478.5103945942317,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 37.919952392578125,
			"height": 25,
			"seed": 1443587268,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "tiMExHeR8QUV7P_eFUXWu",
					"type": "arrow"
				}
			],
			"updated": 1708260055143,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "E(y)",
			"rawText": "E(y)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "E(y)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 76,
			"versionNonce": 719643087,
			"isDeleted": false,
			"id": "3FXfr5cR",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3365.3171740013704,
			"y": 758.2857852192319,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 11.239990234375,
			"height": 25,
			"seed": 1900018940,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "wYX2qs2Aao6jQTnJleJ0H",
					"type": "arrow"
				}
			],
			"updated": 1708260055143,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x",
			"rawText": "x",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 119,
			"versionNonce": 195962529,
			"isDeleted": false,
			"id": "jDlCHll9",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3047.7288166369403,
			"y": 816.4305318874306,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 168.43980407714844,
			"height": 25,
			"seed": 1847562876,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055144,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "E(y) = Bo + 0(x)",
			"rawText": "E(y) = Bo + 0(x)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "E(y) = Bo + 0(x)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 80,
			"versionNonce": 1789251567,
			"isDeleted": false,
			"id": "e49jrSyA",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2951.3118316300465,
			"y": 657.3874913313641,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 25.619979858398438,
			"height": 25,
			"seed": 1283595516,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055145,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Bo",
			"rawText": "Bo",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Bo",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 127,
			"versionNonce": 1865996528,
			"isDeleted": false,
			"id": "momEAgiF4ktwNJt6UJBpZ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3000.1241592954875,
			"y": 668.7849091852245,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 300.2808335248162,
			"height": 1.288739372702139,
			"seed": 609239932,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960415369,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					300.2808335248162,
					-1.288739372702139
				]
			]
		},
		{
			"type": "text",
			"version": 90,
			"versionNonce": 1465035393,
			"isDeleted": false,
			"id": "6lALi02Y",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3089.9643548952126,
			"y": 858.9008041760335,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 60.59992980957031,
			"height": 25,
			"seed": 1990528324,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055147,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "case 1",
			"rawText": "case 1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "case 1",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 307,
			"versionNonce": 838150160,
			"isDeleted": false,
			"id": "-Y0pXG4knEEfp1VKgRjdR",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3568.8233708648845,
			"y": 773.8351734315477,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 1.288775275735361,
			"height": 278.37194106158086,
			"seed": 888318148,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960415602,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "stw5KyrT",
				"focus": 0.4139645806127846,
				"gap": 1.5307617187504547
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					1.288775275735361,
					-278.37194106158086
				]
			]
		},
		{
			"type": "arrow",
			"version": 347,
			"versionNonce": 926262800,
			"isDeleted": false,
			"id": "tCCU9nz9ovLY7h29y37xe",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3550.780768325822,
			"y": 763.5251148377977,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 376.31760541130507,
			"height": 3.8662540211398664,
			"seed": 631828548,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960415602,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "CN9SiFyS",
				"focus": 0.13477938816303997,
				"gap": 8.349752987131069
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					376.31760541130507,
					-3.8662540211398664
				]
			]
		},
		{
			"type": "text",
			"version": 153,
			"versionNonce": 2086926863,
			"isDeleted": false,
			"id": "stw5KyrT",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3559.089843176463,
			"y": 468.93247065121636,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 37.919952392578125,
			"height": 25,
			"seed": 1193953220,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "-Y0pXG4knEEfp1VKgRjdR",
					"type": "arrow"
				}
			],
			"updated": 1708260055147,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "E(y)",
			"rawText": "E(y)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "E(y)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 153,
			"versionNonce": 1736159841,
			"isDeleted": false,
			"id": "CN9SiFyS",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3935.448126724258,
			"y": 748.7078612762164,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 11.239990234375,
			"height": 25,
			"seed": 1838460740,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "tCCU9nz9ovLY7h29y37xe",
					"type": "arrow"
				}
			],
			"updated": 1708260055147,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x",
			"rawText": "x",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 209,
			"versionNonce": 622321711,
			"isDeleted": false,
			"id": "VKNOKml4",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3633.324857250452,
			"y": 810.7188619655551,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 174.63980102539062,
			"height": 25,
			"seed": 960898756,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055148,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "E(y) = Bo + B1(x)",
			"rawText": "E(y) = Bo + B1(x)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "E(y) = Bo + B1(x)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 188,
			"versionNonce": 1090043457,
			"isDeleted": false,
			"id": "2H2UaQGI",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3526.5978136498084,
			"y": 699.3598962601318,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 25.619979858398438,
			"height": 25,
			"seed": 249343556,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055148,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Bo",
			"rawText": "Bo",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Bo",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 185,
			"versionNonce": 1990853199,
			"isDeleted": false,
			"id": "DVu2q8Gf",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3674.271692039055,
			"y": 851.9004307844884,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 69.419921875,
			"height": 25,
			"seed": 259059012,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055150,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "case 2",
			"rawText": "case 2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "case 2",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 94,
			"versionNonce": 2058374896,
			"isDeleted": false,
			"id": "yNIDHH83i8hilacUwFsqK",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3570.732859318467,
			"y": 714.5958868966211,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 297.7033547794115,
			"height": 195.89136460248164,
			"seed": 602219004,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960415369,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					297.7033547794115,
					-195.89136460248164
				]
			]
		},
		{
			"type": "text",
			"version": 102,
			"versionNonce": 581520929,
			"isDeleted": false,
			"id": "L9NxpG7l",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3723.5205144195697,
			"y": 644.1094726043418,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 151.4798126220703,
			"height": 25,
			"seed": 1968932092,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "slope B1 is +ive",
			"rawText": "slope B1 is +ive",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "slope B1 is +ive",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 398,
			"versionNonce": 2075550736,
			"isDeleted": false,
			"id": "ntkfFl6HbKRSo7XDlI3ai",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4176.058442383726,
			"y": 756.1676857821915,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 1.288775275735361,
			"height": 278.37194106158086,
			"seed": 1496155460,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960415605,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "sCNNXOdU",
				"focus": 0.41396458061281016,
				"gap": 1.5307617187504547
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					1.288775275735361,
					-278.37194106158086
				]
			]
		},
		{
			"type": "arrow",
			"version": 438,
			"versionNonce": 762274320,
			"isDeleted": false,
			"id": "6EEkr-oo_fxdraa7XUD_S",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4158.015839844664,
			"y": 745.8576271884415,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 376.31760541130507,
			"height": 3.8662540211398664,
			"seed": 659832004,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960415605,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "4zwc5Z95",
				"focus": 0.13477938816304,
				"gap": 8.349752987131069
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					376.31760541130507,
					-3.8662540211398664
				]
			]
		},
		{
			"type": "text",
			"version": 190,
			"versionNonce": 838000751,
			"isDeleted": false,
			"id": "sCNNXOdU",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4166.324914695305,
			"y": 451.2649830018602,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 37.919952392578125,
			"height": 25,
			"seed": 2125988932,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "ntkfFl6HbKRSo7XDlI3ai",
					"type": "arrow"
				}
			],
			"updated": 1708260055151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "E(y)",
			"rawText": "E(y)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "E(y)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 190,
			"versionNonce": 1132257793,
			"isDeleted": false,
			"id": "4zwc5Z95",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4542.6831982430995,
			"y": 731.0403736268602,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 11.239990234375,
			"height": 25,
			"seed": 1429658564,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "6EEkr-oo_fxdraa7XUD_S",
					"type": "arrow"
				}
			],
			"updated": 1708260055151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x",
			"rawText": "x",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 254,
			"versionNonce": 1757084303,
			"isDeleted": false,
			"id": "wDT2W6o4",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4239.271153493559,
			"y": 794.3401854949675,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 170.35980224609375,
			"height": 25,
			"seed": 888062788,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "E(y) = Bo - B1(x)",
			"rawText": "E(y) = Bo - B1(x)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "E(y) = Bo - B1(x)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 271,
			"versionNonce": 1349712353,
			"isDeleted": false,
			"id": "de2vAC3S",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4136.410363914055,
			"y": 528.3300895620621,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 25.619979858398438,
			"height": 25,
			"seed": 876460740,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Bo",
			"rawText": "Bo",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Bo",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 235,
			"versionNonce": 1606078639,
			"isDeleted": false,
			"id": "mPXNuUyX",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4286.661864660839,
			"y": 840.6767477077426,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 68.79991149902344,
			"height": 25,
			"seed": 1841414724,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "case 3",
			"rawText": "case 3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "case 3",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 211,
			"versionNonce": 714806721,
			"isDeleted": false,
			"id": "UifyREAi",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4356.5306606167205,
			"y": 577.4691707316401,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 147.19981384277344,
			"height": 25,
			"seed": 1595998532,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055155,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "slope B1 is -ive",
			"rawText": "slope B1 is -ive",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "slope B1 is -ive",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 102,
			"versionNonce": 1415538416,
			"isDeleted": false,
			"id": "KTpA8PcSk6JifZC8rwWvT",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4179.185223174165,
			"y": 533.8072049687712,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 282.23819508272027,
			"height": 153.3623190487133,
			"seed": 500610500,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960415369,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					282.23819508272027,
					153.3623190487133
				]
			]
		},
		{
			"type": "text",
			"version": 332,
			"versionNonce": 815456975,
			"isDeleted": false,
			"id": "kYO7Kysq",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3508.386827630846,
			"y": 920.8177840966616,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 546.7193603515625,
			"height": 75,
			"seed": 1412710012,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055156,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "These are the general types of simple linear regression\nlines that are based on the sign and the value of B1\nwhich is the slope",
			"rawText": "These are the general types of simple linear regression\nlines that are based on the sign and the value of B1\nwhich is the slope",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "These are the general types of simple linear regression\nlines that are based on the sign and the value of B1\nwhich is the slope",
			"lineHeight": 1.25,
			"baseline": 67
		},
		{
			"type": "line",
			"version": 101,
			"versionNonce": 1543924464,
			"isDeleted": false,
			"id": "uY4OJIbEnsu1cjlmX4EyG",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3456.5826445834073,
			"y": 315.95726130636524,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 580.498291015625,
			"height": 0,
			"seed": 1341488144,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960415369,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					580.498291015625,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 172,
			"versionNonce": 1900835568,
			"isDeleted": false,
			"id": "ksJ2rROzAUB4zgPfQCtJI",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2917.0977813021573,
			"y": 256.0144512477715,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 1675.2421875000002,
			"height": 763.4815063476564,
			"seed": 1241404144,
			"groupIds": [
				"OayPZxv6VZtr2NsCc9scc"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "65-IHiJtdjA7xX5c9VnNU",
					"type": "arrow"
				}
			],
			"updated": 1703960446600,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 307,
			"versionNonce": 2076045320,
			"isDeleted": false,
			"id": "jiwMJG5B",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1479.954986130025,
			"y": -354.1799054524569,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 535.5465087890625,
			"height": 61.20711430397402,
			"seed": 2060906436,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1704129676466,
			"link": null,
			"locked": false,
			"fontSize": 48.96569144317922,
			"fontFamily": 1,
			"text": "linear regression model",
			"rawText": "linear regression model",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "linear regression model",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 175,
			"versionNonce": 459207800,
			"isDeleted": false,
			"id": "V7At6pYL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1015.9490437126967,
			"y": -126.7079228866964,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 189.58232578683086,
			"height": 43.7971877379621,
			"seed": 1740097348,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1704129676467,
			"link": null,
			"locked": false,
			"fontSize": 35.03775019036968,
			"fontFamily": 1,
			"text": "y = mx + b",
			"rawText": "y = mx + b",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y = mx + b",
			"lineHeight": 1.25,
			"baseline": 30
		},
		{
			"type": "text",
			"version": 213,
			"versionNonce": 1306738959,
			"isDeleted": false,
			"id": "olckQGJx",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1275.973602618965,
			"y": -249.673990360985,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 211.69247436523438,
			"height": 30.360584875522466,
			"seed": 120363260,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260065061,
			"link": null,
			"locked": false,
			"fontSize": 24.288467900417974,
			"fontFamily": 1,
			"text": "y = Bo + B1x + e",
			"rawText": "y = Bo + B1x + e",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y = Bo + B1x + e",
			"lineHeight": 1.25,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 121,
			"versionNonce": 965071888,
			"isDeleted": false,
			"id": "DhEm7dKBIySjDypF-xHvx",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 975.0525620337987,
			"y": -129.90214673519694,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 273.28471936677624,
			"height": 58.80811189350328,
			"seed": 222824772,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "zQcRFUOS759WtAZdhatVg",
					"type": "arrow"
				},
				{
					"id": "23MJ-gEHT-GHD54Zvx6mX",
					"type": "arrow"
				}
			],
			"updated": 1704018971855,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 221,
			"versionNonce": 841977360,
			"isDeleted": false,
			"id": "syBG-RTk1TO4bDCRy6yLP",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1251.566011719414,
			"y": -261.3555276545363,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 266.3660310444076,
			"height": 48.43017578125,
			"seed": 1626922748,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "zQcRFUOS759WtAZdhatVg",
					"type": "arrow"
				}
			],
			"updated": 1704018971855,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 475,
			"versionNonce": 372474608,
			"isDeleted": false,
			"id": "zQcRFUOS759WtAZdhatVg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1226.792068981637,
			"y": -136.82077081003257,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 38.11432736576762,
			"height": 66.87979179516162,
			"seed": 225477444,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018972274,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "DhEm7dKBIySjDypF-xHvx",
				"focus": 0.6153676433893831,
				"gap": 6.918624074835634
			},
			"endBinding": {
				"elementId": "syBG-RTk1TO4bDCRy6yLP",
				"focus": 0.6856946754206976,
				"gap": 9.224789268092081
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					38.11432736576762,
					-66.87979179516162
				]
			]
		},
		{
			"type": "text",
			"version": 221,
			"versionNonce": 1695856033,
			"isDeleted": false,
			"id": "XbfX7Cou",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1385.0271681964218,
			"y": -168.0961619704286,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 378.6995849609375,
			"height": 25,
			"seed": 276057724,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055161,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Bo = y-intercept population parameter",
			"rawText": "Bo = y-intercept population parameter",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Bo = y-intercept population parameter",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 175,
			"versionNonce": 737390831,
			"isDeleted": false,
			"id": "OFnpSW7U",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1385.07972267833,
			"y": -127.83930434938634,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 347.53955078125,
			"height": 25,
			"seed": 1088680956,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055162,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "B1 = slope of population parameter",
			"rawText": "B1 = slope of population parameter",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "B1 = slope of population parameter",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 142,
			"versionNonce": 1706580833,
			"isDeleted": false,
			"id": "U7Tuvel0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 967.6360195790289,
			"y": 66.11550206208904,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 390.1361083984375,
			"height": 29.61239463404606,
			"seed": 1704931580,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "23MJ-gEHT-GHD54Zvx6mX",
					"type": "arrow"
				}
			],
			"updated": 1708260065064,
			"link": null,
			"locked": false,
			"fontSize": 23.689915707236846,
			"fontFamily": 1,
			"text": "Simple Linear Regression Equation",
			"rawText": "Simple Linear Regression Equation",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Simple Linear Regression Equation",
			"lineHeight": 1.25,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 91,
			"versionNonce": 2068691727,
			"isDeleted": false,
			"id": "C9RPoMUl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 981.0233422558381,
			"y": 119.09645909333904,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 159.57981872558594,
			"height": 25,
			"seed": 1828536516,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055164,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "E(y) = Bo + B1x",
			"rawText": "E(y) = Bo + B1x",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "E(y) = Bo + B1x",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 104,
			"versionNonce": 238321168,
			"isDeleted": false,
			"id": "55X07iOHrXqxp71e6oHoo",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 956.7034666390618,
			"y": 114.3312517023029,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 226.00759405838812,
			"height": 32.28682668585526,
			"seed": 135606468,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1704018971855,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 207,
			"versionNonce": 1025129488,
			"isDeleted": false,
			"id": "te8GILNY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 948.033262074917,
			"y": 163.40737217927636,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 488.798828125,
			"height": 19.234490645559244,
			"seed": 13458756,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1704018971855,
			"link": null,
			"locked": false,
			"fontSize": 15.387592516447395,
			"fontFamily": 1,
			"text": "E(y) is the mean or expected value of y, for a given value of x",
			"rawText": "E(y) is the mean or expected value of y, for a given value of x",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "E(y) is the mean or expected value of y, for a given value of x",
			"lineHeight": 1.25,
			"baseline": 13
		},
		{
			"type": "arrow",
			"version": 154,
			"versionNonce": 1150827024,
			"isDeleted": false,
			"id": "FBkty2W643WaHmGznL-VV",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1546.3328761614011,
			"y": 473.32488905496194,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 4.612330386513349,
			"height": 354.00175395764813,
			"seed": 1061210236,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018971855,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-4.612330386513349,
					-354.00175395764813
				]
			]
		},
		{
			"type": "arrow",
			"version": 221,
			"versionNonce": 2091230448,
			"isDeleted": false,
			"id": "v9xb0Dr1exSaaH8tq2FGk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1521.067341107946,
			"y": 464.0109242112117,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 450.8621376439146,
			"height": 4.612394634046041,
			"seed": 1491349188,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018972277,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "jKAoCKbw",
				"focus": 0.25869457097722215,
				"gap": 13.23389956825622
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					450.8621376439146,
					-4.612394634046041
				]
			]
		},
		{
			"type": "text",
			"version": 94,
			"versionNonce": 1976205665,
			"isDeleted": false,
			"id": "jKAoCKbw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1985.1633783201169,
			"y": 449.95420648917224,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.239990234375,
			"height": 25,
			"seed": 1680758780,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "v9xb0Dr1exSaaH8tq2FGk",
					"type": "arrow"
				}
			],
			"updated": 1708260055167,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x",
			"rawText": "x",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 123,
			"versionNonce": 52527407,
			"isDeleted": false,
			"id": "JUIhwbKi",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1538.1443995988998,
			"y": 78.02138370956703,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 9.379989624023438,
			"height": 25,
			"seed": 1393258236,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055167,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "y",
			"rawText": "y",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "ellipse",
			"version": 103,
			"versionNonce": 1709305872,
			"isDeleted": false,
			"id": "8gaAMC0ltj7aFEEvOaf_P",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1675.582721967321,
			"y": 314.1078737383499,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 19.60275750411165,
			"height": 18.44961065995068,
			"seed": 1087532868,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018971856,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 155,
			"versionNonce": 1648979472,
			"isDeleted": false,
			"id": "iLxayvbU8o9lfUHocBey_",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1683.6544607625515,
			"y": 338.32299375274147,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 2.3062294407895934,
			"height": 126.84101305509859,
			"seed": 1381758916,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018971856,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.3062294407895934,
					126.84101305509859
				]
			]
		},
		{
			"type": "line",
			"version": 146,
			"versionNonce": 554773520,
			"isDeleted": false,
			"id": "epNEL0VonLF4A4dO8O5Bj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1542.9762638053148,
			"y": 329.09820448464933,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 127.99412777549333,
			"height": 3.4592799136513577,
			"seed": 1895942140,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018971856,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					127.99412777549333,
					-3.4592799136513577
				]
			]
		},
		{
			"type": "line",
			"version": 134,
			"versionNonce": 1815161360,
			"isDeleted": false,
			"id": "qiynx5Pj1TqrDKEoaC7Xs",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1548.7417089122227,
			"y": 345.24161782757693,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 127.99412777549333,
			"height": 3.45931203741776,
			"seed": 1540079484,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018971856,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					127.99412777549333,
					-3.45931203741776
				]
			]
		},
		{
			"type": "line",
			"version": 120,
			"versionNonce": 245458960,
			"isDeleted": false,
			"id": "T4ft0YKARR3AaGQ2hbyuH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1549.8948236326173,
			"y": 316.41410317913943,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 125.68789833470373,
			"height": 2.3061973170230203,
			"seed": 236289988,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018971856,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					125.68789833470373,
					-2.3061973170230203
				]
			]
		},
		{
			"type": "text",
			"version": 110,
			"versionNonce": 1519758657,
			"isDeleted": false,
			"id": "E9H3t3Y4",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1497.1921869138669,
			"y": 321.4327349636789,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 37.919952392578125,
			"height": 25,
			"seed": 680072572,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055167,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "E(y)",
			"rawText": "E(y)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "E(y)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 787,
			"versionNonce": 1809771272,
			"isDeleted": false,
			"id": "spsB73kd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1744.5651695413321,
			"y": 490.74881997601443,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 657.2518310546875,
			"height": 123.56266465244065,
			"seed": 742625476,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1704129676534,
			"link": null,
			"locked": false,
			"fontSize": 16.475021953658754,
			"fontFamily": 1,
			"text": "Lets say we pick a value of x, that corresponds to an expected value of y\nit is really not that simple, there is actually a distribution of ys for that x.\nRemember our regression model is not perfect, so any expected value of y we\ncome up with, is at best going to be an approximation. So when we say the \nexpected value, we mean is that it is the mean of a small distribution for that\ny. We want to have the expected value of our y in a narrower range",
			"rawText": "Lets say we pick a value of x, that corresponds to an expected value of y\nit is really not that simple, there is actually a distribution of ys for that x.\nRemember our regression model is not perfect, so any expected value of y we\ncome up with, is at best going to be an approximation. So when we say the \nexpected value, we mean is that it is the mean of a small distribution for that\ny. We want to have the expected value of our y in a narrower range",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Lets say we pick a value of x, that corresponds to an expected value of y\nit is really not that simple, there is actually a distribution of ys for that x.\nRemember our regression model is not perfect, so any expected value of y we\ncome up with, is at best going to be an approximation. So when we say the \nexpected value, we mean is that it is the mean of a small distribution for that\ny. We want to have the expected value of our y in a narrower range",
			"lineHeight": 1.25,
			"baseline": 117
		},
		{
			"type": "arrow",
			"version": 186,
			"versionNonce": 1585685008,
			"isDeleted": false,
			"id": "x98knIhqoShUDVihdDOU3",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2158.4923578123035,
			"y": 458.3748736355538,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 4.612330386513349,
			"height": 354.00175395764813,
			"seed": 1777255932,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018971856,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-4.612330386513349,
					-354.00175395764813
				]
			]
		},
		{
			"type": "arrow",
			"version": 297,
			"versionNonce": 1417905904,
			"isDeleted": false,
			"id": "mYsg5q9QaWla4xVJcSxrH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2133.2268227588484,
			"y": 449.06090879180357,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 450.8621376439146,
			"height": 4.612394634046041,
			"seed": 1620878972,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018972279,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "bAjPI1xq",
				"focus": 0.2586945709772319,
				"gap": 13.23389956825713
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					450.8621376439146,
					-4.612394634046041
				]
			]
		},
		{
			"type": "text",
			"version": 126,
			"versionNonce": 81232719,
			"isDeleted": false,
			"id": "bAjPI1xq",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2597.32285997102,
			"y": 435.0041910697642,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.239990234375,
			"height": 25,
			"seed": 2008708860,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "mYsg5q9QaWla4xVJcSxrH",
					"type": "arrow"
				}
			],
			"updated": 1708260055170,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x",
			"rawText": "x",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 155,
			"versionNonce": 2026921249,
			"isDeleted": false,
			"id": "AH39xiUt",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2150.3038812498025,
			"y": 63.071368290158944,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 9.379989624023438,
			"height": 25,
			"seed": 2076850044,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055170,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "y",
			"rawText": "y",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "ellipse",
			"version": 135,
			"versionNonce": 1470912528,
			"isDeleted": false,
			"id": "foknLlHWVvzlxJsrv1wVm",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2287.7422036182234,
			"y": 299.15785831894175,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 19.60275750411165,
			"height": 18.44961065995068,
			"seed": 1494083580,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018971856,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 187,
			"versionNonce": 2122765840,
			"isDeleted": false,
			"id": "iN6bp5diEwmQX8-sWWTt7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2295.8139424134542,
			"y": 323.37297833333344,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 2.3062294407895934,
			"height": 126.84101305509859,
			"seed": 596084860,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018971856,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.3062294407895934,
					126.84101305509859
				]
			]
		},
		{
			"type": "line",
			"version": 178,
			"versionNonce": 560043024,
			"isDeleted": false,
			"id": "dRMNnmqDq-Gk5Kg4pF6D1",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2155.1357454562176,
			"y": 314.14818906524124,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 127.99412777549333,
			"height": 3.4592799136513577,
			"seed": 519641340,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018971856,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					127.99412777549333,
					-3.4592799136513577
				]
			]
		},
		{
			"type": "line",
			"version": 178,
			"versionNonce": 1446285840,
			"isDeleted": false,
			"id": "EhJzxSEtwXTpnJyadVlHi",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2159.748075842731,
			"y": 342.9757037136787,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 127.99412777549333,
			"height": 3.45931203741776,
			"seed": 1189386620,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018971856,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					127.99412777549333,
					-3.45931203741776
				]
			]
		},
		{
			"type": "line",
			"version": 169,
			"versionNonce": 871878672,
			"isDeleted": false,
			"id": "QfY1MIkfVMwXsweaKCo13",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2160.9012548106584,
			"y": 280.70827978275764,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 125.68789833470373,
			"height": 2.3061973170230203,
			"seed": 1452018172,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018971856,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					125.68789833470373,
					-2.3061973170230203
				]
			]
		},
		{
			"type": "text",
			"version": 142,
			"versionNonce": 13123951,
			"isDeleted": false,
			"id": "JNy64mO1",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2109.35166856477,
			"y": 306.4827195442708,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 37.919952392578125,
			"height": 25,
			"seed": 1357998716,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055170,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "E(y)",
			"rawText": "E(y)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "E(y)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 315,
			"versionNonce": 187632656,
			"isDeleted": false,
			"id": "rFv08jFd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1601.8000520968417,
			"y": 157.61248028645826,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 342.29034423828125,
			"height": 17.55529759435921,
			"seed": 1881524804,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1704018971856,
			"link": null,
			"locked": false,
			"fontSize": 14.04423807548737,
			"fontFamily": 1,
			"text": "smaller range of expected y values, better model",
			"rawText": "smaller range of expected y values, better model",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "smaller range of expected y values, better model",
			"lineHeight": 1.25,
			"baseline": 12
		},
		{
			"type": "text",
			"version": 226,
			"versionNonce": 114673928,
			"isDeleted": false,
			"id": "BUrOvFDl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2285.905437325049,
			"y": 185.44229499657337,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 291.83282470703125,
			"height": 16.024978626507906,
			"seed": 1572079100,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1704129676537,
			"link": null,
			"locked": false,
			"fontSize": 12.819982901206325,
			"fontFamily": 1,
			"text": "Larger range of expected y values, bad model",
			"rawText": "Larger range of expected y values, bad model",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Larger range of expected y values, bad model",
			"lineHeight": 1.25,
			"baseline": 11
		},
		{
			"type": "text",
			"version": 276,
			"versionNonce": 890652463,
			"isDeleted": false,
			"id": "dMv8519p",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1693.6457338059981,
			"y": 635.9425744733417,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 867.45068359375,
			"height": 21.367686416824377,
			"seed": 1324813252,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260065076,
			"link": null,
			"locked": false,
			"fontSize": 17.094149133459503,
			"fontFamily": 1,
			"text": "But note that the expected value of y is really just the mean of the distribution of those y values.",
			"rawText": "But note that the expected value of y is really just the mean of the distribution of those y values.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "But note that the expected value of y is really just the mean of the distribution of those y values.",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "arrow",
			"version": 236,
			"versionNonce": 2040695536,
			"isDeleted": false,
			"id": "23MJ-gEHT-GHD54Zvx6mX",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1114.7309772796184,
			"y": -58.27842380790884,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.3208907277960407,
			"height": 116.2324925472862,
			"seed": 1516761104,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018972281,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "DhEm7dKBIySjDypF-xHvx",
				"focus": -0.01330928288064608,
				"gap": 12.815611033784819
			},
			"endBinding": {
				"elementId": "U7Tuvel0",
				"focus": -0.22505371792362586,
				"gap": 8.161433322711666
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					3.3208907277960407,
					116.2324925472862
				]
			]
		},
		{
			"type": "line",
			"version": 129,
			"versionNonce": 1182827536,
			"isDeleted": false,
			"id": "YwR5Rb8ukvmVVkCSfsFx5",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1428.7665036891021,
			"y": -288.45327279943695,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 641.4926147460938,
			"height": 0,
			"seed": 1936520208,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018971856,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					641.4926147460938,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 139,
			"versionNonce": 1229820656,
			"isDeleted": false,
			"id": "12sX72-6dnJxejh3-rE8_",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 910.8399696721749,
			"y": -372.58347096024426,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 1748.3304850260424,
			"height": 1048.9982096354167,
			"seed": 765293808,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "65-IHiJtdjA7xX5c9VnNU",
					"type": "arrow"
				},
				{
					"id": "lnCk9_L6Ll5CVJ-Wa9IVZ",
					"type": "arrow"
				},
				{
					"id": "4JB3WKShh3AxHqF6oYGRR",
					"type": "arrow"
				},
				{
					"id": "wOXOjUn6rH4utfciDZYiV",
					"type": "arrow"
				}
			],
			"updated": 1704018972282,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 231,
			"versionNonce": 640097296,
			"isDeleted": false,
			"id": "95ZAlc12",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2108.8859355971917,
			"y": 1264.6369432259708,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 783.5438232421875,
			"height": 43.779035295759066,
			"seed": 502857340,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703960436007,
			"link": null,
			"locked": false,
			"fontSize": 35.02322823660725,
			"fontFamily": 1,
			"text": "REGRESSION EQUATION WITH ESTIMATES",
			"rawText": "REGRESSION EQUATION WITH ESTIMATES",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "REGRESSION EQUATION WITH ESTIMATES",
			"lineHeight": 1.25,
			"baseline": 30
		},
		{
			"type": "text",
			"version": 171,
			"versionNonce": 2146046209,
			"isDeleted": false,
			"id": "6CA0lzIQ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1657.472448571522,
			"y": 1356.8149827767522,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1086.1788330078125,
			"height": 25,
			"seed": 482365052,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055178,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "If we actually knew the population parameters, Bo and B1, we could use the simple linear regression equation",
			"rawText": "If we actually knew the population parameters, Bo and B1, we could use the simple linear regression equation",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "If we actually knew the population parameters, Bo and B1, we could use the simple linear regression equation",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 120,
			"versionNonce": 1480342415,
			"isDeleted": false,
			"id": "WCCL60S4",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2121.6993947210754,
			"y": 1424.7759289960602,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 212.78721618652344,
			"height": 33.33554610568162,
			"seed": 1208894404,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055178,
			"link": null,
			"locked": false,
			"fontSize": 26.6684368845453,
			"fontFamily": 1,
			"text": "E(y) = Bo + B1x",
			"rawText": "E(y) = Bo + B1x",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "E(y) = Bo + B1x",
			"lineHeight": 1.25,
			"baseline": 23
		},
		{
			"type": "text",
			"version": 289,
			"versionNonce": 90327265,
			"isDeleted": false,
			"id": "hmnCsreq",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1621.135255491165,
			"y": 1486.9451620457255,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1223.098876953125,
			"height": 50,
			"seed": 1791898748,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055180,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "In reality we almost never have the population parameters. Therefore we will estimate them using sample data. When using\nsample data, we have to change our equation a little bit.",
			"rawText": "In reality we almost never have the population parameters. Therefore we will estimate them using sample data. When using\nsample data, we have to change our equation a little bit.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "In reality we almost never have the population parameters. Therefore we will estimate them using sample data. When using\nsample data, we have to change our equation a little bit.",
			"lineHeight": 1.25,
			"baseline": 42
		},
		{
			"type": "text",
			"version": 146,
			"versionNonce": 1559270416,
			"isDeleted": false,
			"id": "cu8X5kXh",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2132.7901801563435,
			"y": 1557.0101208905921,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 214.08529663085938,
			"height": 43.77907889229892,
			"seed": 1913204932,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "UlMMb24DLPnID3toZTcEm",
					"type": "arrow"
				}
			],
			"updated": 1703960436007,
			"link": null,
			"locked": false,
			"fontSize": 35.023263113839135,
			"fontFamily": 1,
			"text": "y = bo + b1x",
			"rawText": "y = bo + b1x",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y = bo + b1x",
			"lineHeight": 1.25,
			"baseline": 30
		},
		{
			"type": "text",
			"version": 192,
			"versionNonce": 795603375,
			"isDeleted": false,
			"id": "pqnhKhSS",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1498.7925518081292,
			"y": 1615.7304316467275,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 315.8796081542969,
			"height": 25,
			"seed": 681754620,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055183,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "y is the point estimator of E(y)",
			"rawText": "y is the point estimator of E(y)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y is the point estimator of E(y)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 188,
			"versionNonce": 1120437441,
			"isDeleted": false,
			"id": "m8eMYSB2",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1484.7082535380398,
			"y": 1658.1072278241827,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 475.8394775390625,
			"height": 25,
			"seed": 349767804,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055184,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "y is the mean value of y for a given value of x",
			"rawText": "y is the mean value of y for a given value of x",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y is the mean value of y for a given value of x",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 116,
			"versionNonce": 121506832,
			"isDeleted": false,
			"id": "k5ewXSoABSSNsw5hISLXj",
			"fillStyle": "solid",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1461.8389908427275,
			"y": 1597.2832096182674,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 525.8136858258927,
			"height": 112.67438616071468,
			"seed": 120788804,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "UlMMb24DLPnID3toZTcEm",
					"type": "arrow"
				}
			],
			"updated": 1703960436007,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 223,
			"versionNonce": 368802032,
			"isDeleted": false,
			"id": "UlMMb24DLPnID3toZTcEm",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2007.9966533706292,
			"y": 1655.1853005083349,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 109.54450334821422,
			"height": 71.98638916015625,
			"seed": 1374858308,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436354,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "k5ewXSoABSSNsw5hISLXj",
				"focus": 0.819281650815779,
				"gap": 20.34397670200906
			},
			"endBinding": {
				"elementId": "cu8X5kXh",
				"focus": 0.8247026051113338,
				"gap": 15.2490234375
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					109.54450334821422,
					-71.98638916015625
				]
			]
		},
		{
			"type": "text",
			"version": 298,
			"versionNonce": 993183248,
			"isDeleted": false,
			"id": "vAsqGVEj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1977.9131223996455,
			"y": 1726.5996158682624,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 711.3416748046875,
			"height": 43.77903529575861,
			"seed": 26197188,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703960436007,
			"link": null,
			"locked": false,
			"fontSize": 35.02322823660689,
			"fontFamily": 1,
			"text": "GETTING READY FOR LEAST SQUARES",
			"rawText": "GETTING READY FOR LEAST SQUARES",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "GETTING READY FOR LEAST SQUARES",
			"lineHeight": 1.25,
			"baseline": 30
		},
		{
			"type": "text",
			"version": 268,
			"versionNonce": 260039631,
			"isDeleted": false,
			"id": "69tOxX0j",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1893.3044449442896,
			"y": 1800.59323333478,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 870.4190673828125,
			"height": 25,
			"seed": 1441221828,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055187,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Going back to our previous example, we now add the bill price of the meal to our data.",
			"rawText": "Going back to our previous example, we now add the bill price of the meal to our data.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Going back to our previous example, we now add the bill price of the meal to our data.",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 290,
			"versionNonce": 331105441,
			"isDeleted": false,
			"id": "EYQCjqvR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2537.302247678663,
			"y": 2051.053351219825,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 279.450927734375,
			"height": 254.8763655044115,
			"seed": 2035532100,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055189,
			"link": null,
			"locked": false,
			"fontSize": 29.12872748621846,
			"fontFamily": 1,
			"text": "Bill($)       Tip($)\n34.00        5.00\n108.00       17.00\n64.00        11.00\n88.00       8.00\n99.00        14.00\n51.00         5.00",
			"rawText": "Bill($)       Tip($)\n34.00        5.00\n108.00       17.00\n64.00        11.00\n88.00       8.00\n99.00        14.00\n51.00         5.00",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Bill($)       Tip($)\n34.00        5.00\n108.00       17.00\n64.00        11.00\n88.00       8.00\n99.00        14.00\n51.00         5.00",
			"lineHeight": 1.25,
			"baseline": 244
		},
		{
			"type": "arrow",
			"version": 628,
			"versionNonce": 793115888,
			"isDeleted": false,
			"id": "O07i8LnBIhQgIRyJhF3Ws",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1698.2174786501123,
			"y": 2391.5060576930387,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.27156778162589035,
			"height": 447.5676618303569,
			"seed": 538380028,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436355,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "mvTGKhgY",
				"focus": 0.03615812123033649,
				"gap": 12.190464564732338
			},
			"endBinding": {
				"elementId": "Rkyl10kw",
				"focus": -0.17236832415939618,
				"gap": 12.778363909040763
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-0.27156778162589035,
					-447.5676618303569
				]
			]
		},
		{
			"type": "text",
			"version": 254,
			"versionNonce": 1217434095,
			"isDeleted": false,
			"id": "Rkyl10kw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1612.4988898731385,
			"y": 1906.160031953641,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 145.7398223876953,
			"height": 25,
			"seed": 1995511620,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "O07i8LnBIhQgIRyJhF3Ws",
					"type": "arrow"
				}
			],
			"updated": 1708260055190,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "tip amount ($)",
			"rawText": "tip amount ($)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "tip amount ($)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 123,
			"versionNonce": 1049295376,
			"isDeleted": false,
			"id": "O6N3lB4MZZkcBkjTJ59OS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1685.4831820397121,
			"y": 2370.207665533441,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 852.8822544642856,
			"height": 4.694737025669838,
			"seed": 877624444,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436007,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					852.8822544642856,
					-4.694737025669838
				]
			]
		},
		{
			"type": "text",
			"version": 126,
			"versionNonce": 871172225,
			"isDeleted": false,
			"id": "JH5GhhbR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2025.7774586859168,
			"y": 2465.3390655055387,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139.6398468017578,
			"height": 25,
			"seed": 426028284,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055190,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Bill amount($)",
			"rawText": "Bill amount($)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Bill amount($)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 55,
			"versionNonce": 329677839,
			"isDeleted": false,
			"id": "mvTGKhgY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1683.7259798912746,
			"y": 2403.696522257771,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 27.999984741210938,
			"height": 25,
			"seed": 903852668,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "O07i8LnBIhQgIRyJhF3Ws",
					"type": "arrow"
				}
			],
			"updated": 1708260055191,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "20",
			"rawText": "20",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "20",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 111,
			"versionNonce": 1025134689,
			"isDeleted": false,
			"id": "863WO49I",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1822.089801738373,
			"y": 2402.8783023917003,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.559982299804688,
			"height": 25,
			"seed": 1408317636,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055192,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "40",
			"rawText": "40",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "40",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 72,
			"versionNonce": 1958355503,
			"isDeleted": false,
			"id": "QP9CTFit",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1969.849375538596,
			"y": 2404.170591035673,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.559982299804688,
			"height": 25,
			"seed": 750861892,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055193,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "60",
			"rawText": "60",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "60",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 94,
			"versionNonce": 1695784001,
			"isDeleted": false,
			"id": "VqcXtv1p",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2131.758206453774,
			"y": 2402.742106800182,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 29.059982299804688,
			"height": 25,
			"seed": 1465766852,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055194,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "80",
			"rawText": "80",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "80",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 77,
			"versionNonce": 1555301455,
			"isDeleted": false,
			"id": "zDqdM3Xz",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2293.0379828907166,
			"y": 2400.969558669602,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 32.93998718261719,
			"height": 25,
			"seed": 1374484804,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055195,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "100",
			"rawText": "100",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "100",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 70,
			"versionNonce": 2075683873,
			"isDeleted": false,
			"id": "iQUnCBM0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2465.8301669029934,
			"y": 2400.0862927655835,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 33.41998291015625,
			"height": 25,
			"seed": 222183420,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055195,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "120",
			"rawText": "120",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "120",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 93,
			"versionNonce": 191668847,
			"isDeleted": false,
			"id": "cZegTbor",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1652.446203454333,
			"y": 2364.3194296238435,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 108004548,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055196,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "4",
			"rawText": "4",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 97,
			"versionNonce": 687357953,
			"isDeleted": false,
			"id": "uWkh5c2A",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1657.2834575698466,
			"y": 2295.9556077767456,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 201870460,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055197,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "6",
			"rawText": "6",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "6",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 125,
			"versionNonce": 833387663,
			"isDeleted": false,
			"id": "exeZe884",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1654.6464336440652,
			"y": 2227.6569191606736,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 15.29998779296875,
			"height": 25,
			"seed": 316391292,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055197,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "8",
			"rawText": "8",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "8",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 124,
			"versionNonce": 1792186337,
			"isDeleted": false,
			"id": "1JCiIpdW",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1653.6393099693998,
			"y": 2168.812750633888,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.17999267578125,
			"height": 25,
			"seed": 619848060,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055198,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "10",
			"rawText": "10",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "10",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 124,
			"versionNonce": 1395397295,
			"isDeleted": false,
			"id": "8Hxpjr79",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1653.0877265430604,
			"y": 2106.516346476523,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.659988403320312,
			"height": 25,
			"seed": 2004988924,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055199,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "12",
			"rawText": "12",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "12",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 128,
			"versionNonce": 1398207425,
			"isDeleted": false,
			"id": "FZ3Ym0xe",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1654.4760365667773,
			"y": 2043.9722267778611,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.219985961914062,
			"height": 25,
			"seed": 464781124,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055200,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "16",
			"rawText": "16",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "16",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 91,
			"versionNonce": 1754522831,
			"isDeleted": false,
			"id": "zv6I2mG0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1655.7745159194558,
			"y": 1977.5823690769694,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.719985961914062,
			"height": 25,
			"seed": 2042734972,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055201,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "18",
			"rawText": "18",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "18",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "ellipse",
			"version": 58,
			"versionNonce": 340580880,
			"isDeleted": false,
			"id": "mNY7wVcA4g25Sqs8GKo-e",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1769.130642977213,
			"y": 2329.6746542332194,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 2069215996,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436007,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 83,
			"versionNonce": 398923792,
			"isDeleted": false,
			"id": "nJiJVAqT7cFbkPH1rcm5u",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1911.1415333929501,
			"y": 2332.8149566188213,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 365749628,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436007,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 189,
			"versionNonce": 1833539088,
			"isDeleted": false,
			"id": "8-oX5YsuxYDGm6BAUakPj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2397.6835430190654,
			"y": 1996.415725661791,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 429064004,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436007,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 140,
			"versionNonce": 701256720,
			"isDeleted": false,
			"id": "KMZXMKl5lpyOjCDUaOSkg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2225.665938736142,
			"y": 2216.9208787728394,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 857864188,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436007,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 172,
			"versionNonce": 55005712,
			"isDeleted": false,
			"id": "8-rrDB9iK3CR-OJPWOUs1",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2279.4651156334635,
			"y": 2061.590765770608,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 850569596,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436007,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 119,
			"versionNonce": 817008656,
			"isDeleted": false,
			"id": "5GG14r2hAXXB3_RshMIOM",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2070.6426581836868,
			"y": 2092.8365805027506,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 1755237116,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436007,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1073,
			"versionNonce": 1241910800,
			"isDeleted": false,
			"id": "1NjZEn3x",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1565.7144035566384,
			"y": 2505.11702832641,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 752.5128784179688,
			"height": 465.1007254464271,
			"seed": 1040110972,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703960436007,
			"link": null,
			"locked": false,
			"fontSize": 23.255036272321355,
			"fontFamily": 1,
			"text": "Graphing the data on a scatter plot, \nThe tip dollar amount depends on the original\nbill amount. This is what we think and hypothesizing.\nso general, a lower bill will result in a lower tip and \na more expensive meal will result in a higher tip.\n\nLooking at the scatter plot, it appears there is some \nkind of linear relationship that goes form left to right.\n\nSo if we drew a line it would probably start at the lower left\nand go to the upper right.\n\nAnd most importantly, if that line reduces the residual sum of \nsquare significantly from the model where we only used the mean\nof the tip, that is when we say our regression model is \"good\" in \na qualitative sense.",
			"rawText": "Graphing the data on a scatter plot, \nThe tip dollar amount depends on the original\nbill amount. This is what we think and hypothesizing.\nso general, a lower bill will result in a lower tip and \na more expensive meal will result in a higher tip.\n\nLooking at the scatter plot, it appears there is some \nkind of linear relationship that goes form left to right.\n\nSo if we drew a line it would probably start at the lower left\nand go to the upper right.\n\nAnd most importantly, if that line reduces the residual sum of \nsquare significantly from the model where we only used the mean\nof the tip, that is when we say our regression model is \"good\" in \na qualitative sense.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Graphing the data on a scatter plot, \nThe tip dollar amount depends on the original\nbill amount. This is what we think and hypothesizing.\nso general, a lower bill will result in a lower tip and \na more expensive meal will result in a higher tip.\n\nLooking at the scatter plot, it appears there is some \nkind of linear relationship that goes form left to right.\n\nSo if we drew a line it would probably start at the lower left\nand go to the upper right.\n\nAnd most importantly, if that line reduces the residual sum of \nsquare significantly from the model where we only used the mean\nof the tip, that is when we say our regression model is \"good\" in \na qualitative sense.",
			"lineHeight": 1.25,
			"baseline": 456
		},
		{
			"type": "text",
			"version": 123,
			"versionNonce": 144590456,
			"isDeleted": false,
			"id": "vMmhIJWR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1939.2616230003791,
			"y": 1850.2883486770988,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 512.8851318359375,
			"height": 49.0000261579239,
			"seed": 1057719203,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1704129676667,
			"link": null,
			"locked": false,
			"fontSize": 39.20002092633912,
			"fontFamily": 1,
			"text": "Meal bill vs Tip amount($)",
			"rawText": "Meal bill vs Tip amount($)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Meal bill vs Tip amount($)",
			"lineHeight": 1.25,
			"baseline": 34
		},
		{
			"type": "text",
			"version": 313,
			"versionNonce": 111465377,
			"isDeleted": false,
			"id": "nuaouPHT",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3951.23997562276,
			"y": 2467.0755682566833,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 279.450927734375,
			"height": 254.8763655044115,
			"seed": 1932427245,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055204,
			"link": null,
			"locked": false,
			"fontSize": 29.12872748621846,
			"fontFamily": 1,
			"text": "Bill($)       Tip($)\n34.00        5.00\n108.00       17.00\n64.00        11.00\n88.00       8.00\n99.00        14.00\n51.00         5.00",
			"rawText": "Bill($)       Tip($)\n34.00        5.00\n108.00       17.00\n64.00        11.00\n88.00       8.00\n99.00        14.00\n51.00         5.00",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Bill($)       Tip($)\n34.00        5.00\n108.00       17.00\n64.00        11.00\n88.00       8.00\n99.00        14.00\n51.00         5.00",
			"lineHeight": 1.25,
			"baseline": 244
		},
		{
			"type": "arrow",
			"version": 697,
			"versionNonce": 314540272,
			"isDeleted": false,
			"id": "3Fxb7wxqZv9fbysxnL8_q",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3112.155206594209,
			"y": 2807.528274729897,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.27156778162589035,
			"height": 447.5676618303569,
			"seed": 982645325,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436361,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Q6KUE03I",
				"focus": 0.03615812123030405,
				"gap": 12.190464564732792
			},
			"endBinding": {
				"elementId": "49a7GpK3",
				"focus": -0.1723683241593962,
				"gap": 12.778363909040308
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-0.27156778162589035,
					-447.5676618303569
				]
			]
		},
		{
			"type": "text",
			"version": 277,
			"versionNonce": 1098674927,
			"isDeleted": false,
			"id": "49a7GpK3",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3026.4366178172354,
			"y": 2322.1822489905,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 145.7398223876953,
			"height": 25,
			"seed": 274147501,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "3Fxb7wxqZv9fbysxnL8_q",
					"type": "arrow"
				}
			],
			"updated": 1708260055204,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "tip amount ($)",
			"rawText": "tip amount ($)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "tip amount ($)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 146,
			"versionNonce": 944259600,
			"isDeleted": false,
			"id": "bM3j2YB56NeJtRF4XKH1E",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3099.4209099838095,
			"y": 2786.2298825703,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 852.8822544642856,
			"height": 4.694737025669838,
			"seed": 640125709,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436007,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					852.8822544642856,
					-4.694737025669838
				]
			]
		},
		{
			"type": "text",
			"version": 149,
			"versionNonce": 2028713857,
			"isDeleted": false,
			"id": "dUskGHd9",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3439.7151866300132,
			"y": 2881.361282542397,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139.6398468017578,
			"height": 25,
			"seed": 1014800749,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055204,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Bill amount($)",
			"rawText": "Bill amount($)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Bill amount($)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 78,
			"versionNonce": 644758799,
			"isDeleted": false,
			"id": "Q6KUE03I",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3097.663707835372,
			"y": 2819.71873929463,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 27.999984741210938,
			"height": 25,
			"seed": 1218440141,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "3Fxb7wxqZv9fbysxnL8_q",
					"type": "arrow"
				}
			],
			"updated": 1708260055204,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "20",
			"rawText": "20",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "20",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 134,
			"versionNonce": 1818959713,
			"isDeleted": false,
			"id": "LfPYnlnR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3236.02752968247,
			"y": 2818.900519428559,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.559982299804688,
			"height": 25,
			"seed": 1521150509,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055204,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "40",
			"rawText": "40",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "40",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 987874095,
			"isDeleted": false,
			"id": "TkKRCQTw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3383.7871034826926,
			"y": 2820.192808072532,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.559982299804688,
			"height": 25,
			"seed": 1132928141,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055204,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "60",
			"rawText": "60",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "60",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 117,
			"versionNonce": 796035905,
			"isDeleted": false,
			"id": "5979Vyeg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3545.695934397871,
			"y": 2818.76432383704,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 29.059982299804688,
			"height": 25,
			"seed": 2062418669,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055204,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "80",
			"rawText": "80",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "80",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 100,
			"versionNonce": 524256591,
			"isDeleted": false,
			"id": "TyfkQHW9",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3706.9757108348135,
			"y": 2816.9917757064613,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 32.93998718261719,
			"height": 25,
			"seed": 1164516685,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055205,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "100",
			"rawText": "100",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "100",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 93,
			"versionNonce": 442596129,
			"isDeleted": false,
			"id": "XV6jJaa0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3879.7678948470907,
			"y": 2816.1085098024423,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 33.41998291015625,
			"height": 25,
			"seed": 441576365,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055205,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "120",
			"rawText": "120",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "120",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 116,
			"versionNonce": 1390412655,
			"isDeleted": false,
			"id": "Hirf10gl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3066.3839313984295,
			"y": 2780.3416466607023,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 1238494733,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055205,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "4",
			"rawText": "4",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 120,
			"versionNonce": 1302818561,
			"isDeleted": false,
			"id": "GqdAol0X",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3071.2211855139435,
			"y": 2711.9778248136045,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 1659020397,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055205,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "6",
			"rawText": "6",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "6",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 148,
			"versionNonce": 1443609999,
			"isDeleted": false,
			"id": "xjAseuOW",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3068.5841615881623,
			"y": 2643.679136197532,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 15.29998779296875,
			"height": 25,
			"seed": 1498255053,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055205,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "8",
			"rawText": "8",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "8",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 147,
			"versionNonce": 801367777,
			"isDeleted": false,
			"id": "iAK5F53F",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3067.577037913497,
			"y": 2584.8349676707467,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.17999267578125,
			"height": 25,
			"seed": 1806445869,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055205,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "10",
			"rawText": "10",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "10",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 147,
			"versionNonce": 201012143,
			"isDeleted": false,
			"id": "LdVLEWQF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3067.0254544871573,
			"y": 2522.5385635133816,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.659988403320312,
			"height": 25,
			"seed": 1231552397,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055205,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "12",
			"rawText": "12",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "12",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 151,
			"versionNonce": 726033089,
			"isDeleted": false,
			"id": "x1kYrmox",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3068.4137645108744,
			"y": 2459.9944438147195,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.219985961914062,
			"height": 25,
			"seed": 2025489901,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055205,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "16",
			"rawText": "16",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "16",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 114,
			"versionNonce": 1557587407,
			"isDeleted": false,
			"id": "SzP27wqn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3069.712243863553,
			"y": 2393.604586113828,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.719985961914062,
			"height": 25,
			"seed": 2091728973,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055205,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "18",
			"rawText": "18",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "18",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "ellipse",
			"version": 81,
			"versionNonce": 1182409232,
			"isDeleted": false,
			"id": "IsNjYDPPfLZu0jAdmlnYM",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3183.0683709213095,
			"y": 2745.696871270078,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 991538861,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 106,
			"versionNonce": 621502480,
			"isDeleted": false,
			"id": "tuZV7R-0IWqntoYEghO-c",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3325.0792613370472,
			"y": 2748.83717365568,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 581521677,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 212,
			"versionNonce": 1522851344,
			"isDeleted": false,
			"id": "v4gtuAOIQ3jPZ36rF_4qk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3811.6212709631623,
			"y": 2412.4379426986497,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 282437485,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 163,
			"versionNonce": 1486789648,
			"isDeleted": false,
			"id": "9Xwpi1XjydFis4WnsJR9t",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3639.603666680239,
			"y": 2632.943095809698,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 2011705805,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 195,
			"versionNonce": 814782992,
			"isDeleted": false,
			"id": "MGAwCOwJY5_Wm9f_zqZqa",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3693.4028435775604,
			"y": 2477.6129828074663,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 1157263405,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 142,
			"versionNonce": 1972557840,
			"isDeleted": false,
			"id": "26OwUcw-BQggfEk9D7LkQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3484.580386127783,
			"y": 2508.8587975396094,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 100000397,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 146,
			"versionNonce": 1687549192,
			"isDeleted": false,
			"id": "i5BL9Cmk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3353.199350944476,
			"y": 2266.3105657139577,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 512.8851318359375,
			"height": 49.0000261579239,
			"seed": 1335101677,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1704129676669,
			"link": null,
			"locked": false,
			"fontSize": 39.20002092633912,
			"fontFamily": 1,
			"text": "Meal bill vs Tip amount($)",
			"rawText": "Meal bill vs Tip amount($)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Meal bill vs Tip amount($)",
			"lineHeight": 1.25,
			"baseline": 34
		},
		{
			"type": "line",
			"version": 122,
			"versionNonce": 1470632976,
			"isDeleted": false,
			"id": "Rnks7azr0QatoI_hz9fXb",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3186.1463869299578,
			"y": 2773.398527125003,
			"strokeColor": "#9c36b5",
			"backgroundColor": "#ffc9c9",
			"width": 690,
			"height": 342.0000457763672,
			"seed": 335104429,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					690,
					-342.0000457763672
				]
			]
		},
		{
			"type": "line",
			"version": 89,
			"versionNonce": 2141917712,
			"isDeleted": false,
			"id": "VHr8ValIwOhiJIUBGQxgU",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3178.6463869299578,
			"y": 2732.898496607425,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 730.5000305175781,
			"height": 265.49999237060547,
			"seed": 163560195,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					730.5000305175781,
					-265.49999237060547
				]
			]
		},
		{
			"type": "line",
			"version": 113,
			"versionNonce": 1788760080,
			"isDeleted": false,
			"id": "A8ZlgZmmnVBbsg7aNMzdn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3213.1463564123796,
			"y": 2776.398481348636,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 655.5000305175781,
			"height": 361.49999618530273,
			"seed": 1929320173,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					655.5000305175781,
					-361.49999618530273
				]
			]
		},
		{
			"type": "text",
			"version": 410,
			"versionNonce": 1337311096,
			"isDeleted": false,
			"id": "Q7mWfKNj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3303.792724388507,
			"y": 3082.7352964780857,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 303.728271484375,
			"height": 291.2872748621846,
			"seed": 353021901,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "lsXP1kBAsyCBG_smCDSgQ",
					"type": "arrow"
				}
			],
			"updated": 1704129676690,
			"link": null,
			"locked": false,
			"fontSize": 29.12872748621846,
			"fontFamily": 1,
			"text": "Bill($)       Tip($)\n34.00        5.00\n108.00       17.00\n64.00        11.00\n88.00       8.00\n99.00        14.00\n51.00         5.00\nx' = 74       y' = 10",
			"rawText": "Bill($)       Tip($)\n34.00        5.00\n108.00       17.00\n64.00        11.00\n88.00       8.00\n99.00        14.00\n51.00         5.00\nx' = 74       y' = 10",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Bill($)       Tip($)\n34.00        5.00\n108.00       17.00\n64.00        11.00\n88.00       8.00\n99.00        14.00\n51.00         5.00\nx' = 74       y' = 10",
			"lineHeight": 1.25,
			"baseline": 280
		},
		{
			"type": "arrow",
			"version": 1051,
			"versionNonce": 1084753136,
			"isDeleted": false,
			"id": "ao10sxAUdsiJGYNta-oOZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2464.707955359957,
			"y": 3423.188002951299,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.27156778162589035,
			"height": 447.5676618303569,
			"seed": 1427975725,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436367,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "p1pmuQGw",
				"focus": 0.03615812123036902,
				"gap": 12.190464564733702
			},
			"endBinding": {
				"elementId": "gPSYMw9c",
				"focus": -0.1723683241593962,
				"gap": 12.778363909038944
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-0.27156778162589035,
					-447.5676618303569
				]
			]
		},
		{
			"type": "text",
			"version": 355,
			"versionNonce": 751723169,
			"isDeleted": false,
			"id": "gPSYMw9c",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2378.989366582983,
			"y": 2937.841977211903,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 145.7398223876953,
			"height": 25,
			"seed": 1058070669,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "ao10sxAUdsiJGYNta-oOZ",
					"type": "arrow"
				}
			],
			"updated": 1708260055206,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "tip amount ($)",
			"rawText": "tip amount ($)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "tip amount ($)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 306,
			"versionNonce": 691660528,
			"isDeleted": false,
			"id": "lsXP1kBAsyCBG_smCDSgQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2451.9736587495563,
			"y": 3401.889610791702,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 852.8822544642856,
			"height": 4.694737025669838,
			"seed": 1755268845,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436368,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "Q7mWfKNj",
				"focus": -1.1468209128275113,
				"gap": 23.172302425761927
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					852.8822544642856,
					-4.694737025669838
				]
			]
		},
		{
			"type": "text",
			"version": 227,
			"versionNonce": 397890543,
			"isDeleted": false,
			"id": "tBqCMSqR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2792.26793539576,
			"y": 3497.021010763799,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139.6398468017578,
			"height": 25,
			"seed": 1951523149,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055206,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Bill amount($)",
			"rawText": "Bill amount($)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Bill amount($)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 156,
			"versionNonce": 1628137089,
			"isDeleted": false,
			"id": "p1pmuQGw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2450.216456601119,
			"y": 3435.3784675160327,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 27.999984741210938,
			"height": 25,
			"seed": 2005020589,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "ao10sxAUdsiJGYNta-oOZ",
					"type": "arrow"
				}
			],
			"updated": 1708260055207,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "20",
			"rawText": "20",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "20",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 212,
			"versionNonce": 346357263,
			"isDeleted": false,
			"id": "K9xM1hcJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2588.5802784482175,
			"y": 3434.560247649962,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.559982299804688,
			"height": 25,
			"seed": 542749197,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055207,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "40",
			"rawText": "40",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "40",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 173,
			"versionNonce": 851242593,
			"isDeleted": false,
			"id": "LmRkDPAn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2736.3398522484395,
			"y": 3435.852536293934,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.559982299804688,
			"height": 25,
			"seed": 466741357,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055207,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "60",
			"rawText": "60",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "60",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 195,
			"versionNonce": 379085871,
			"isDeleted": false,
			"id": "KYLnrTZX",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2898.248683163619,
			"y": 3434.424052058442,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 29.059982299804688,
			"height": 25,
			"seed": 1001673421,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055207,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "80",
			"rawText": "80",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "80",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 178,
			"versionNonce": 145914433,
			"isDeleted": false,
			"id": "jZqfJJiA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3059.5284596005613,
			"y": 3432.6515039278634,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 32.93998718261719,
			"height": 25,
			"seed": 1553625389,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055207,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "100",
			"rawText": "100",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "100",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 171,
			"versionNonce": 1836713551,
			"isDeleted": false,
			"id": "Pp4PPtI3",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3232.3206436128376,
			"y": 3431.7682380238452,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 33.41998291015625,
			"height": 25,
			"seed": 200131469,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055207,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "120",
			"rawText": "120",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "120",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 194,
			"versionNonce": 1137412641,
			"isDeleted": false,
			"id": "Rx1xjBvU",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2418.9366801641763,
			"y": 3396.001374882105,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 1843907053,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055207,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "4",
			"rawText": "4",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 198,
			"versionNonce": 1478648943,
			"isDeleted": false,
			"id": "dn1lxczk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2423.7739342796913,
			"y": 3327.6375530350065,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 1670513741,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055207,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "6",
			"rawText": "6",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "6",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 226,
			"versionNonce": 2096602625,
			"isDeleted": false,
			"id": "izGtj9OR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2421.13691035391,
			"y": 3259.3388644189345,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 15.29998779296875,
			"height": 25,
			"seed": 1892020909,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055207,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "8",
			"rawText": "8",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "8",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 225,
			"versionNonce": 643432079,
			"isDeleted": false,
			"id": "jPricv6b",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2420.129786679244,
			"y": 3200.49469589215,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.17999267578125,
			"height": 25,
			"seed": 1647121677,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055207,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "10",
			"rawText": "10",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "10",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 225,
			"versionNonce": 53884385,
			"isDeleted": false,
			"id": "eSshjiAc",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2419.578203252905,
			"y": 3138.198291734785,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.659988403320312,
			"height": 25,
			"seed": 859892589,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055207,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "12",
			"rawText": "12",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "12",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 229,
			"versionNonce": 450450607,
			"isDeleted": false,
			"id": "KgDo8O1m",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2420.9665132766213,
			"y": 3075.654172036122,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.219985961914062,
			"height": 25,
			"seed": 877327821,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055207,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "16",
			"rawText": "16",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "16",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 192,
			"versionNonce": 429314497,
			"isDeleted": false,
			"id": "8I6yu8Hh",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2422.2649926293007,
			"y": 3009.2643143352307,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.719985961914062,
			"height": 25,
			"seed": 1885647917,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055207,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "18",
			"rawText": "18",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "18",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "ellipse",
			"version": 159,
			"versionNonce": 1169482768,
			"isDeleted": false,
			"id": "kmEFfrLRu0IvcTY21WXab",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2535.6211196870563,
			"y": 3361.35659949148,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 1400350349,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 184,
			"versionNonce": 865985040,
			"isDeleted": false,
			"id": "R3Khnz_wWOwCwMZnhgl7S",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2677.632010102795,
			"y": 3364.496901877082,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 272452845,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 290,
			"versionNonce": 934748176,
			"isDeleted": false,
			"id": "GXMFnW12p_hLexmP2r1WE",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3164.17401972891,
			"y": 3028.097670920053,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 1178543949,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 241,
			"versionNonce": 569941520,
			"isDeleted": false,
			"id": "Sb0B6VGeJyND1As34Zoz7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2992.1564154459857,
			"y": 3248.6028240311007,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 1742124461,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 273,
			"versionNonce": 56253456,
			"isDeleted": false,
			"id": "1veb9uB3dzGRKGrw78Srs",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3045.955592343308,
			"y": 3093.272711028869,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 1613592589,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 220,
			"versionNonce": 232020496,
			"isDeleted": false,
			"id": "yitmFbqNXgoj8How8mSvW",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2837.13313489353,
			"y": 3124.518525761012,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 2034036333,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 224,
			"versionNonce": 1860487032,
			"isDeleted": false,
			"id": "xwCfkNLU",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2705.752099710223,
			"y": 2881.970293935361,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 512.8851318359375,
			"height": 49.0000261579239,
			"seed": 30316749,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1704129676694,
			"link": null,
			"locked": false,
			"fontSize": 39.20002092633912,
			"fontFamily": 1,
			"text": "Meal bill vs Tip amount($)",
			"rawText": "Meal bill vs Tip amount($)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Meal bill vs Tip amount($)",
			"lineHeight": 1.25,
			"baseline": 34
		},
		{
			"type": "text",
			"version": 186,
			"versionNonce": 222881487,
			"isDeleted": false,
			"id": "DbDDwq35",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2781.1164154526923,
			"y": 3544.4572471512615,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 163.374755859375,
			"height": 56.38465294471099,
			"seed": 1858283811,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055208,
			"link": null,
			"locked": false,
			"fontSize": 45.10772235576879,
			"fontFamily": 1,
			"text": "x' = 74",
			"rawText": "x' = 74",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x' = 74",
			"lineHeight": 1.25,
			"baseline": 40
		},
		{
			"type": "text",
			"version": 182,
			"versionNonce": 1950845960,
			"isDeleted": false,
			"id": "r65ymO7U",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2265.424182880577,
			"y": 3194.611102695133,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 116.03999328613281,
			"height": 43.818408700727716,
			"seed": 2051450029,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1704129676702,
			"link": null,
			"locked": false,
			"fontSize": 35.05472696058217,
			"fontFamily": 1,
			"text": "y' = 10",
			"rawText": "y' = 10",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y' = 10",
			"lineHeight": 1.25,
			"baseline": 30
		},
		{
			"type": "line",
			"version": 149,
			"versionNonce": 1024381456,
			"isDeleted": false,
			"id": "zlOx8mWFSZLTlVXV6NQWu",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2467.270402456899,
			"y": 3211.5341796182097,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 476.3077016977163,
			"height": 5.538423978365245,
			"seed": 1915790061,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					476.3077016977163,
					-5.538423978365245
				]
			]
		},
		{
			"type": "line",
			"version": 148,
			"versionNonce": 1166675984,
			"isDeleted": false,
			"id": "SH8g4Apr9ti5Pl_v-tZks",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2845.7318939683173,
			"y": 3405.380380414484,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 5.538423978365245,
			"height": 227.07697941706738,
			"seed": 427374573,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-5.538423978365245,
					-227.07697941706738
				]
			]
		},
		{
			"type": "text",
			"version": 128,
			"versionNonce": 1966666145,
			"isDeleted": false,
			"id": "301OhoAx",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2855.2703742868284,
			"y": 3173.995727469772,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 192.83982849121094,
			"height": 25,
			"seed": 1393611501,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055210,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(74, 10) CENTROID",
			"rawText": "(74, 10) CENTROID",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(74, 10) CENTROID",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "diamond",
			"version": 123,
			"versionNonce": 221334544,
			"isDeleted": false,
			"id": "Lb7GZRCnUbjdHboDYnOEl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2827.5780665945204,
			"y": 3191.2265154805896,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 27.692307692307622,
			"height": 29.538433368389178,
			"seed": 2130149485,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 237,
			"versionNonce": 62408513,
			"isDeleted": false,
			"id": "txKSANZz",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2477.42416410053,
			"y": 3094.6110557450124,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 479.3781433105469,
			"height": 61.076941856971196,
			"seed": 1972922947,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260065126,
			"link": null,
			"locked": false,
			"fontSize": 24.430776742788478,
			"fontFamily": 1,
			"text": "The best-fit regression line will / must \npass through the centroid",
			"rawText": "The best-fit regression line will / must \npass through the centroid",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The best-fit regression line will / must \npass through the centroid",
			"lineHeight": 1.25,
			"baseline": 51
		},
		{
			"type": "arrow",
			"version": 1097,
			"versionNonce": 474016496,
			"isDeleted": false,
			"id": "4W8YwIOrDyr1ioWlBRtHL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2903.57768071142,
			"y": 4251.728355228077,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.27156778162589035,
			"height": 447.5676618303569,
			"seed": 611272579,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436373,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "93H2LN79",
				"focus": 0.03615812123036902,
				"gap": 12.190464564733702
			},
			"endBinding": {
				"elementId": "z7n0BAXG",
				"focus": -0.1723683241593962,
				"gap": 12.778363909039399
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-0.27156778162589035,
					-447.5676618303569
				]
			]
		},
		{
			"type": "text",
			"version": 367,
			"versionNonce": 1279341807,
			"isDeleted": false,
			"id": "z7n0BAXG",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2817.859091934446,
			"y": 3766.3823294886806,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 145.7398223876953,
			"height": 25,
			"seed": 381771555,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "4W8YwIOrDyr1ioWlBRtHL",
					"type": "arrow"
				}
			],
			"updated": 1708260055211,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "tip amount ($)",
			"rawText": "tip amount ($)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "tip amount ($)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 236,
			"versionNonce": 311411216,
			"isDeleted": false,
			"id": "AOIfuyBb8qOMrNBuhPOjW",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2890.843384101019,
			"y": 4230.42996306848,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 852.8822544642856,
			"height": 4.694737025669838,
			"seed": 305103555,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					852.8822544642856,
					-4.694737025669838
				]
			]
		},
		{
			"type": "text",
			"version": 239,
			"versionNonce": 2068583809,
			"isDeleted": false,
			"id": "3nHYMXxF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3231.137660747223,
			"y": 4325.561363040577,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139.6398468017578,
			"height": 25,
			"seed": 794309219,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055211,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Bill amount($)",
			"rawText": "Bill amount($)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Bill amount($)",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 168,
			"versionNonce": 1061863183,
			"isDeleted": false,
			"id": "93H2LN79",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2889.0861819525817,
			"y": 4263.918819792811,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 27.999984741210938,
			"height": 25,
			"seed": 1862921731,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "4W8YwIOrDyr1ioWlBRtHL",
					"type": "arrow"
				}
			],
			"updated": 1708260055211,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "20",
			"rawText": "20",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "20",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 224,
			"versionNonce": 1057996129,
			"isDeleted": false,
			"id": "9DvJf9bH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3027.4500037996804,
			"y": 4263.10059992674,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.559982299804688,
			"height": 25,
			"seed": 876819875,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055211,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "40",
			"rawText": "40",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "40",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 185,
			"versionNonce": 1222509871,
			"isDeleted": false,
			"id": "KCLKfUya",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3175.2095775999023,
			"y": 4264.392888570712,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.559982299804688,
			"height": 25,
			"seed": 2117241155,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055211,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "60",
			"rawText": "60",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "60",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 207,
			"versionNonce": 1070819649,
			"isDeleted": false,
			"id": "aQwvZbXk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3337.1184085150817,
			"y": 4262.96440433522,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 29.059982299804688,
			"height": 25,
			"seed": 1647732963,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055211,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "80",
			"rawText": "80",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "80",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 190,
			"versionNonce": 1751353167,
			"isDeleted": false,
			"id": "RcEHtayJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3498.398184952024,
			"y": 4261.191856204641,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 32.93998718261719,
			"height": 25,
			"seed": 1172132995,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055211,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "100",
			"rawText": "100",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "100",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 183,
			"versionNonce": 1727437089,
			"isDeleted": false,
			"id": "OquOd6ys",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3671.1903689643013,
			"y": 4260.308590300623,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 33.41998291015625,
			"height": 25,
			"seed": 1491455011,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055212,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "120",
			"rawText": "120",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "120",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 206,
			"versionNonce": 473154927,
			"isDeleted": false,
			"id": "JEdJX5bt",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2857.806405515639,
			"y": 4224.541727158883,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 1329483715,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055212,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "4",
			"rawText": "4",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 210,
			"versionNonce": 1172884737,
			"isDeleted": false,
			"id": "YmiqVVlR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2862.643659631154,
			"y": 4156.177905311784,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 1527078755,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055212,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "6",
			"rawText": "6",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "6",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 238,
			"versionNonce": 60243855,
			"isDeleted": false,
			"id": "A6VN8U1r",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2860.006635705373,
			"y": 4087.879216695712,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 15.29998779296875,
			"height": 25,
			"seed": 1720285955,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055212,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "8",
			"rawText": "8",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "8",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 237,
			"versionNonce": 338265313,
			"isDeleted": false,
			"id": "DE5dRc6S",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2858.9995120307067,
			"y": 4029.0350481689275,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.17999267578125,
			"height": 25,
			"seed": 239674019,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055212,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "10",
			"rawText": "10",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "10",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 237,
			"versionNonce": 1086748079,
			"isDeleted": false,
			"id": "1eZbAgmu",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2858.447928604368,
			"y": 3966.7386440115624,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.659988403320312,
			"height": 25,
			"seed": 1525864003,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055212,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "12",
			"rawText": "12",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "12",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 241,
			"versionNonce": 1833451713,
			"isDeleted": false,
			"id": "WTriv1Tk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2859.836238628084,
			"y": 3904.1945243128994,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.219985961914062,
			"height": 25,
			"seed": 996480483,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055212,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "16",
			"rawText": "16",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "16",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 204,
			"versionNonce": 451536847,
			"isDeleted": false,
			"id": "OBdimM66",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2861.1347179807635,
			"y": 3837.804666612008,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.719985961914062,
			"height": 25,
			"seed": 1051615619,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055212,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "18",
			"rawText": "18",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "18",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "ellipse",
			"version": 171,
			"versionNonce": 1640079888,
			"isDeleted": false,
			"id": "WOtIxzL3G2tQ3m9Yeaw34",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2974.490845038519,
			"y": 4189.896951768258,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 235747619,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 196,
			"versionNonce": 1801642000,
			"isDeleted": false,
			"id": "ckDSTi3IqnU2g-ygqffa0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3116.501735454258,
			"y": 4193.03725415386,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 653270211,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 302,
			"versionNonce": 1781292560,
			"isDeleted": false,
			"id": "8VexOW3K_5Gj27TNHsyXt",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3603.043745080374,
			"y": 3856.6380231968305,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 1425378403,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 253,
			"versionNonce": 253107216,
			"isDeleted": false,
			"id": "wS_lBdMzLAxeHIY7uFqWY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3431.0261407974485,
			"y": 4077.143176307878,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 1810630659,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 285,
			"versionNonce": 739777040,
			"isDeleted": false,
			"id": "zMUwVW63PxgkEKviYPWnD",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3484.825317694771,
			"y": 3921.813063305646,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 1104285603,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 232,
			"versionNonce": 338319376,
			"isDeleted": false,
			"id": "MQCHaFV7ZfqlWtD75JU0A",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3276.002860244993,
			"y": 3953.0588780377893,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 18.77903529575906,
			"height": 10.954502650669383,
			"seed": 1758864195,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 236,
			"versionNonce": 474432264,
			"isDeleted": false,
			"id": "UhF6dzns",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3144.6218250616857,
			"y": 3710.5106462121385,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 512.8851318359375,
			"height": 49.0000261579239,
			"seed": 693551843,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1704129676772,
			"link": null,
			"locked": false,
			"fontSize": 39.20002092633912,
			"fontFamily": 1,
			"text": "Meal bill vs Tip amount($)",
			"rawText": "Meal bill vs Tip amount($)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Meal bill vs Tip amount($)",
			"lineHeight": 1.25,
			"baseline": 34
		},
		{
			"type": "line",
			"version": 207,
			"versionNonce": 1449104400,
			"isDeleted": false,
			"id": "RWDrVxuYJmBFv5AyE47Cz",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3004.56883052959,
			"y": 4220.598561846817,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffc9c9",
			"width": 655.5000305175781,
			"height": 361.49999618530273,
			"seed": 105179587,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					655.5000305175781,
					-361.49999618530273
				]
			]
		},
		{
			"type": "text",
			"version": 142,
			"versionNonce": 1323597985,
			"isDeleted": false,
			"id": "hp7dP8N5",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3666.426039571519,
			"y": 3834.6521689397796,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 216.2397918701172,
			"height": 25,
			"seed": 1609884035,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055213,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "y = 0.1462x - 0.8188",
			"rawText": "y = 0.1462x - 0.8188",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y = 0.1462x - 0.8188",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "diamond",
			"version": 163,
			"versionNonce": 1098240016,
			"isDeleted": false,
			"id": "xogUBduebQDM81HnCtwaM",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3278.4389112078043,
			"y": 4029.2317384384787,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 45.27838812934033,
			"height": 52.58138020833303,
			"seed": 382154691,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 168,
			"versionNonce": 1612322287,
			"isDeleted": false,
			"id": "JnMdqxs3",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3194.5797939117974,
			"y": 3991.200664762262,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 182.83984375,
			"height": 25,
			"seed": 2121437997,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055213,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(74,10) CENTROID",
			"rawText": "(74,10) CENTROID",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(74,10) CENTROID",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 196,
			"versionNonce": 1454228609,
			"isDeleted": false,
			"id": "4YSUBR8r",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1484.2320805725499,
			"y": 3784.665788006746,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 225.9397735595703,
			"height": 25,
			"seed": 781738253,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "UVWdAAHwalBs5gNMnmLOw",
					"type": "arrow"
				},
				{
					"id": "3bos0sivrmfuqdBvUC5HI",
					"type": "arrow"
				}
			],
			"updated": 1708260055214,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "y'i = 0.1462x - 0.8188",
			"rawText": "y'i = 0.1462x - 0.8188",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y'i = 0.1462x - 0.8188",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 219,
			"versionNonce": 1749256527,
			"isDeleted": false,
			"id": "AjH9DqAm",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1534.466988989041,
			"y": 3713.4040579729362,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 379.924560546875,
			"height": 35.825626148897285,
			"seed": 1149315789,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260065130,
			"link": null,
			"locked": false,
			"fontSize": 28.66050091911783,
			"fontFamily": 1,
			"text": "QUICK INTERPRETATION",
			"rawText": "QUICK INTERPRETATION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "QUICK INTERPRETATION",
			"lineHeight": 1.25,
			"baseline": 24
		},
		{
			"type": "text",
			"version": 638,
			"versionNonce": 1258823944,
			"isDeleted": false,
			"id": "K12MoOo9",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 927.4705341571084,
			"y": 3944.3902681308264,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 804.1808471679688,
			"height": 62.372041590072996,
			"seed": 369188419,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1704129676786,
			"link": null,
			"locked": false,
			"fontSize": 24.9488166360292,
			"fontFamily": 1,
			"text": "For every $1 the bill amount(x) increases, we wold expect the tip\namount to increase by $0.1462 or about 15-cents.",
			"rawText": "For every $1 the bill amount(x) increases, we wold expect the tip\namount to increase by $0.1462 or about 15-cents.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "For every $1 the bill amount(x) increases, we wold expect the tip\namount to increase by $0.1462 or about 15-cents.",
			"lineHeight": 1.25,
			"baseline": 53
		},
		{
			"type": "rectangle",
			"version": 217,
			"versionNonce": 557023760,
			"isDeleted": false,
			"id": "k71BH-TKOAsZya6yMJofk",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 919.1261076841224,
			"y": 3908.207666998528,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 845.9413281609027,
			"height": 128.36038028492658,
			"seed": 2008735661,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "UVWdAAHwalBs5gNMnmLOw",
					"type": "arrow"
				}
			],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 546,
			"versionNonce": 1951854320,
			"isDeleted": false,
			"id": "UVWdAAHwalBs5gNMnmLOw",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1312.9377397282979,
			"y": 3883.4634402062484,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 261.3602941176473,
			"height": 66.49995691636013,
			"seed": 793103437,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436382,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "k71BH-TKOAsZya6yMJofk",
				"focus": -0.5607893451028171,
				"gap": 24.744226792279733
			},
			"endBinding": {
				"elementId": "4YSUBR8r",
				"focus": -0.33871906216800785,
				"gap": 7.297695283142275
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					261.3602941176473,
					-66.49995691636013
				]
			]
		},
		{
			"type": "text",
			"version": 400,
			"versionNonce": 1080265825,
			"isDeleted": false,
			"id": "agipPV7j",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1893.6776294341785,
			"y": 3938.5096833128664,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 665.21923828125,
			"height": 75,
			"seed": 774881901,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055219,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "if the bill amount (x) is zero, then the expected / predicted tip \namount is $-0.8188 or negative 82-cents! Does this make snese\n? No. The intercept may or may not make sense in the \"real world\".",
			"rawText": "if the bill amount (x) is zero, then the expected / predicted tip \namount is $-0.8188 or negative 82-cents! Does this make snese\n? No. The intercept may or may not make sense in the \"real world\".",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "if the bill amount (x) is zero, then the expected / predicted tip \namount is $-0.8188 or negative 82-cents! Does this make snese\n? No. The intercept may or may not make sense in the \"real world\".",
			"lineHeight": 1.25,
			"baseline": 67
		},
		{
			"type": "rectangle",
			"version": 228,
			"versionNonce": 865729040,
			"isDeleted": false,
			"id": "6Aa1EHTk_RYmcVvlBzOhy",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1854.318570380869,
			"y": 3911.7369351511015,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 767.0693072150734,
			"height": 128.36038028492658,
			"seed": 1919279011,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "3bos0sivrmfuqdBvUC5HI",
					"type": "arrow"
				}
			],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 582,
			"versionNonce": 2042360560,
			"isDeleted": false,
			"id": "3bos0sivrmfuqdBvUC5HI",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2267.2367689102816,
			"y": 3885.446292917646,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 544.3716969209554,
			"height": 86.60457835477973,
			"seed": 865580515,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436383,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "6Aa1EHTk_RYmcVvlBzOhy",
				"focus": 0.7599658231292432,
				"gap": 26.2906422334554
			},
			"endBinding": {
				"elementId": "4YSUBR8r",
				"focus": -0.6010645922509168,
				"gap": 12.693217857206037
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-544.3716969209554,
					-86.60457835477973
				]
			]
		},
		{
			"type": "line",
			"version": 129,
			"versionNonce": 581792784,
			"isDeleted": false,
			"id": "uVN0984sCM7_sKpuYxbK2",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2098.344880640774,
			"y": 1328.9330256072565,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 851.8181501116071,
			"height": 0,
			"seed": 979150352,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					851.8181501116071,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 210,
			"versionNonce": 50622992,
			"isDeleted": false,
			"id": "r53uPo53ZcYYEHmHTf_ym",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1508.6298566917399,
			"y": 3752.1060326640845,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 450.69737025669656,
			"height": 0,
			"seed": 866486000,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					450.69737025669656,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 271,
			"versionNonce": 2076946448,
			"isDeleted": false,
			"id": "47qQfXl2HN6w77HHaM7AM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 895.6814226794636,
			"y": 3695.7688395837267,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1746.4525495256696,
			"height": 360.5579485212056,
			"seed": 2063306992,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1703960436008,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 109,
			"versionNonce": 842749456,
			"isDeleted": false,
			"id": "1GZoKY7HvIzkayN0v-yg2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 868.5607189368457,
			"y": 1202.3039373417039,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 3391.498107910158,
			"height": 3178.5437011718764,
			"seed": 966029040,
			"groupIds": [
				"fUohjcGhbuf9ejgalfrqt"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "4JB3WKShh3AxHqF6oYGRR",
					"type": "arrow"
				}
			],
			"updated": 1703960455261,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 126,
			"versionNonce": 1580358384,
			"isDeleted": false,
			"id": "Sm62Q3InCR_y5Pujvda5Q",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1780.2188831139365,
			"y": 1683.2891973514693,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1703.636474609376,
			"height": 0,
			"seed": 1639416848,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703960500938,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1703.636474609376,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 112,
			"versionNonce": 227339280,
			"isDeleted": false,
			"id": "65-IHiJtdjA7xX5c9VnNU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2673.678364200519,
			"y": -195.27487757590643,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1009.1239929199223,
			"height": 457.4578857421878,
			"seed": 63697424,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018971882,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "12sX72-6dnJxejh3-rE8_",
				"focus": -0.5548883441055239,
				"gap": 14.507909502301118
			},
			"endBinding": {
				"elementId": "ksJ2rROzAUB4zgPfQCtJI",
				"focus": 0.2300429571108698,
				"gap": 19.28256590802215
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					622.6512145996098,
					-25.4511228265319
				],
				[
					1009.1239929199223,
					432.0067629156559
				]
			]
		},
		{
			"type": "arrow",
			"version": 48,
			"versionNonce": 754167024,
			"isDeleted": false,
			"id": "4JB3WKShh3AxHqF6oYGRR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1829.3093151282528,
			"y": 678.4153875370152,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 504.7808837890625,
			"height": 496.8937683105469,
			"seed": 1220770544,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018972282,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "12sX72-6dnJxejh3-rE8_",
				"focus": -0.24407042158688053,
				"gap": 2.0006488618428193
			},
			"endBinding": {
				"elementId": "1GZoKY7HvIzkayN0v-yg2",
				"focus": 0.610946858340473,
				"gap": 26.99478149414199
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-110.4205322265625,
					260.2777099609375
				],
				[
					394.3603515625,
					496.8937683105469
				]
			]
		},
		{
			"type": "arrow",
			"version": 114,
			"versionNonce": 1395976720,
			"isDeleted": false,
			"id": "lnCk9_L6Ll5CVJ-Wa9IVZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 891.170429630205,
			"y": -311.3200375661933,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1144.0830993652353,
			"height": 370.6986999511721,
			"seed": 1872707600,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018971882,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "12sX72-6dnJxejh3-rE8_",
				"focus": 0.1252314780482074,
				"gap": 19.669540041969867
			},
			"endBinding": {
				"elementId": "uPOQeWmWAgY8y6Y4Xg7xF",
				"focus": -0.5365583949213729,
				"gap": 18.20629605977092
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-647.1891784667969,
					-256.443011176089
				],
				[
					-1144.0830993652353,
					114.25568877508312
				]
			]
		},
		{
			"type": "rectangle",
			"version": 52,
			"versionNonce": 467657744,
			"isDeleted": false,
			"id": "bcHEk2nL-j3602DtrxLVo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2492.4076038170615,
			"y": 1549.1139349002965,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 3202.2052001953143,
			"height": 3517.693328857424,
			"seed": 2024784912,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "wOXOjUn6rH4utfciDZYiV",
					"type": "arrow"
				}
			],
			"updated": 1703960509912,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 89,
			"versionNonce": 1690382576,
			"isDeleted": false,
			"id": "wOXOjUn6rH4utfciDZYiV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1463.8887829016903,
			"y": 694.981015588773,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1080.5471801757822,
			"height": 836.0437774658207,
			"seed": 481058544,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704018972282,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "12sX72-6dnJxejh3-rE8_",
				"focus": -0.349701902327051,
				"gap": 18.566276913600518
			},
			"endBinding": {
				"elementId": "bcHEk2nL-j3602DtrxLVo",
				"focus": -0.3778225262488072,
				"gap": 18.089141845703125
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-481.11968994140716,
					276.0521697998048
				],
				[
					-694.0740966796884,
					607.3148345947269
				],
				[
					-1080.5471801757822,
					836.0437774658207
				]
			]
		},
		{
			"type": "text",
			"version": 515,
			"versionNonce": 313697839,
			"isDeleted": false,
			"id": "fj6US580",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1915.0807505670923,
			"y": -238.6913790511723,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 633.6194458007812,
			"height": 150,
			"seed": 372523760,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055220,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The difference between the observed value of y and the\nstraight line (Bo + B1x) be an error e. It is convenient to think\nof e as a statistical error; that is, it is a random variable\nthat accounts for the failure of the model to fit the data\nexactly. The error may be made up of the effects of other\nvariables on delivery time, measurnment errors, and so forth",
			"rawText": "The difference between the observed value of y and the\nstraight line (Bo + B1x) be an error e. It is convenient to think\nof e as a statistical error; that is, it is a random variable\nthat accounts for the failure of the model to fit the data\nexactly. The error may be made up of the effects of other\nvariables on delivery time, measurnment errors, and so forth",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The difference between the observed value of y and the\nstraight line (Bo + B1x) be an error e. It is convenient to think\nof e as a statistical error; that is, it is a random variable\nthat accounts for the failure of the model to fit the data\nexactly. The error may be made up of the effects of other\nvariables on delivery time, measurnment errors, and so forth",
			"lineHeight": 1.25,
			"baseline": 142
		},
		{
			"type": "text",
			"version": 42,
			"versionNonce": 601184321,
			"isDeleted": false,
			"id": "lvmP7Qhb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1861.9728204290943,
			"y": -231.15797501878302,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 43.279937744140625,
			"height": 25,
			"seed": 1140132080,
			"groupIds": [
				"Ag-efvgKeqhq44QC2a8a5"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055221,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "e = ",
			"rawText": "e = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "e = ",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 37,
			"versionNonce": 821823567,
			"isDeleted": false,
			"id": "u0ae1u8u",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 5006.021187883986,
			"y": 1311.2391479421708,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 118.89588928222656,
			"height": 73.5810320490258,
			"seed": 1480744200,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055222,
			"link": null,
			"locked": false,
			"fontSize": 58.86482563922063,
			"fontFamily": 1,
			"text": "SST",
			"rawText": "SST",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "SST",
			"lineHeight": 1.25,
			"baseline": 52
		},
		{
			"type": "text",
			"version": 31,
			"versionNonce": 1927456801,
			"isDeleted": false,
			"id": "G2UE7Oo6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4890.538851203891,
			"y": 1542.5868423391437,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.87995910644531,
			"height": 25,
			"seed": 307168632,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055222,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "SSR",
			"rawText": "SSR",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "SSR",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 19,
			"versionNonce": 538191471,
			"isDeleted": false,
			"id": "4MB2WzQW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 5165.220654589308,
			"y": 1534.1776219615392,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.799957275390625,
			"height": 25,
			"seed": 1526567800,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055224,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "SSE",
			"rawText": "SSE",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "SSE",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 68,
			"versionNonce": 689066504,
			"isDeleted": false,
			"id": "EVhyGRHqMoTQ2ea4OKZvW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4870.770784797642,
			"y": 1521.9001459687008,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 74.85544840494731,
			"height": 60.24953206380202,
			"seed": 1506050168,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "ZOPeSR_NdM-yYD-7X14aC",
					"type": "arrow"
				}
			],
			"updated": 1704292987224,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 84,
			"versionNonce": 2023983224,
			"isDeleted": false,
			"id": "4mbW1qe_pQpZS2EdEdfKM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 5148.283602180454,
			"y": 1512.7714736867997,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 69.37815348307322,
			"height": 60.2494812011721,
			"seed": 96831240,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "5U4RdK8vBOGWk_bWmXNDW",
					"type": "arrow"
				}
			],
			"updated": 1704292991946,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 27,
			"versionNonce": 196658808,
			"isDeleted": false,
			"id": "sncfnEHvnxVGp9hvvl_pO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4960.232149543735,
			"y": 1302.811121107047,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 193.52864583333303,
			"height": 78.50690205891942,
			"seed": 248175992,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "ZOPeSR_NdM-yYD-7X14aC",
					"type": "arrow"
				},
				{
					"id": "5U4RdK8vBOGWk_bWmXNDW",
					"type": "arrow"
				}
			],
			"updated": 1704292991946,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 46,
			"versionNonce": 53524088,
			"isDeleted": false,
			"id": "ZOPeSR_NdM-yYD-7X14aC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4954.75495634712,
			"y": 1368.5378463674638,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 36.514892578125,
			"height": 142.40786234537768,
			"seed": 1874017544,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704292988453,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "sncfnEHvnxVGp9hvvl_pO",
				"focus": 0.8935138916576613,
				"gap": 5.477193196614735
			},
			"endBinding": {
				"elementId": "EVhyGRHqMoTQ2ea4OKZvW",
				"focus": -0.010887448494195937,
				"gap": 10.954437255859489
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-36.514892578125,
					142.40786234537768
				]
			]
		},
		{
			"type": "arrow",
			"version": 16,
			"versionNonce": 2127116152,
			"isDeleted": false,
			"id": "5U4RdK8vBOGWk_bWmXNDW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 5153.7607953770685,
			"y": 1374.0150649953935,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 32.86336263020803,
			"height": 131.45339965820312,
			"seed": 754920456,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1704292991946,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "sncfnEHvnxVGp9hvvl_pO",
				"focus": -0.8329763673046421,
				"gap": 1
			},
			"endBinding": {
				"elementId": "4mbW1qe_pQpZS2EdEdfKM",
				"focus": 0.30810844446467145,
				"gap": 7.303009033203011
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					32.86336263020803,
					131.45339965820312
				]
			]
		},
		{
			"type": "text",
			"version": 230,
			"versionNonce": 930806785,
			"isDeleted": false,
			"id": "KzC6HUz5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4819.692802213008,
			"y": 1642.9664301483883,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 703.69921875,
			"height": 75,
			"seed": 437631864,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055225,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "If SSR is large, it uses up more SST and therefore SSE is smaller\nrelative to SST. The coefficient of determination quantifies this ratio\nas a percentage.",
			"rawText": "If SSR is large, it uses up more SST and therefore SSE is smaller\nrelative to SST. The coefficient of determination quantifies this ratio\nas a percentage.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "If SSR is large, it uses up more SST and therefore SSE is smaller\nrelative to SST. The coefficient of determination quantifies this ratio\nas a percentage.",
			"lineHeight": 1.25,
			"baseline": 67
		},
		{
			"type": "text",
			"version": 71,
			"versionNonce": 1321435279,
			"isDeleted": false,
			"id": "LvqAerMC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4855.524406216914,
			"y": 1745.8297927785966,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 455.99951171875,
			"height": 25,
			"seed": 1977250936,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055225,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "coefficient of determination r^2 = SSR / SST",
			"rawText": "coefficient of determination r^2 = SSR / SST",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "coefficient of determination r^2 = SSR / SST",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 273,
			"versionNonce": 295556065,
			"isDeleted": false,
			"id": "dZG5KMGI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4881.327018521601,
			"y": 1853.139973442659,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 894.6990966796875,
			"height": 150,
			"seed": 57361928,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055227,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r ^2 = 89.925 / 120\ncoefficient of determination = r^2 = 0.7493 or 74.93%\n\nWe can conclude that 74.93% of the total sum of squares can be explained by\nusing the estimated regression equation to predict the tip amount. The remainder is error\n",
			"rawText": "r ^2 = 89.925 / 120\ncoefficient of determination = r^2 = 0.7493 or 74.93%\n\nWe can conclude that 74.93% of the total sum of squares can be explained by\nusing the estimated regression equation to predict the tip amount. The remainder is error\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "r ^2 = 89.925 / 120\ncoefficient of determination = r^2 = 0.7493 or 74.93%\n\nWe can conclude that 74.93% of the total sum of squares can be explained by\nusing the estimated regression equation to predict the tip amount. The remainder is error\n",
			"lineHeight": 1.25,
			"baseline": 142
		},
		{
			"type": "text",
			"version": 84,
			"versionNonce": 1052939951,
			"isDeleted": false,
			"id": "xVWLhubj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 5187.266959927849,
			"y": 2008.6786086965624,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 92.39990234375,
			"height": 25,
			"seed": 416010360,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1708260055227,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Good Fit!",
			"rawText": "Good Fit!",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Good Fit!",
			"lineHeight": 1.25,
			"baseline": 17
		}
	],
	"appState": {
		"theme": "dark",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 2,
		"currentItemStrokeStyle": "dashed",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 1266.4992381821767,
		"scrollY": 266.6633904729867,
		"zoom": {
			"value": 0.5499999999999999
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"gridColor": {
			"Bold": "#C9C9C9FF",
			"Regular": "#EDEDEDFF"
		},
		"currentStrokeOptions": null,
		"previousGridSize": null,
		"frameRendering": {
			"enabled": true,
			"clip": true,
			"name": true,
			"outline": true
		}
	},
	"files": {}
}
```
%%