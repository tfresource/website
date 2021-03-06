---
title: "GPS-enabled surveys"
categories:
  - Travel Survey Data
---

GPS-enabled [travel surveys](Travel_surveys) use GPS data logging devices to passively collect objective and accurate travel details with the additional goal of reducing respondent burden. The U.S. Federal Highway Administration sponsored the first test of a GPS-enabled survey in Lexington, Kentucky in 1996. The use of GPS in surveys today has become common practice, particularly for [household travel surveys](Household_travel_surveys).

Types of GPS Studies
====================

GPS can serve several different roles within a [travel survey](Travel_surveys).

Trip Rate Validation (Correction of Reported Travel)
----------------------------------------------------

In this ‘traditional’ application, the focus of the GPS effort is on reported trip rate validation. To meet this object, a sub-sample of households participating in a household travel survey are provided with travel diaries for recording their travel for a 24-hour period and with a GPS data logging device. On the assigned travel day(s), household members record their travel and activities in a diary or log while simultaneously capturing GPS data either in household vehicles (if an in-vehicle study) or by household members of age 16 and older (if a person-based study). The analysis focuses on a comparison of the diary data (typically obtained through a telephone interview, a personal interview, or from the diaries themselves) and the trips detected in the GPS data (obtained through software processing). The results of this comparison can be used to generate customized trip rate correction factors based on certain types of trips (such as short stops made for discretionary purposes) that tend to be under-reported and/or on socio-demographic characteristics of persons or households who most often under-report travel. These correction factors can then be applied to the larger non-GPS sample.

Prompted Recall
---------------

In a GPS-based prompted recall travel survey, household members under the age of 16 are provided traditional diaries and their details are collected by telephone, personal interview, or diary return. Household members of age 16 and older (if a person-based study) or household vehicles (if in-vehicle study) are equipped with passive GPS data loggers for the assigned travel period. Trip detection algorithms are used to identify possible trip ends and the respondents are presented with trip summaries and maps of the detected travel to confirm the GPS-based trips and to collect supplemental information about those trips which cannot easily be obtained from the GPS data (such as parking fees and size of travel party). This feedback loop can be implemented by web, by telephone, or by mail. One variation of this approach has been implemented on handheld devices (such as personal digital assistants (PDAs) or mobile phones) with the prompted recall component implemented either at the end of each trip or end of each travel day.

GPS-Only Travel Survey
----------------------

In a GPS-only travel survey, household members under the age of 16 are provided traditional diaries and their details are collected by telephone, personal interview, or diary return. Household members of age 16 or older (if a person-based study) or household vehicles (if in-vehicle study) are equipped with GPS for the assigned travel period. Trip detection algorithms are used to identify possible trip ends. Up to this point, the methodology is similar to the prompted recall approach. However, instead of re-contacting the respondents, sophisticated algorithms impute many of the missing variables using other available information.

Instrumentation Approach
========================

The GPS devices can be utilized within a vehicle (vehicle-based approach) or on a person (person-based approach). The use of one approach versus the other can and should be dictated by the study objectives and approach tradeoffs. For example, in the 2007-2008 Washington DC regional travel survey, the primary focus was on vehicle miles traveled (VMT) and so an in-vehicle approach was implemented; whereas the Chicago regional household travel survey wanted to focus on transit users, so a person-based GPS approach was implemented. Vehicle-based approaches may result in better information regarding transportation supply-side information (such as route choice, roadway speeds, etc.), but do not capture other travel behavior aspects such as mode choice. Person-based approaches may show significant promise in capturing mode choice, but are subject to other limitations such as higher respondent burden (associated with the need to carry and charge the device) and quality (wearable GPS data can be scattered or ‘noisy’ due to incorrect usage or significant sky blockage).

Vehicle-based Approach
----------------------

In-vehicle GPS household travel survey efforts to date have shown that respondent burden is minimal as the devices do not need user interaction and they remain in the vehicle, with a clear sky view and reliable power supply, resulting in consistent quality and coverage. Vehicle-based data is easier to process given the higher quality position information and the fact that vehicles travel on roads that exist in GIS networks.

Although in-vehicle approaches are more suitable to longer duration deployments (given minimal respondent burden and power supplied by the vehicle itself), household travel survey designs using this approach have historically restricted their duration to one or two days. This constraint was driven by higher equipment and data processing costs, and the need for quick equipment turnaround times necessary to support the target GPS sample size. Consequently, these factors have restricted the primary analysis of the data to focus only on a single benefit – that of trip rate auditing. However, given significantly lower equipment and data processing costs, recent in-vehicle GPS studies are opting for longer duration periods (typically one week).

Person-based Approach
---------------------

In the person-based studies (also referred to as wearable studies) performed to date in the US, all household members of age 16 and older have been provided with wearable devices. Respondent burden is higher than a vehicle-based approach because participants have to regularly or periodically recharge the devices and must remember to wear or carry them (usually by means of clip or lanyard).

GPS data collected in wearable studies tends to be a little messier given the continuous power supply and the ability to collect points while indoors. This scatter in the GPS data requires better software algorithms to remove the noise in the data. In cases where participants forget to carry the device or to recharge the unit, the lack of GPS data cannot be easily distinguished from non-travel behavior. If more than one person in a household receives a GPS device, it is feasible that devices can be inadvertently swapped in the midst of data collection, especially during multi-day data collection periods.
On the other hand, wearable GPS augments to household travel surveys have provided GPS data that have been invaluable in exploring non-motorized or transit travel behavior. Finding ways to increase participation levels and improving the ease of use and recharging method (or providing a longer battery life) could greatly improve the realized benefits of a wearable GPS approach.

References
==========

Travel Survey Methods Committee (ABJ40). GPS Surveys. In [Travel Survey Manual](http://www.travelsurveymanual.org/HomePage.html). Chapter 23.

