Done
- 2024-02-01
    - create form to add a category ✅ 2024-02-03
        - make name field unique ✅ 2024-02-03
    - create form to add a tag ✅ 2024-02-03
        - make name field unique ✅ 2024-02-03
    - create table to see categories ✅ 2024-02-04
    - create table to see tags ✅ 2024-02-04
    - make website load categories and tags first before loading in the tracked time  logs ✅ 2024-02-04
    - add a pomodoro button to start a pomodoro ✅ 2024-02-04
    - add a break button to start a break ✅ 2024-02-04
    - add a config for pomodoro to modify time for it ✅ 2024-02-04
    - add a config for break to modify time for it ✅ 2024-02-04
    - make clicking pomodoro after it ends to automatically start break ✅ 2024-02-04

Not done
- 2024-02-01
    - modify category list to use the new categories
        - likely model the data { db, key }
    - modify tag list to use the new tags
        - likely model the data { db, key }
    - figure out a way to send notifications for when a pomodoro finishes
        - add a config to enable notifications for this
    - send a notification for when a break finishes
        - add a config to enable notifications for this
    - add a display to show start time
        - add a button to change the start time value to previous log value for the day
    - allow user to modify the description/category/tags while it is being run

- 2024-02-04
    - make the cells editable able to choose between different inputs
    - check the latest record, and if there is no end time, start updating the display automatically
    - reverse sort the time tracking records
    - save the pomodoro and break time config in indexeddb
    - make the website a progressive web app
    - when clicking pomodoro or break, instead of making the display show the time from 00:00:00 and it goes up, make it start from the pomodoro/break time and go down