# dp_popup_plugin

This plugin provides a pop-up download form in Wordpress which is displayed when called by an HTML button.

    <input type=button value="Download" onClick="openForm();">

It allows for the display of a top banner by passing in a value for parameter 'banner_image'

This plugin will display a 'Download on the Apple Store' button. To specify the navigate to url pass in a value
for parameter 'apple_store_url'

This plugin will display a 'Get it on Google Play' button. To specify the navigate to url pass in a value
for parameter 'google_play_url'

Lastly, a 'close' button is displayed at the bottom of the form which will closed the pop-up form when clicked.

To call from WordPress add the following ShortCode.

  [popup-plugin button_text="Download Today" banner_image="" apple_store_url="" google_play_url=""]

