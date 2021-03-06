# Alarms and Alerts

To configure the various Alarms and Alerts that are built into xDrip+, go to `Settings` > `Alarms and Alerts`. 
* [`Glucose Level Alerts List`](#Glucose-Level-Alerts-List)
* [`Glucose Alerts Settings`](#Glucose-Level-Settings)
* [`Calibration Alerts`](#Calibration-Alerts)
* [`Missed reading Alert`](#Missed-reading-Alert)
* [`Other Alerts`](#Other-Alerts)
* [`Extra Alerts (xDrip+)`](#Extra-Alerts)

## Glucose Level Alerts List

This is where you can configure alerts for various BG levels. You can create two types of alerts: *Low Alerts* and *High Alerts*. 

* To create a *Low Alert*, tap the `Create Low Alert` button. A screeen will pop up with the following variables:
  * `Alert Name` -- The name of the alert (i.e. "Low Alert")
  * `Threshold` -- This sets the threshold for the alert. Since this a *Low Alert*, xDrip+ will alert when glucose values drop below this threshold.
  * `Default Snooze` -- This setting tells xDrip+ how long to wait to re-alert if the alert is snoozed. The default is 30 minutes.
  * `Re-raise every x minutes if unacknowledged` -- If you do not acknowledge the alert, xDrip will continue re-alert every x minutes until the alert is acknowledged. 
  * `Alert Tone` -- This setting allows you to set a custom tone for this alert. 
  * `Select time for alert` -- You can set a custom timeframe for each alert. The default is `all day`.
  * `Overide phone Silent Mode` -- On by default. This setting allows xDrip+ to override the "Do Not Disturb" feature on Android phones.
  * `Vibrate on alert` -- On by default. xDrip+ will vibrate as well as play an audible tone.
  * `Disable alert` -- Checking this box will disable the alert. You can reenable the alert by unchecking this box.
  * To test your alert, tap the `Test Alert` button. Once you are satisfied with your alert, tap the `Save Alert` button, and you will be returned to the Alert List.

* To create a *High Alert*, tap the `Create High Alert` button. A screeen will pop up with the following variables:
  * `Alert Name` -- The name of the alert (i.e. "Low Alert")
  * `Threshold` -- This sets the threshold for the alert. Since this a *Low Alert*, xDrip+ will alert when glucose values drop below this threshold.
  * `Default Snooze` -- This setting tells xDrip+ how long to wait to re-alert if the alert is snoozed. The default is 120 minutes.
  * `Re-raise every x minutes if unacknowledged` -- If you do not acknowledge the alert, xDrip will continue re-alert every x minutes until the alert is acknowledged. 
  * `Alert Tone` -- This setting allows you to set a custom tone for this alert. 
  * `Select time for alert` -- You can set a custom timeframe for each alert. The default is `all day`.
  * `Overide phone Silent Mode` -- On by default. This setting allows xDrip+ to override the "Do Not Disturb" feature on Android phones.
  * `Vibrate on alert` -- On by default. xDrip+ will vibrate as well as play an audible tone.
  * `Disable alert` -- Checking this box will disable the alert. You can reenable the alert by unchecking this box.
  * To test your alert, tap the `Test Alert` button. Once you are satisfied with your alert, tap the `Save Alert` button, and you will be returned to the Alert List.
  
To delete an existing alert, press and hold on the alert you wish to remove. A window with the alert settings will pop up. Scroll to the bottom and tap `Remove Alert` to delete it. 
  
## Glucose Level Settings

This section has additional settings for alerts related to blood glucose levels. 

* `Alert Volume Profile` -- Available options are:
  * High (default)
  * Medium
  * Ascending volume
  * Vibrate only
  * Silent

* `Smart Snoozing` -- Keep snoozing if glucose is heading in the right direction.
* `Smart Alerting` -- Don't alert if glucose is heading in the right direction.
* `Don't alarm during phone calls` -- Alarms are silenced during telephone calls.
* `Buttons silence alarms` -- Pressing the physical volume up or down buttons will snooze an active alarm when in the app. 
* `Start Snoozed` -- Alarms start out snoozed and must persist for a while to actually trigger.
* `Shortcut to Bg Level Alerts` -- This option creates a shortcut on the **Menu** called `Level Alerts` to the `Glucose Levels Alerts List` (see above). 
* `Suppress Alerts if missed readings` -- Suppress snoozed and active alerts after predefined period of missed readings. Checking this option will allow you to set the `Suppress snoozed and active alerts after .. minutes (minumum 10)` variable. Otherwise, it will remain grayed out.
* `Notification Channels` -- Use the Android 8+ notification channel feature.

## Calibration Alerts

This section allows you to set alerts related to calibrations. 

* `Calibrations Alerts` -- Off by default. Sliding this switch to the ON position wil allow xDrip+ to alert with calibration requests.
  * `Hours between calibrations` -- How many hours between calibration requests. The default value is 24 hours.
  * `Calibration Request Sound` -- On by default. Allows you to set a custom sound for this alert.
  * `Ovveride Silent mode` -- On by default. Allows xDrip+ to override the "Do Not Disturb" feature on Android phones for this alert.
  * `Even when charging` -- Checked by default. If unchecked, xDrip+ will not ask for calibrations when the phone is charging.
  * `Repeat Alerts` -- On by default. xDrip+ will continue to alert until a calibration is performed.
  
    * `Alert Repeat minutes` -- This sets a time interval between repeated calibration alerts. The default value is 20 minutes.

* `Initial Alert` -- xDrip+ will play a sound when an Initial Calibration is requested after a sensor start or restart.

## Missed reading Alert

This setting configures xDrip+ to alert if no data is recieved after x number of minutes. To enable this alert, check the `enable alert` box at the top of the screen. 

* `Alert if no data recieved in x minutes` -- xDrip+ will alert if no glucose data is recieved after x number of minutes. The default value is 30 minutes .
* `Select time for alert` -- You can set a custom timeframe for the alert. The default is `all day`.
* `Number of minutes before raising the same alert after snooze` -- If the alert is snoozed, xDrip+ will wait x minutes before re-alerting. The default value is 20 minutes.
* `Reraise alerts before snooze time`

  * `Alert Rereaise time (in SECONDS)`

## Other Alerts

#### Noisy Readings
* `Bad (noisy) Value Alerts`

  * `Alert after x minutes of noisy values` -- Default is 90 minutes.
  * `Alert Snooze` -- Number of minutes to wait before raising the same alert after snooze.
  * `Reraise alerts before snooze time` -- Reraise the alert if not snoozed sooner.
    * `Alert Reraise time` -- Number of SECONDS to pass before raising the same alert.

#### Falling/Rising BG
* `Bg falling fast`

  * `falling threshold` -- Sets the rate at which BG values must drop to trigger the `Bg falling fast` alert. The default is 3 mg/dl (0.16 mmol).
  
* `Bg falling fast`

  * `rising threshold` -- Sets the rate at which BG values must drop to trigger the `Bg falling fast` alert. The default is 3 mg/dl (0.16 mmol).
  

#### Alert Preferences (For these alerts)
* `Alert Sound` -- This setting allows you to set a custom tone for this alert.
* `Override Slient mode on these alerts` -- Off by default. Allows xDrip+ to override the "Do Not Disturb" feature on Android phones for this alert.

## Extra Alerts (xDrip+)

#### Persistent High Alert
* `Persistent High Alert` -- Alert if above high value for a specified length of time.

  * `for longer than (minutes)` -- The default value is 60 minutes.
  * `Repeating max every (minutes)` -- xDrip+ will re-alert if glucose continues to stay above high value. The default value is 30 minutes.
  * `Persistent High Sound` -- Allows you to set a custom tone for this alert.
  
#### Forecasted Low Alert
* `Forecast Lows` -- Extrapolate data to try to predict lows. This setting will display a unobtrusive message on the home screen when a low is predicted.
  * `Raise alarm on Forecast Low` -- Notify when predicted low time reaches theshold.
  * `Alarm at Forecasted low mins` -- The default value is 40 minutes.
  * `Predicted Low Sound` -- Allows you to set a custom tone for this alert.
  
#### Other xDrip+ Alerts
* `Collector battery alerts` -- Notify when batter level goes below x percentage.

  * `Low battery percentage` -- The default value is 30 percent.

* `Parakeet related alerts` -- Notify when parakeet device stops checking in.

  * `Silent alert when charging` -- Raise parakeet notification silently when charging.
  
* `Follower Chime New` -- Notify when data arrives from the master if the interval is > 20 minutes.
