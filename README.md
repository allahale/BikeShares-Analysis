# Bike Shares- Analysis

Authors: Alla Hale

This was a project for the course W205- Fundamentals of Data Engineering at UC Berkeley. It was completed using python, SQL, and Google BigQuery. The python notebook contains the full analysis.

## Problem Statement

Ford GoBike (https://www.fordgobike.com/), the company running Bay Area Bikeshare, is trying to increase ridership.  To accomplish this, Ford GoBike wants to offer deals through the mobile app. What deals should be offered?

Currently, the company has three options: a flat price for a single one-way trip, a day pass that allows unlimited 30-minute rides for 24 hours and an annual membership. 

## Overall Recommendations

The detailed analysis supporting these recommendations follows.  From the available dataset, it is clear that ridership has declined in the last several months.  

In order to increase ridership, it is recommended to:

1. **Cater to subscribers\* with any offers.**  Overall, close to 90 % of all bike trips are taken by subscribers.  Even when total numbers drop, subscribers are still taking the majority of trips.  They are important to keep, and it is important to convert more customers to subcribers.  
\* Subscribers are those with annual or 30-day memberships; customers are those with daily or 3-day passes.

2. **Take advantage of peak and low demand times.** The majority of rides occur on weekdays, during rush hours (7-9 AM and 5-7 PM).  Ford GoBike should offer deals during low demand times to increase ridership at those times.  Additionally, Ford GoBike could increase rates during peak demand times to increase revenues.  Alternatively, planning bike maintenance at the low demand times would allow for continued service quality while maintaining the bike fleet.

3. **Offer holiday specials.**  Holidays, in particular, show low ridership rates.  Days like Christmas, Independence Day, and others that are typically non-working days correspond with low ridership rates.  On these days, it would be good to offer specials to encourage people to try out the service.

4. **Offer weekend-only subscriptions.** Customers ride on the weekends, but it seems that overall rides could increase if we offered a weekend-only subscription.  For those people who do use the bikes, but only on the weekends, the subscription rate could be significantly less than the full subscription rate, but higher than a day pass.  This would be tempting for riders who might want to subscribe for more frequent use, but not for the purposes of commuting.

5. **Add a pay per time option.** Most trips are less than 30 minutes in length.  Since the day pass allows 30-minute rides, there may be potential riders who choose to walk over paying for a 30-minute ride but using only 5 minutes of it.  Adding a pay per time option may entice more riders to hop on bikes for the very short trips.