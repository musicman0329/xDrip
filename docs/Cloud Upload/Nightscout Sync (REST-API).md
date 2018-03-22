### Nightscout Sync (REST-API)
The Nightscout Sync (REST-API) upload option is the preferred method for uploading data to Nightscout.

Follow these steps in order to enable REST-API syncing with Nightscout. 
  * Go to Settings > Cloud Upload > Nightscout Sync (REST-API). 
  * Slide the "Enabled" switch to the right.
  * In the `Base URL` field, enter your Nightscout URL. It will be in one of two formats, depending on where you decided to host your Nightscout site.
  
 ```
 https://yourAPIsecret@yourSITEname.azurewebsites.net/api/v1
 OR
 https://yourAPIsecret@yourSITEname.herokuapp.com/api/v1
 ```

#### Settings

* `Use mobile data` -- Upload even when using mobile data
* `Send Display Glucose` -- Use noise smoothing and plugs etc (if enabled) for broadcasted value
* `Download data` -- Also try to download data from Nightscout.
* `Automatic Calibration` -- Calibrate using new blood glucose readins if the conditions appear right to do so without asking confirmation (experimental).

#### Extra Options

* `Skip LAN uploads` -- For local servers with 192.168.x.x addresses, skip uploads when there is no local network connectivity.
* `Upload bridge battery` -- Send your bridge battery level to Nightscout. Uncheck if your battery sensor is broken.
* `Upload treatments` -- Send treatment data to Nightscout. Uncheck if your careportal is broken.
* `Alert on failures` -- Display and sound a notification if Nightscout uploads are failing.
* `Back-fill data` -- Tap to send historical data to Nightscout.
