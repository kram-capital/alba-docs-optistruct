# Configuration

OptiStruct has a plethora of settings enabling you to configure not only the look and feel of the indicator, but also the functionality so that you can tailor your experience to your exact needs. OptiStruct aims to be unopinionated about the way that you trade so that it can be moulded around you and the elements of the strategy that you use. Let's start by opening up the configuration options.
## View the settings
Please take a look at the official Tradingview documentation if you are unsure on how to view the configuration settings for the indicators that are applied to your chart and the return to this page for the OptiStruct specific configuration options.
[!ref target="blank" text="Official Docs"](https://shorturl.at/isyY6)
# Settings Overview
## Inputs Tab

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
:   This setting is useful if you have chosen a recent date in the previous option in case OptiStruct doesn't have enough data to calculate the trend 
===

### BoS / ChoCh

==- Click to expand 

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
Triggering alerts requires an additional step that will be explained in the alerts section 
!!!
===
### Inducements
==- Click to expand 
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
:   Mark new inducements in real-time

Alerts when market takes out IDMs
:   Trigger an alert in Tradingview when the market takes out an IDM

!!!
Triggering alerts requires an additional step that will be explained in the alerts section 
!!!

===
### High / Low markings
==- Click to expand 

![](/assets/img/docs-optistruct-3-configuration-1-inputs-4-high-lo-mh.png)

Mark H/L
:   Mark the highs and lows on the chart

Row 1
:   In order from left to right
    - Size of swing marker
    - Toggle between a graphical and textual representation

Row 2
:   In order from left to right
    - Higher low label (if textual)
    - Higher low colour (if graphical)
    - Higher high label (if textual)
    - Higher high colour (if graphical)

Row 3
:   In order from left to right
    - Lower high label (if textual)
    - Lower high colour (if graphical)
    - Lower low label (if textual)
    - Lower lower colour (if graphical)

===
### High / Low sweeps
==- Click to expand 
![](/assets/img/docs-optistruct-3-configuration-1-inputs-5-high-lo-mh.png)

Show H/L sweeping lines
:   Mark the highs and lows sweeps on the chart

Row 1
:   In order from left to right
    - Text label of the sweep line
    - Size of the text label
    - Colour of the text label

Row 2
:   In order from left to right
    - Sweep line type
    - Sweep line thickness

Alerts when market sweeps out previous H/L
:   Trigger an alert in Tradingview when the market sweeps a previous H/L

!!!
Triggering alerts requires an additional step that will be explained in the alerts section 
!!!

===
### Extreme Order Blocks
==- Click to expand 
![](/assets/img/docs-optistruct-3-configuration-1-inputs-6-extreme-mh.png)

Show Extreme Order Blocks
:   Mark extreme order blocks on chart

Alert on extreme order block mitigation <!-- TODO tell the team about wording -->
:   Trigger an alert in Tradingview when the market mitigates an extreme order block

Label attributes
:   In order from left to right
    - Size of the text label
    - Border of the rectangle style
    - Width of the rectangle border

Row 1 (Bullish EOB)
:   In order from left to right
    - Label colour
    - Background colour
    - Border colour (width must be > 0)

Row 2 (Bearish EOB)
:   In order from left to right
    - Label colour
    - Background colour
    - Border colour (width must be > 0)


!!!
Triggering alerts requires an additional step that will be explained in the alerts section 
!!!


===


### Decisional Order Blocks
==- Click to expand 
![](/assets/img/docs-optistruct-3-configuration-1-inputs-7-decisio-mh.png)

Show Decisional Order Blocks
:   Mark the decisional order blocks on the chart 

Alert on decisional order block mitigation <!-- TODO tell the team about wording -->
:   Trigger an alert in Tradingview when the market mitigates a decisional order block

Label attributes
:   In order from left to right
    - Size of the text label
    - Border of the rectangle style
    - Width of the rectangle border

Row 1 (Bullish DOB)
:   In order from left to right
    - Label colour
    - Background colour
    - Border colour (width must be > 0)

Row 2 (Bearish DOB)
:   In order from left to right
    - Label colour
    - Background colour
    - Border colour (width must be > 0)


!!!
Triggering alerts requires an additional step that will be explained in the alerts section 
!!!


===

### Smart Money Traps
==- Click to expand 
![](/assets/img/docs-optistruct-3-configuration-1-inputs-8-smart-m-mh.png)

Show Smart Money Traps
:   Mark the smart money traps on the chart layout

Alert on smart money trap mitigation <!-- TODO tell the team about wording -->
:   Trigger an alert in Tradingview when the market mitigates a smart money trap

Label attributes
:   In order from left to right
    - Size of the text label
    - Border of the rectangle style
    - Width of the rectangle border

Row 1 (Bullish SMT)
:   In order from left to right
    - Label colour
    - Background colour
    - Border colour (width must be > 0)

Row 2 (Bearish SMT)
:   In order from left to right
    - Label colour
    - Background colour
    - Border colour (width must be > 0)


!!!
Triggering alerts requires an additional step that will be explained in the alerts section 
!!!


===

### IDMs Demands / Supplies
==- Click to expand 
![](/assets/img/docs-optistruct-3-configuration-1-inputs-9-ob-with-mh.png)

IDM demand/supplies are supply and demand zones that print before an inducement has been taken

Show IDM Demand / Supply
:   Mark the demand/supplies on the chart layout

Alert on demand/supplies mitigation
:   Trigger an alert in Tradingview when the market mitigates an IDM demand/supply

Label attributes
:   In order from left to right
    - Size of the text label
    - Border of the rectangle style
    - Width of the rectangle border

Row 1 (Bullish IDM D/S)
:   In order from left to right
    - Label colour
    - Background colour
    - Border colour (width must be > 0)

Row 2 (Bearish IDM D/S)
:   In order from left to right
    - Label colour
    - Background colour
    - Border colour (width must be > 0)


!!!
Triggering alerts requires an additional step that will be explained in the alerts section 
!!!


===

### Historical Order Blocks
==- Click to expand 
![](/assets/img/docs-optistruct-3-configuration-1-inputs-9-ob-with-mh.png)

Show historical order blocks
:   Mark the historical order blocks on the chart layout

Alert on every historical order blocks mitigation 
:   Trigger an alert in Tradingview when the market mitigates an historical order block

Add a prefix to historical OBs 
:   Specify some text to prepend order block label

Label attributes
:   In order from left to right
    - Size of the text label
    - Border of the rectangle style
    - Width of the rectangle border

Row 1 (Bullish historical order blocks)
:   In order from left to right
    - Label colour
    - Background colour
    - Border colour (width must be > 0)

Row 2 (Bearish historical order blocks)
:   In order from left to right
    - Label colour
    - Background colour
    - Border colour (width must be > 0)

Keep the aesthetic options of historical order blocks 
:   If this is checked then visual settings above will be ignored and historical order blocks will retain the look of the standard decisional and extreme POIs
<br />Ask the team 

!!!
Triggering alerts requires an additional step that will be explained in the alerts section 
!!!


===

## Style Tab
![](/assets/img/docs-optistruct-3-configuration-1-inputs-11-style.png)
The three settings within the style tab are to globally toggle the visibility of the drawings created by OptiStruct.

Style settings
:   &nbsp;
    - Display or hide all OptiStruct boxes
    - Display or hide all OptiStruct labels
    - Display or hide all OptiStruct lines


## Visibility Tab
This is outside of the scope of our software but below is a link where you will find the official documentation.
[!ref target="blank" text="Official Docs"](https://shorturl.at/rGSUZ)
