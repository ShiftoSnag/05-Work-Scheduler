# 05-Work-Scheduler

## Description:
The Work Day Planner creates efficency and ease among your busy schedule. You can document all upcoming events for the day in your planer, It's easy to keep track with the color boxs; grey indicates the past, red indicaates the current time, and green indicates the promising future.. making it visually easy for varying consumers to keep track of the their time and events. 

# Overview

## The Challenge:
Create a simple calendar application that allows a user to save events for each hour of the day. The application will run in the browser and feature dynamically updated HTML and CSS powered by jQuery. 

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

## Usage Instructions
1. Open the document on your local device at the beginning of your day - you'll enter scheduled events/reminders into the planner to keep tracked.
2. Scroll down to see the timeblocks for the current day.
3. Click on the timeblocks type to edit the events.
4. Click the save button (on the right) to save the event.
5. Refresh the page to see the changes.
6. Events not saved in timeblocks before refresh won't be tracked locally.