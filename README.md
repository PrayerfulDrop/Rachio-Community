# Rachio-Community
Community version of Rachio App/Drivers for Hubitat

Rachio Community builds off of the same base code likely used for the official Rachio integration. On top of the native features, this community version adds:
* Dashboard. See your watering schedule and skips, in conjunction with Rachio weather information, on your smart home dashboard. Substantially similar to what you see on the Home tab of the mobile app, except Rachio Community enhances it to include different icons for different types of skips. Highly configurable.
* Next Run and Last Run data exposed for automation & display. Automate based on when your next run will occur and/or when your last run occurred.
* Rain Sensor State exposed. Use your irrigation system's rain sensor for automation and/or see its status on your smart home dashboard.
* Next event data exposed. See information about your system's next event, e.g., scheduled run or skip.
* Monthly watering summary exposed. See the same monthly watering summary as on the Home tab of the mobile app.

![Rachio Community Dashboard](https://raw.githubusercontent.com/lnjustin/Rachio-Community/master/Images/Dashboard.JPG)

The Dashboard outputs an SVG image to a local endpoint as well as a cloud endpoint, so you can display the dashboard on any image tile of any dashboard, e.g., Sharptools dashboard, Smartly, etc. The dashboard is highly configurable with regard to:
* Number of days on dashboard
* Hide/Show precipitation percentage, precipitation amount, high/low temp
* Select from predefined color schemes or customize every color
* Expand or Collapse vertical or horizontal spacing
* scale up or down in size

Future enhancements will include HTML-based dashboard with clickable days to bring up additional information.

**Uses undocumented Rachio API**
Note that Rachio Community relies on an undocumented API to extend the native Rachio functionality. Rachio makes no guarantee about availability of its undocumented API, meaning it could change without notice at any time. Accordingly, the expanded functionality in Rachio Community cannot be guaranteed.

**Install Instructions**
0. Uninstall the Rachio native app
1. Install the Rachio Zone driver
2. Install the Rachio Controller driver
3. Install the Rachio Community app
4. Enable Oath
5. Follow the install instructions in the Rachio Community app

