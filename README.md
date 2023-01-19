# Obsidian Sample Plugin

Plugin that displays a [pomodoro timer](https://en.wikipedia.org/wiki/Pomodoro_Technique) in the [Obsidian](https://obsidian.md/) status bar. 

This also allows for additional logging and time tracking via the pomodoro, to measure what was actually worked on during the course of a day.

## Use

Start the pomodoro timer, which will prompt for an "Intention" or goal that you will focus on for the time.

Once the timer is up, Obsidian will take focus, and ask for what was worked on, and log to the daily note.

By default, no hotkeys or buttons are added, feel free to set or add those as needed!

All actions are available from the command pallette.

## Settings

You can change the duration of the pomodoro timer, breaks, and interval between long breaks, and toggle the end of timer sound.

Autostart timer allows you to toggle whether the next break or pomodoro start automatically after the next, or waits for you to start it. If disabled, you can specify a number of pomodoro-and-break cycles that run automatically (for instance, if you want to run two pomodoros and their corresponding breaks without stopping and then pause, enter 2).

### Logging

If you enable logging, the plugin will write to the file you specify as your log file at the end of each pomodoro. If no such file exists, it will be created at the end of your first pomo. By default, the log message is "🍅 dddd, MMMM DD YYYY, h:mm A" (e.g. "🍅 Friday, July 16 2021, 6:18 PM"), but you can specify your own message using [moment display format](https://momentjs.com/docs/#/displaying/format/).

"Log to daily note" will append the log to the daily note. Please note that this currently *only* works by appending to the end of the file.

You can open the current log file by clicking the timer.
