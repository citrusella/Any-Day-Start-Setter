# Any-Day-Start-Setter
A third party tool for [Habitica](https://habitica.com) that allows setting any custom day start supported by the API, even if the official client doesn't support selecting it. The tool is a website accessed at https://citrusella.github.io/Any-Day-Start-Setter

Before using this tool, you should understand:

- You should understand [the warning about late Custom Day Starts on the Custom Day Start page on Habitica Wiki](https://habitica.fandom.com/wiki/Custom_Day_Start#Examples_and_a_Warning_about_Late_Custom_Day_Start_Times).
- Changing your Custom Day Start on the website or app displays a warning informing you the earliest possible calendar day and time that your next Cron will run upon changing your Custom Day Start. Keep in mind that this tool does not display that warning.
- If the API's behavior is modified to match the available times on the website and block/error on the selection of other times, this tool could permanently stop working to set later day starts. (I don't know that this is very likely to happen on v3 of the API, but if it happens then I will likely not be able to fix it.)
- Changing your day start to a time after 12 p.m. (noon / +12) will cause the website's day start dropdown to become blank. This is a side effect of those times no longer being a valid setting in the website's interface, even though your account can still be set to them "behind the scenes".
  - The website and/or the app are probably a better option to change your Custom Day Start if they support the option you are selecting.
     - The website supports 12 a.m. to 12 p.m.
     - The Android app supports all hours from 12 a.m. to 11 p.m. as of the last update to this tool.
     - I do not have iOS, so I cannot confirm what hours it supports.
