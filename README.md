# 05 Third-Party APIs: Work Day Scheduler

Modified starter code to make functional a basic work day scheduler. This app runs in the browser and feature dynamically updated HTML and CSS powered by jQuery.

[Moment.js](https://momentjs.com/) library to work with date and time.

## User Story

```md
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

## Acceptance Criteria

```md
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
```

The following picture depicts the application:

![Image of calendar.](./Assets/images/Screenshot%202022-08-12%20134032.jpg)

Modifications:
Created div elements that house time slot, save button, and text area
Created JS to appropriately connect moment and have save functionality that utilizes local storage