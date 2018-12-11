# cryptohoper
AutoTrade Bot For Windows
 CH Companion
What's this?

CH Companion is a browser extension that lets you auto-select most traded coins using TradingView's volume data in CH config page.

image
How does it work?

When you press the "Select coin" button, CH Companion queries TradingView for latest data with this strategy:

    It orders by volume DESC, using 24h candles
    It filters by the exchange and base currency you have input
    It keeps all the currencies you have put in the whitelist field
    It throws away from the results the currencies you have put in the blacklist field
    It optionally filters out the results that don't match the min % volatility threshold
    It optionally filters out the results that don't match the max % change threshold
    It optionally filters out the results that don't match the Oscillators rating requirements (Strong buy, buy and neutral)
    It limits the results to the number of coins you have input in limit field

And finally it will auto-select the resulting coins on your CH config page.
Disclaimer

    I'm not responsible for any losses you might occur using this software. Use it at your own risk.
    Since data comes from a third party website (TradingView) the results may not be consistent with the data shown on your exchange website (eg: Volume on Binance).
    Always check the selected currencies before applying changes

Installation for Firefox

    Download the XPI extension from --> here <--
    Go to the Add-ons page in Firefox (about:addons)
    Drag-and-drop the downloaded file in this page

Installation for Chrome

    Download the ZIP extension from --> here <--
    Extract the zip file
    Go to Chrome Extensions page (chrome://extensions/)
    Enable "Developer mode"
    Click on "Load unpacked" and select the folder where you unzipped the file

Upgrade

    Remove the old version
    Install the new one

Watch out: upgrading may erase your saved settings. Keep note of them before proceeding!
Usage

    Go to your CH config page
    Click on the extension icon
    Set preferences. Watch out: Blacklist and whitelist accept comma separated values! Eg: USDT, BNB.
    Click on the "Select coins" button

That's it!
To do

    Proper logo
    Publish this on Chrome Web Store
    Publish this on Firefox Add-ons
    Buy a Lambo
