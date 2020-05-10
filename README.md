# **Covid-19 analysing and forecasting(india) using prophet**

**The coronavirus COVID-19 is affecting 215 countries and territories around the world**

Corona statistics all over the world(at the time the report was written) is:
*   Confirmed:   3,917,944
*   Death:       270,740
*   Recovered:   1,344,260

Corona statistics in India(at the time the report was written) is:
*   Confirmed:   56,409
*   Death:       1,890
*   Recovered:   16,790

These Datasets used contain data till 03-May-2020
The Report was written on 08-May-2020

Doctors are giving thier best to the patients and research laboratories are working hard to find the vaccine

Engineers are also doing thier best by discovering new techniques to identify new cases and what steps are useful to take this pandemic to an end

Here,we will analyse the current situation of India and we will compare with few other countries,we will discuss the reasons of why the things are going in this way and we will predict the change in number of cases using Prophet(an open source facebook program)

we are going to compare:
*   India
*   Italy
*   Korea

![](https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/piechart.PNG)
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/taball.PNG" height="400">
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/activecomp.PNG" height="400">
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/folliummap.PNG" height="400">

**Which parts of india have more covid-19 cases?**
 * Metropolitan cities likes delhi,mumbai and banglore are having more number of covid-19 cases because these cities are the hubs of international deals and trading.Due to high population corona virus can be easily transmitted from one to many even with a sneeze
 
**Reasons for Maharastra having more cases**
  *   One of the reason is Maharastra goverm is conducting lot of tests comparedto other states
      
      * “The logical explanation is that the more the state tests, the more cases it will find,” said Tarun Bhatnagar, scientist, National Institute of Epidemiology, Chennai. The states that have been testing more number of suspected cases even with the current guidelines will find more cases, he said.
      * [News Report](https://theprint.in/health/why-maharashtra-has-indias-highest-covid-19-mortality-numbers/398409/)


*   The Places where corona is widely spread is mostly having high population density and these are the hubs of international deals and trading.Due to high population corona virus can be easily transmitted from one to many even with a sneeze
      * When the virus got transmitted it won't show the effect immediately.so one may feel normal and meet several other people and transmit virus to them
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/tot vs rec.PNG" height="400">

**Which state recovery rate is high and why?**


*   The Kerala's recovery rate is much higher other big states. Currently, Kerala's recovery rate stands at  92.07 per cent. Whereas Maharashtra's recovery rate is  49.32 per cent, West Bengal  27.08 per cent, Uttar Pradesh 34.27 per cent, Tamil Nadu 36.59 per cent, Telangana  53.37 per cent, Rajasthan 48.29 per cent, and Gujarat 22.11 per cent.
*   According to The News Minute, Kerala managed to trace contacts of confirmed COVID-19 patients swiftly and limit the spread of the virus in other parts of the state.
*   Another important reason for Kerala's high recoveries was that the many patients had mild symptoms, Ekbal added.

[Source](https://www.businesstoday.in/latest/trends/coronavirus-update-kerala-recovery-rate-at-93-percent-higher-than-maharashtra-gujarat-12-other-states/story/403108.html)

<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/Tcum.PNG" height="400">
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/bargraph.PNG" height="400">
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/Tcum tot vs new.PNG" height="400">
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/ind comp.png">
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/ita comp.png">
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/kor comp.png">
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/total comp.png">

**How korea graph got stabilised?**

* In an interview with CNN, South Korean Health Minister Park Neunghoo said that he is hoping that his country has passed the peak. Emphasizing the success of early testing, he added that "detecting patients at an early stage is very important and we learned the simple lessons by dealing with this virus that this is very contagious — and once it starts, it spreads very quickly and in very wide areas." Park also said that "raising the testing capability is very important because that way, you can detect someone who's carrying the virus, then you can contain the virus". If the positive trend continues, South Korea's strategy will surely become a model for other impacted countries to follow.

<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/comp outline.png">
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/confirmed1.png">
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/confirmed2.png">
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/death1.png">
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/death2.png">
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/recovered1.png">
<img src="https://github.com/likhith1542/analysing-and-forecasting-covid-19-in-india/blob/master/recovered2.png">

# **Overall Observations:**
* Madhyapradesh has highest number of cases.
* Kerala has highest recovery rate.
* Eastern states are having less number of covid-19 cases.
* India didn't reached its peek yet.India will get hit by corona may be june-july months.
* According to prophet the cases will increase in upcoming days.
* The percentage of people recovering is higher than the people dying.
* The new techniques in discovering covid-19 helped in recognizing cases fastly.
* The cases discovered,recovered and deaths are high on first three days of week and the steep goes down till the end day off the week.
* We have to follow Lockdown rigourously to keep ourselves away from covid-19.
