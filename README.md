# dp_popup_plugin

This plugin provides a pop-up download form in Wordpress which is displayed when called by an HTML button.

    <input type=button value="Download" onClick="openForm();">

1.  It allows for the display of a top banner by passing in a value for parameter 'banner_image'

2.  This plugin will display a 'Download on the Apple Store' button. To specify the navigate to url pass in a value
    for parameter 'apple_store_url'

3.  This plugin will display a 'Get it on Google Play' button. To specify the navigate to url pass in a value
    for parameter 'google_play_url'

4. Lastly, a 'close' button is displayed at the bottom of the form which will closed the pop-up form when clicked.

    <button type="button" class="formSubmitBtn" onclick="closeForm()">Close</button>
    
To install: 
    
    Download zip file
    Upload zip file into WordPress

To call from WordPress add the following ShortCode.

    [popup-plugin button_text="Download Today" banner_image="" apple_store_url="" google_play_url=""]

