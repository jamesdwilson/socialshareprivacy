
 Translation of [Heise's SocialSharePrivacy plugin][1].

English translation and modifications by James Wilson http://jameswilson.name


This was originally an automatically translated document, please feel free to contribute to improve it. <nav>
## Navigation

1.  [Change log][2]
2.  [Files][3]
3.  [Requirements and Limitations][4]
4.  [Dimensions][5]
5.  Simple integration
    1.  [Source][6]
    2.  [Explanation of codes][7]
6.  [Options][8]
    1.  [General][9]
    2.  [Facebook][10]
    3.  [Twitter][11]
    4.  [Google +][12]
7.  [Sample integrations][13]
    1.  [Only integrate Facebook][14]
    2.  [No option to permanently activate offer][15]
    3.  [Google only offer + and specify your own path to the CSS file.][16]
8.  [URL][17]
9.  [Remember my settings][18]
10. [License][19]
11. [Logo][20]</nav>

1.  ## Change log

    1.  ### Version 1.3

        *    First version, which can also be used multiple times on one page. This can be used in different instances of different URIs, the option is via `<font><font>uri</font></font>` laws feature a pop-DOM nodes passed through which one can identify a URI. Examples of the use we have the documentation for the <a href="#examples" rel="noreferrer">sample transclusions</a> added.
        *    Correction for IE <9: The per `<font><font>css_path</font></font>` specified style sheet has not been built with jQuery versions = 1.4.2!.
    2.  ### Version 1.2

        *    JS: Facebook app id, removed as it no longer necessary to use the Like / Recommend button.
    3.  ### Version 1.1

        *    CSS: At various elements we have added more information to the final configuration, keep in integrating into their own pages, lower. Above all, we have `<font><font>margin</font></font>` - `<font><font>padding</font></font>` - `<font><font>width</font></font>` and - `<font><font>height</font></font>` -added information.
        *    The document has been extended by a examples and this change log area.
        *    The plug-in content was slightly changed and made some code abbreviations.
        *    JS bug-fix: There was an error, if it is in the side of a `<font><font>canonical</font></font>` attribute was, but that was an empty value.
        *    JS-Bug correction: When the options of Google + there was a statement that was later interrogated in the script before.
        *    JS bug-fix: The Perma-option of Google + was only when the permafrost was enabled by Twitter.
        *    Twitter: If activated the iFrame was too large and layered underneath links. `<font><font><iframe ...style="width:130px; height:25px;"> </
                    iframe></font></font>` added.
        *   General: If the option is css_path empty, no link tag is fitted with an empty href in the page.
        *   General: The use of the buttons can now have the option URI `<font><font>uri</font></font>` can be controlled. It is both a fixed value, as a function possible. Default is the function included `<font><font>getUri</font></font>`
        *   **New features:**
            *   Facebook: The label versions of the button "Share" and "Like" can be controlled via the new "action". Values â€‹â€‹are " `<font><font>recommend</font></font>` "(default) and" `<font><font>like</font></font>` ".
            *   Twitter: parameter " `<font><font>language</font></font>` "(default" `<font><font>en</font></font>` ") now available for Twitter.
    4.  ### Version 1.0

        *   First public release
2.  ## Files

    Our plug-in includes the following files:

    *   index.html (the document you are reading)
    *   dimensions.gif (infographics for this document)
    *   2-click-logo_min.jpg (small logo)
    *   jquery.socialshareprivacy.js
    *   jquery.socialshareprivacy.min.js
    *   socialshareprivacy / socialshareprivacy.css
    *   socialshareprivacy / images / dummy_facebook.png
    *   socialshareprivacy / images / dummy\_facebook\_en.png
    *   socialshareprivacy / images / dummy_gplus.png
    *   socialshareprivacy / images / dummy_twitter.png
    *   socialshareprivacy / images / settings.png
    *   socialshareprivacy / images / socialshareprivacy_info.png
    *   socialshareprivacy / images / socialshareprivacy\_on\_off.png
    *   socialshareprivacy/images/2-klick-logo.jpg
3.  ## Requirements and Limitations

     Technical requirements are jQuery and JavaScript enabled in your browser. We tested with jQuery 1.4.
     The plug-in can now be used within an HTML page only once.

     If you have any suggestions for improvement, please contact us via email at <a href="https://mail.google.com/mail/?view=cm&fs=1&tf=1&to=2klick@heise.de&su=Vorschlag%20zum%20Plug-In" rel="noreferrer" target="_blank">2klick@heise.de</a> .

     The permanent activation of the service works only in Internet Explorer, version 8, because previous versions do not support JSON. Therefore, absent in IE <= 7 this function. The rest of the plug-ins is not affected.

    For its own Facebook app mandatory ID is required, see [Note on the Facebook app id][21] .

4.  ## Dimensions

    ![Dimensions of the plug-ins][22]
     The plug-in requires a total of about 600 pixels in width (when all services are running) and about 290 pixels in height, but this depends also on the length of the specified mouse-over text.

5.  1.  ## Integration

            <font><font><head></font></font><font></font><font><font>
                ...</font></font><font></font><font><font class="">
                Click Here src="jquery.js"> </ script> </font></font><font></font><font><font>
                Click Here src="jquery.socialshareprivacy.js"> </ script></font></font><font></font><font><font>
                <script type="text/javascript"></font></font><font></font><font><font>
                jQuery (document). ready (function ($) {</font></font><font></font><font><font>
                if ($ ('# socialshareprivacy'). length> 0) {</font></font><font></font><font><font class="">
                $ ('# Socialshareprivacy') socialSharePrivacy ().; </font></font><font></font><font><font>
                }</font></font><font></font><font><font>
                });</font></font><font></font><font><font>
                </ Script></font></font><font></font><font><font>
                ...</font></font><font></font><font><font>
                </ Head></font></font><font></font><font><font>
                <body></font></font><font></font><font><font>
                ...</font></font><font></font><font><font>
                <div id="socialshareprivacy"> </ div></font></font><font></font><font><font>
                ...</font></font><font></font><font><font>
                </ Body></font></font>


    2.  ### Explanation of codes

            <font><font>Click Here src="jquery.js"> </ script> </font></font><font></font><font><font>
                Click Here src="jquery.socialshareprivacy.js"> </ script></font></font>


         The first line binds the JavaScript framework "JQuery" ( <a href="http://jquery.com/" rel="noreferrer">http://jquery.com/</a> ) that the second line of our plug-in. jQuery is our package **is not** in, you have yet to even download it from the aforementioned website.

            <font><font><script type="text/javascript"></font></font><font></font><font><font>
                jQuery (document). ready (function ($) {</font></font><font></font><font><font>
                if ($ ('# socialshareprivacy'). length> 0) {</font></font><font></font><font><font>
                $ ('# Socialshareprivacy') socialSharePrivacy ().; </font></font><font></font><font><font>
                }</font></font><font></font><font><font>
                });</font></font><font></font><font><font>
                </ Script></font></font>


         In this `<font><font><script></font></font>` will block the plug-in function to an arbitrary hanging, empty HTML element in the side, in this case, the element with the `<font><font>id </font></font>` *socialshareprivacy* .
         order to attach the plug-ins will only happen if the element is actually present, we do not have the control function `<font><font>if</font></font>` that surrounds the attachment and check the necessary condition.

            <font><font><body></font></font><font></font><font><font>
                ...</font></font><font></font><font><font>
                <div id="socialshareprivacy"> </ div></font></font><font></font><font><font>
                ...</font></font><font></font><font><font>
                </ Body></font></font>


         Somewhere in `<font><font><body></font></font>` section of the website you placed the empty HTML element with the desired `<font><font>id</font></font>` , used for the same `<font><font>id</font></font>` in the previous `<font><font><script></font></font>` block needs to be.

6.  ## Options

     To integrate a variety of options are available. The following are the general options listed first and then the options for the individual services (Facebook, Twitter, Google +) are listed.
     example of a call with options:

        <font><font>$ ('# Socialshareprivacy'). SocialSharePrivacy ({</font></font><font></font><font><font>
            services: {</font></font><font></font><font><font>
            facebook: {</font></font><font></font><font><font>
            'Perma_option': 'off'</font></font><font></font><font><font>
            }, </font></font><font></font><font><font>
            twitter: {</font></font><font></font><font><font>
            'Status': 'off'</font></font><font></font><font><font>
            },</font></font><font></font><font><font>
            GPlus: {</font></font><font></font><font><font>
            'Display_name': 'Google Plus'</font></font><font></font><font><font>
            }</font></font><font></font><font><font>
            },</font></font><font></font><font><font>
            'Cookie_domain': 'heise.de'</font></font><font></font><font><font>
            });</font></font>


    1.  <caption>general options</caption> Option

        Default

        Description

        info_link

        http://www.heise.de/ct/artikel/2-Klicks-fuer-mehr-Datenschutz-1333879.html

        Link to detailed privacy information, in our case an H-item.

        txt_help

        *Text*

        Mouseover text of the *i* -icon

        settings_perma

        Remember to enable data transfer and agree:

        Headline of the settings menu

        cookie_path

        /

        Path of the cookie

        cookie_domain

        `<font><font>document.location.host</font></font>`

        Domain for which the cookie is valid

        cookie_expires

        365

        The duration of the cookie is valid in days

        css_path

        socialshareprivacy / socialshareprivacy.css

        Path to CSS file, empty if no stylesheet is installed

        uri

        getUri

        The URI to be passed by the buttons. Possible is a fixed value (eg `<font><font>"http://www.heise.de"</font></font>` ) or function (see `<font><font>function getUri ()</font></font>` in the Plug-in source code)

    2.  <caption>Options: Facebook</caption> Option

        Default

        Description

        status

        on

        The user has to select Facebook

         app_id

        *omitted (since version 1.2)*

        Facebook App-ID, it is necessary to the *Recommended* button can take advantage of Facebook. If it is not specified, the user despite Facebook `<font><font>'status':
                    'on' </font></font>` **not** available. In the JavaScript console, the developer a notice is issued.

        dummy_img

        socialshareprivacy / images / dummy_facebook.png

        Path to the static graphics

        txt_info

        *Text*

        Mouseover text of the Recommended button

        txt\_fb\_off

        not linked to Facebook

        Text equivalent of graphic switch in the off state, generally not visible to the user

        txt\_fb\_on

        connected to Facebook

        Text equivalent of graphic switch in the ON state, generally not visible to the user

        perma_option

        on

        The user has the option to leave Facebook show permanently (via a cookie)

        display_name

        Facebook

        Spelling of the service in the options

        referrer_track

        Â

        Is hung at the end of the URL, referrer tracking can be used

        language

        en_US

        Language setting

        action

        recommend

        Label of the button: Recommended ( `<font><font>recommend</font></font>` ) or like me ( `<font><font>like</font></font>` )

    3.  <caption>Options: Twitter</caption> Option

        Default

        Description

        status

        on

        The user has to choose from Twitter

        dummy_img

        socialshareprivacy / images / dummy_twitter.png

        Path to the static graphics

        txt_info

        *Text*

        Mouseover text of the Tweet button

        txt\_twitter\_off

        not associated with Twitter

        Text equivalent of graphic switch in the off state, generally not visible to the user

        txt\_twitter\_on

        associated with Twitter

        Text equivalent of graphic switch in the ON state, generally not visible to the user

        perma_option

        on

        The user has the option to leave permanently Show Twitter (via a cookie)

        display_name

        Twitter

        Spelling of the service in the options

        referrer_track

        Â

        Is hung at the end of the URL, referrer tracking can be used

        tweet_text

        `<font><font>getTweetText</font></font>`

         The function checks whether the meta tag `<font><font>DC.title</font></font>` there and use those. Is it also still `<font><font>DC.creator</font></font>` this is somewhat removed ("-") is appended. Is `<font><font
                    class="">DC.title</font></font>` No <title> the tag of the page is used.
         This option can use his own text ( `<font><font class="">typeof ==
                string</font></font>` will be overwritten) or with a specific function ( `<font><font class="">typeof == function</font></font>` ) that generates the text.
         The passed text is always truncated to 120 characters and spaces with the last ... replaced.

        language

        s

        Language setting (the default is " `<font><font>en</font></font>` "yes, we like it better than Twitter Tweet)

    4.  <caption>Options: Google +</caption> Option

        Default

        Description

        status

        on

        The user has selected Google to +

        dummy_img

        socialshareprivacy / images / dummy_gplus.png

        Path to the static graphics

        txt_info

        *Text*

        Mouseover text of "+1" button

        txt\_gplus\_off

        not associated with Google +

        Text equivalent of graphic switch in the off state, generally not visible to the user

        txt\_gplus\_on

        + associated with Google

        Text equivalent of graphic switch in the ON state, generally not visible to the user

        perma_option

        on

        The user has the option to let Google map + permanently (via a cookie)

        display_name

        Google +

        Spelling of the service in the options

        referrer_track

        Â

        Is hung at the end of the URL, referrer tracking can be used

        language

        de

        Language setting

7.  ## Sample integrations

     The following are a few examples of common configurations of transclusions.

    *   ### Only integrate Facebook

            <font><font>$ ('# Socialshareprivacy'). SocialSharePrivacy ({</font></font><font></font><font><font>
                services: {</font></font><font></font><font><font>
                twitter: {</font></font><font></font><font><font>
                'Status': 'off'</font></font><font></font><font><font>
                },</font></font><font></font><font><font>
                GPlus: {</font></font><font></font><font><font>
                'Status': 'off'</font></font><font></font><font><font>
                }</font></font><font></font><font><font>
                }</font></font><font></font><font><font>
                });</font></font>


    *   ### No option to permanently activate offer

            <font><font class="">$ ('# Socialshareprivacy'). SocialSharePrivacy ({</font></font><font></font><font><font>
                services: {</font></font><font></font><font><font>
                facebook: {</font></font><font></font><font><font>
                'Perma_option': 'off'</font></font><font></font><font><font>
                }, </font></font><font></font><font><font>
                twitter: {</font></font><font></font><font><font>
                'Perma_option': 'off'</font></font><font></font><font><font>
                },</font></font><font></font><font><font>
                GPlus: {</font></font><font></font><font><font>
                'Perma_option': 'off'</font></font><font></font><font><font>
                }</font></font><font></font><font><font>
                }</font></font><font></font><font><font>
                });</font></font>


    *   ### Google only offer + and specify your own path to the CSS file.

            <font><font>$ ('# Socialshareprivacy'). SocialSharePrivacy ({</font></font><font></font><font><font>
                services: {</font></font><font></font><font><font>
                facebook: {</font></font><font></font><font><font>
                'Status': 'off'</font></font><font></font><font><font>
                }, </font></font><font></font><font><font>
                twitter: {</font></font><font></font><font><font>
                'Status': 'off'</font></font><font></font><font><font>
                }</font></font><font></font><font><font>
                },</font></font><font></font><font><font>
                'Css_path': '/ style / plugins / socialshareprivacy.css'</font></font><font></font><font><font>
                });</font></font>


    *   ### Several 2-click button bars on one side

        #### Option 1: A call to the appropriate plug-ins with a selector

            <div class="anriss">
                <h3> <a href="http://www.heise.de"> heise </ a> </
                h3>
                <p> lorem ipsum </ p>
                <div class="social"> </ div>
                </ Div>

                    <div class="anriss">
                    <h3> <a href="http://www.heise.de/security/"> heise security </ a> </
                    h3>
                    <p> dolor sit amet </ p>
                    <div class="social"> </ div>
                    </ Div>

                    <script>
                    $ (". Social"). SocialSharePrivacy ({
                    uri: function (context) {
                    return $ (context) parents ("anriss.") find ("h3 a") attr ("href")...;
                    }
                    });
                    </ Script>


        #### Option 2: Multiple call the plug-ins

            <div>
                <h3> <a href="http://www.heise.de"> heise </ a> </
                h3>
                <p> lorem ipsum </ p>
                <div id="one"> </ div>
                </ Div>
                <script>
                $ ("# One"). SocialSharePrivacy ({
                uri: "http://www.heise.de"
                });
                </ Script>

                    <div>
                    <h3> <a href="http://www.heise.de/security/"> heise security </ a> </
                    h3>
                    <p> dolor sit amet </ p>
                    <div id="two"> </ div>
                    </ Div>
                    <script>
                    $ ("# Two"). SocialSharePrivacy ({
                    uri: "http://www.heise.de/security/"
                    });
                    </ Script>


8.  ## URL

     The URL that the service is transferred can be controlled via an option.
    By default, a function within the plug-ins, the URL of the current page `<font><font>document.location.href</font></font>` determined, however, is a canonical deposited ( `<font><font><link rel =
        "canonical"></font></font>` ), this will be taken.

9.  ## Remember settings

     Before the cookie is requested, as are the settings the user will first examine how the plug-in is configured. If the plug-in has been changed, the user may subsequently no disadvantages.
     was turned off for all services the watch list function ( `<font><font class="">'perma_option':
        'off'</font></font>` ) disappears and the setting menu.

10. ## License

     This plug-in is under the MIT License ( <a href="http://www.opensource.org/licenses/mit-license.php" rel="noreferrer">http://www.opensource.org/licenses/mit-license.php</a> ) and must be happy for private, as well as commercial purposes only.
