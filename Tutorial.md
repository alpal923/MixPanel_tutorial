# MixPanel Tutorial

## Access

Access is granted by Kevin Harrison, or whoever Product Analytics has selected in the event of his death. 

## Overview

MixPanel is an events-based, user-centric tool used to understand our customers’ action within the Vivint app. There are two main kinds of data: the events, which are tracked in a history log, and the user info, saved as a current snapshot. Due to the nature of these types of data, it is important to understand that a single event log will never change but may indicate changes in the system’s status whereas a single user info snapshot will update as changes are made.

MixPanel specializes in two kinds of events views. Insights are interpreted as “how many users have taken [a specified] action.” Funnels instead show users’ sequences of actions. 

As you move through this tutorial, please be aware that there is a Lexicon available to you when you come across an event you don’t understand. As a ‘data dictionary’ of sorts, the Lexicon provides descriptions of the events you will see logged in the main body of MixPanel’s functionality. To access the Lexicon, select the stacked cylinder in the upper right corner of any screen, then click “Lexicon.” Please note that some events are defined by MixPanel and others are created from follow users in our company. On this page, you will see a tab for “Custom Events,” which take several **actions** and put them in groups you can query.

Also in the menu from the stacked cylinder is a feature called “Cohorts.” If you select this, you will see a page detailing the cohorts that other Vivint employees have created. Cohorts group **user characteristics** into easily filterable partitions for later use.

## Creating an Insight Report

1. Click “Reports” in the upper left corner, then “Insights”
    * You have now instantiated a new Insight Report

![Create report](/docs/assets/img/mixpanel_create_report.png)

2. Click “Select Event” on the left side of the report builder page
3. Search for and choose an event that you want to track
    * Popular events include: Arm State, Camera Play, Lock, Garage Door, and Thermostat
4. Adjust the kind of metric you want to report (default is a count of unique users)
    1. Select “Unique Users”
    1. Select the metric most useful for your report
       * Some metrics shown are categories. Click the dropdown button (down arrow) next to the metric group name to see more specific metrics that fall under these categories.
    1. Click the meatball menu (three dots) next to the event name to toggle for first-time events or add other filters specific to just this event
    
    ![Add a metric](/docs/assets/img/mixpanel_add_metric.png)
    
    * In this example, I am interested in seeing  the average camera plays per user.
5. Add additional events by clicking the + button to the right of Metrics
   * Repeat steps 3 and 4 for any additional steps you wish to include
6. Apply global filters (filters to all events in the report)
    1. Click the + button to the right of “Filter”
    1. Search for and select the relevant filter
    
    ![Add filter](/docs/assets/img/mixpanel_filter.png)
    
    * Continuing the previous example, I am only looking for mobile app events. Thus, adding a filter onto "App" will alow me to do so. Once I click on "App" in this example, I will be given a list of app types in which I will select "Android" and "iOS."
7. Add a breakdown
    1. Click the + button to the right of “Breakdown”
    1. Search for and select the characteristic you want to group by
    
    ![Add breakdown](/docs/assets/img/mixpanel_breakdown.png)
    
    * To compare the two different app types I already filtered for, I could add "App" to the breakdowns. This will make two separately colored elements in the same visual.
8. Adjust the time frame by selecting the desired range in the bar above the graph

![Set time range](/docs/assets/img/mixpanel_time_range.png)

* Here, I am about to set my time range from 30 days to 6 months.
9. Select the graph type by clicking “Line” in the top right and choosing the view you want
10. Save and add
    1. Now that you have some sense for what your report is, double click “Untitled” in the top left corner
    1. Give your report a name
    1. Click “Save” in the upper right corner
    1. Select the dashboard you want to add your newly created report to

## Sharing and Setting Alerts

After you have created your Insight report, you can share and set alerts.
- To share, select the chain link symbol in the same area of the “Save” button. This will automatically save a copy of the link to your clipboard.
- To set an alert:
    1. Click the meatball menu (three dots) in the upper right
    2. Hover over “Alerts” then click “Create Alert”
    3. Select the desired metrics and conditions under which you wish to be alerted
    4. Name the alert at the top of the window
    5. Click “Create Alert” at the bottom of the window
    
    ![Set alert](/docs/assets/img/mixpanel_share_alert.png)
    
    * (Please note the chain link icon where I could copy the link to this visual if I wanted to.)

## Conclusion

This Mixpanel tutorial has provided you with valuable insights into the world of user analytics and how Mixpanel can be a powerful tool for tracking and analyzing user behavior. We've covered the basics of setting up Mixpanel, creating and tracking events, and how we might use the data to make informed decisions.

By harnessing the capabilities of Mixpanel, you can gain a deeper understanding of our users, their preferences, and their interactions with your product or service. This knowledge is instrumental in optimizing your offerings, improving user experience, and ultimately driving growth and success.

Remember that the key to success with MixPanel is to continuously monitor and adapt your analytics strategy as our business evolves. Regularly revisiting our goals, fine-tuning event tracking, and exploring the wealth of insights Mixpanel offers will enable us to stay ahead in today's competitive digital landscape.

If you have any questions, please reach out to the Product Analytics team.