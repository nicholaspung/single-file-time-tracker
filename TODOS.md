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
    - modify category list to use the new categories ✅ 2024-02-05
        - likely model the data { db, key } ✅ 2024-02-05
    - modify tag list to use the new tags ✅ 2024-02-05
        - likely model the data { db, key } ✅ 2024-02-05
    - add a display to show start time ✅ 2024-02-09
        - add a button to change the start time value to previous log value for the day ✅ 2024-02-09
    - allow user to modify the description/category/tags while it is being run ✅ 2024-02-22
    - figure out a way to send notifications for when a pomodoro finishes
        - add a config to enable notifications for this ✅ 2024-02-23
    - send a notification for when a break finishes
        - add a config to enable notifications for this ✅ 2024-02-23

- 2024-02-04
    - when clicking pomodoro or break, instead of making the display show the time from 00:00:00 and it goes up, make it start from the pomodoro/break time and go down ✅ 2024-02-05
    - reverse sort the time tracking records ✅ 2024-02-09
    - save the pomodoro and break time config in localstorage ✅ 2024-02-12
    - check the latest record, and if there is no end time, start updating the display automatically ✅ 2024-02-13
    - make the website a progressive web app ✅ 2024-02-23

- 2024-02-05
    - in time tracking, if stopTime is undefined, make it show '' ✅ 2024-02-14

- 2024-02-09
    - When deleting a time tracking record, it currently does not display the correct records because I forgot to add the condition of removing a record if it doesn't show up in the fetching of data ✅ 2024-02-14
    - Create a button when it checks the latest record, that you can change the time to the current time ✅ 2024-02-14

- 2024-02-12
    - for pomodoro config, move the values to be read from the configs, and not the elements ✅ 2024-02-22
    - add a toast or some kind of notification for when an action is done, i.e. timer has started, pomodoro time config has been updated, etc. ✅ 2024-02-24
    - add hotkeys to be able to focus on specific inputs and tables to navigate everything through the keyboard ✅ 2024-02-24

- 2024-02-22
    - fix bug where the start time doesn't display correct when there's a record currently running ✅ 2024-02-22
    - Update the "set to last stop time today, to actually be for today ✅ 2024-02-23
        - if there's no previous record, don't show the button ✅ 2024-02-23

- 2024-03-17
    - add modal to edit time records, categories, and tags ✅ 2024-03-17
    - make sure when you update categories and tags to also update the time records with those values ✅ 2024-03-18

Working on


Not done
- 2024-02-12
    - create a button that is able to check the position of the record relative to the other records, and be able to set the time to the previous/latest start/stop time
    - make into a desktop app using Tauri (figure out Tauri and Rust)

- 2024-02-22
    - make into a desktop app using Wails (figure out Wails and Go)
    - add an action log to the page to log all the actions taken place, kind of like an audit log

- 2024-02-24
    - Add a "play button" next to a log that automatically fills out the start timer inputs

- 2024-03-18
    - Add JSDoc comments for help with types
    - add a search bar for tracked time records/categories/tags
    - remember to add all the pop up toasts for actions that are taken