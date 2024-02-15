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

- 2024-02-04
    - when clicking pomodoro or break, instead of making the display show the time from 00:00:00 and it goes up, make it start from the pomodoro/break time and go down ✅ 2024-02-05
    - reverse sort the time tracking records ✅ 2024-02-09
    - save the pomodoro and break time config in localstorage ✅ 2024-02-12
    - check the latest record, and if there is no end time, start updating the display automatically ✅ 2024-02-13

- 2024-02-05
    - in time tracking, if stopTime is undefined, make it show '' ✅ 2024-02-14

- 2024-02-09
    - When deleting a time tracking record, it currently does not display the correct records because I forgot to add the condition of removing a record if it doesn't show up in the fetching of data ✅ 2024-02-14

Working on
- make the website a progressive web app
- allow user to modify the description/category/tags while it is being run
- for pomodoro config, move the values to be read from the configs, and not the elements

Not done
- 2024-02-01
    - figure out a way to send notifications for when a pomodoro finishes
        - add a config to enable notifications for this
    - send a notification for when a break finishes
        - add a config to enable notifications for this
    - allow user to modify the description/category/tags while it is being run

- 2024-02-04
    - make the cells editable able to choose between different inputs
    - make the website a progressive web app

- 2024-02-05
    - there's a bug when you click on an editable cell, and you try clicking into it to go to another position where it triggers again and makes it a regular cell again
    - in editable cell, add an option to show the records
    - on a new day, bucket all the time tracker records into a csv and store it somewhere to be downloaded later, maybe have a button/link that says download csv for all previous time tracker data
    - add another table that saves all the different descriptions there are, so that when a user types in the description, it can pop up later on for autocomplete

- 2024-02-09
    - Create a button when it checks the latest record, that you can change the time to the current time

- 2024-02-12
    - create a button that is able to check the position of the record relative to the other records, and be able to set the time to the previous/latest start/stop time
    - make into a desktop app using Tauri (figure out Tauri and Rust)
    - add hotkeys to be able to focus on specific inputs and tables to navigate everything through the keyboard
    - add a toast or some kind of notification for when an action is done, i.e. timer has started, pomodoro time config has been updated, etc.
    - for pomodoro config, move the values to be read from the configs, and not the elements