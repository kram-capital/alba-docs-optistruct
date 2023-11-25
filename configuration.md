# Configuration

OptiStruct has a plethora of settings enabling you to configure not only the look and feel of the indicator, but also the functionality so that you can tailor your experience to your exact needs. OptiStruct aims to be unopinionated about the way that you trade so that it can be moulded around you and the elements of the strategy that you use. Let's start by opening up the configuration options.
## View the settings
Please take a look at the official Tradingview documentation if you are unsure on how to view the configuration settings for the indicators that are applied to your chart and the return to this page for the OptiStruct specific configuration options.
[!ref target="blank" text="Official Docs"](https://shorturl.at/isyY6)
## Settings Overview
### Inputs Tab

=== Initialisation
![](/assets/img/docs-optistruct-3-configuration-1-inputs-1.png)

Use Structure Mapping v2
:   Use an earlier version of the structure mapping algorithm. Note that some features will be unavailable if this setting is on.

Confirm CHoCH with wicks
:   Configure OptiStruct to recognise wicks as valid changes of character

Confirm BoS with wicks
:   Configure OptiStruct to recognise wicks as valid structure breaks

Starting
:   Set the date and time that you would like OptiStruct to begin the mapping on the chart. This can help with performance. Leaving the default setting will map from the beginning of the chart

Initial Trend
:   Not sure what this does <!-- TODO What is this? -->
===
=== BoS/CHoCH (Click to expand) <!-- TODO Configure collapsed panels for production -->
![](/assets/img/docs-optistruct-3-configuration-1-inputs-2-bos-cho-mh.jpg)

Mark BoS / CHoCH
:   Toggles the marking of BoS and CHoCH instances

Failed Structures Bullish
:   Colour of bullish BoS / CHoCH markings

Failed Structures Bearish
:   Colour of bearish BoS / CHoCH markings

Row 1
:   In order from left to right
    - BoS label
    - BoS line type
    - BoS line thickness

Row 2
:   In order from left to right
    - CHoCH label
    - CHoCH line type
    - CHoCH line thickness

Failed Structure
:   When price breaks structure without taking an inducement
    - Bullish colour line
    - Bearish colour line

Row 3
:   In order from left to right
    - Failed BoS label
    - Failed BoS line type
    - Failed BoS line thickness

Row 4
:   In order from left to right
    - Failed CHoCH label
    - Failed CHoCH line type
    - Failed CHoCH line thickness

Alert when BoS/ChoCh is confirmed
:   Trigger an alert in Tradingview when a BoS / ChoCh is confirmed

Alert when fake BoS/ChoCh is confirmed
:    Trigger an alert in Tradingview when a fake BoS is confirmed


!!!
Triggering alerts requires an additional step that will be explained in the alerts section <!-- TODO create link to alerts section -->
!!!
===
=== Inducements (Click to expand) <!-- TODO Configure collapsed panels for production -->
![](/assets/img/docs-optistruct-3-configuration-1-inputs-3-inducem-mh.png)

Mark IDM
:   Mark inducements on the chart

Row 1
:   In order from left to right
    - IDM label
    - Label text size
    - Label text colour

Row 2
:   In order from left to right
    - IDM line type
    - IDM line thickness

Mark live IDM
:   Mark live IDM <!-- What does this mean? -->

Alerts when market takes out IDMs
:   Trigger an alert in Tradingview when IDM is taken
    

!!!
Triggering alerts requires an additional step that will be explained in the alerts section <!-- TODO create link to alerts section -->
!!!
===

### Style Tab

### Visibility Tab