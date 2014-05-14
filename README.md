iOS Round #2
==========

Target: Verify objective-c and iOS development skills

## Assignment
You have a [list of webviews](http://appcontent.hotelquickly.com/en/1/ios/index.json) with defined URLs. Create an iPhone application with a list of all webviews. Click on a webview name should open new screen with webview content.  

Webviews with parameter ```cache == true ``` should be preloaded in background. When user opens a webview, content should be loaded from cache. If content is downloaded from network, not from cache, activityIndicator should be shown.

Please write clean & maintainable code to implement the relevant functionality. Simply writing correct code isn't enough.

Coding will be shared over ScreenShare. Please do not write any code before screensharing session.

##### Specification:
* Usage of thrid party libraries is allowed
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

##### Timeframe
* 30 minutes for preparation (without writing the code)
* 60 minutes coding with screen share (It does not have to be completely finished in this time)
* 15-30 minutes additional questions


##### Prerequisite
* Download, install, register in [ScreenHero app](http://screenhero.com/)
* Add Josef as a contact - josef.nevoral@hotelquickly.com
* In GitHub, fork this repository to you own account
* The solution, after finished, should be send as pull request to original HQ repository.
