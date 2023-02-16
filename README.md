# Any Day Start Setter

![Life Well Lived license badge](https://img.shields.io/badge/license-Life%20Well%20Lived-lightgrey) Version 2 of this tool is licensed under the Life Well Lived license, a license intended to let "retired" works "die a natural death". It disallows commercial use and modified/derivative works, as well as unmodified forks. Its full text can be read [here](https://github.com/citrusella/Any-Day-Start-Setter/blob/main/LICENSE).

This tool is no longer maintained (it has been made archived/read-only for this reason), and its creator and current license do not give permission or blessing for it to be forked. Thank you. 

Any Day Start Setter is a third party tool for [Habitica](https://habitica.com) that allows setting any custom day start supported by the API, even if the official client doesn't support selecting it. The tool is a website accessed at https://citrusella.github.io/Any-Day-Start-Setter

Before using this tool, you should understand:

- You should understand [the warning about late Custom Day Starts on the Custom Day Start page on Habitica Wiki](https://habitica.fandom.com/wiki/Custom_Day_Start#Examples_and_a_Warning_about_Late_Custom_Day_Start_Times).
- Changing your Custom Day Start on the website or app displays a warning informing you the earliest possible calendar day and time that your next Cron will run upon changing your Custom Day Start. Keep in mind that this tool does not display that warning.
- If the API's behavior is modified to match the available times on the website and block/error on the selection of other times, this tool could permanently stop working to set later day starts. (I don't know that this is very likely to happen on v3 of the API, but if it happens there is no way to fix it.)
- Changing your day start to a time after 12 p.m. (noon / +12) will cause the website's day start dropdown to become blank. This is a side effect of those times no longer being a valid setting in the website's interface, even though your account can still be set to them "behind the scenes".
  - The website and/or the app are probably a better option to change your Custom Day Start if they support the option you are selecting. The website and current versions of the iOS and Android apps support hours from 12 a.m. to 12 p.m. (0:00 to 12:00), as of the most recent update to this tool.
     -  Versions of the Android app prior to approximately version 3.5.3 (3524), released mid-June 2022, support **all** hours from 12 a.m. to 11 p.m. (0:00 to 23:00, all 24 hours the API supports), so if your device has not yet updated to the latest version or cannot update, you may be able to use the Android app to make your change instead.
     -  It stands to reason that an old enough iOS app version should be able to support all hours as well, but as I do not have iOS, I do not know when the iOS app changed from supporting all hours to supporting just until noon. (The most I can infer is that the code was changed in the iOS app's Github files in February 2022, but it is possible a version of the app using the new code was released later than that point in time.)
