iOS Round #2
==========

Target: Verify objective-c and iOS development skills

## Assignment
You have a [list of webviews](http://appcontent.hotelquickly.com/en/1/ios/index.json) with defined URLs. Create an iPhone application with a list of all webviews. Click on a webview name should open new screen with webview content.  

Webviews with parameter ```cache == true ``` should be downloaded in background so when user opens it, content is loaded from cache. If content is downloaded from network not from cache, activityIndicator should be shown.

##### Specification:
* Use key from json as a name of webview
* Use this values for replacements in URLs:
	* {userId} = 276
	* {appSecretKey} = gvx32RFZLNGhmzYrfDCkb9jypTPa8Q
	* {currencyCode} = USD
	* {offerId} = 10736598
	* {selectedVouchers} = []

##### Bonus questions
* If URL of webview changes, will application load content from new URL?
* We would like to have a link in webview, that will open some native screen in application. Is it possible? How would you do it?
