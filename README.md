# AutoR6DropCollector
Combining the Twitch auto joiner script with a built in and autonomous checker that screens for R6 matches that have drops and calls the twitch joiner to join streams to automatically collect drops

This project works by taking information from PandaScore API for future siege games, running it through a filter that only includes games that would likely have twitch drops, and schedules the twitch autojoiner to join streams an interchangable amount of time before games, even when your laptop is asleep. To configure, create a config.json file by following the example format and inserting your PandaScore API key and timezone as well as the events you would like to set the autowatcher for.
