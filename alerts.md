# Alerts
In the configuration.md section you will have seen that a lot of the objects marked out by OptiStruct enable you to set alerts which will notify you upon specific events. 
This is useful because it allows you to close Tradingview and do other activities whilst our software monitors price actions for you. 

## Monitoring
OptiStruct will monitor the following:

- Any instrument available in Tradingview
- Multiple time frames for the selected instruments
- Any combination of events such as mitigations, sweeps, BoS, CHoCH Etc.

!!!
By combining OptiStruct with our other indicators you can also monitor session liquidity and daily/weekly/monthly liquidity with the exact same automation
!!!

OptiStruct puts Tradingview on steroids. Once configured properly and in the way that you would normally watch the charts, you can leave your desk and do other things.

## Configuration
One of the best things about OptiStruct is how easy it is to configure. We first tell OptiStruct what events we would to be notified upon before configuring Tradingview to listen for them. Let's go through the steps to set your trading day to autopilot!

### Prerequisites
Firstly, we must decide which events we would like to be notified for, such as EOB mitigations or high/low sweeps. This is extremely simple and the instructions can be found for each event in the relevant part of the configuration section of this documentation. It is possible to configure Tradingview first but the way we advise does give a better understanding of the work flow. Once you have configured OptiStruct's alerts, move on to the next section. To be comprehensive, we will demonstrate how to configure OptiStruct to send an alert when an extreme POI is mitigated.

This steps must be carried out for each event that you would like to be alerted for. It really is that easy!

![](/assets/img/docs-optistruct-3-configuration-3-alerts-pre.png)



### Configure Tradingview
This is another very easy step. It must be carried out for each pair and each time frame that you would like to be notified for.
For example if you would like to be notified on all of the criteria that is selected in the OptiStruct configuration for EURUSD on the H4, H1 and M15 time frames then it must be explicitly done. Here is how it is done.
![](/assets/img/docs-optistruct-3-configuration-3-alerts-main-1.pn-mh.png)

When you have clicked on the 'Add Alert on...' button within Tradingview you will be presented with the popup dialog shown in the image below. To reiterate, this process must be carried out on each pair and each time frame that you would like to be notified on.

![](/assets/img/docs-optistruct-3-configuration-3-alerts-main-2.pn-mh-2.png)

So the steps would be:

- Select a pair
- Select a time frame
- Carry out the instructions in the 'Configure Tradingview' section above

You will need to carry out these steps several times, for example...

- EURUSD H4
- EURUSD H1
- EURUSD M15
- GBPUSD H4
- GBPUSD H1
- GBPUSD M15
- XAUUSD H4
- XAUUSD H1
- XAUUSD M15 

### Final Result
Once you have completed the steps then you be able to click on the alerts section of Tradingview and see something like this...
![](/assets/img/docs-optistruct-3-configuration-3-alerts-main-alerts-tab.png)