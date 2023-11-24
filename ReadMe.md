Because we exceed the 20000 character in our code we cant work inside of WebFlow we had to call our code from an outsource. Currently we are using GitHub for that. It works like this;
Create a new repository from GitHub, create a file, paste all the code including what you like to implement. When you commit your change if you go to link of 
https://cdn.jsdelivr.net/gh/YOUR GITHUB NAME/YOUR REPOSITORY NAME/YOUR FILE NAME        exampleLink = https://cdn.jsdelivr.net/gh/ET45/EnergyBE/data28.js
you should be able to see your code. When you change your code, dont edit the code inside of the file. It does not change your cdn.jsdelivr file. You should create a new file and paste your updated code there and it will create a new cdn.jsdelivr.
From there go to webFlow, get in the project, on top left corner you will see the small WEBFLOW logo. Click on the logo, on dropdown click the Site Setting. 
On the new page there is a list on the left side, click Custom Code at the bottom of that list. Inside Footer code there is <script type="text/javascript" src="https://cdn.jsdelivr.net/gh/ET45/EnergyBE/data28.js"></script>
Change the src="" inside of the script with your cdn.jsdeliver code.

The IDs we used in the project to match with the WebFlow frontend are represented at down.

heaterButton - Heater Action Button
heaterButtonDisabled - Disabled Heater Button
heaterText - Heater Information Text
heaterTextDisabled - Disabled Heater Text
panelButton - Solar Panel Button
panelButtonDisabled - Disabled Panel Button
panelText - Panel Information Text
panelTextDisabled - Disabled Panel Text
houseButton - House Selection Button
houseButtonDisabled - Disabled House Button
houseText - House Information Text
houseTextDisabled - Disabled House Text
yearButton - Year Selection Button
yearButtonDisabled - Disabled Year Button
yearText - Year Information Text
yearTextDisabled - Disabled Year Text
personButton - Person Selection Button
personButtonDisabled - Disabled Person Button
personText - Person Information Text
personTextDisabled - Disabled Person Text
2023resultGas - Gas Results 2023
2023resultGasHigh - High Gas Results 2023
2023resultElectric - Electric Results 2023
2023resultElectricHigh - High Electric Results 2023
2035resultGasHigh - High Gas Results 2035
2035resultElectricHigh - High Electric Results 2035
2035resultGasLow - Low Gas Results 2035
2035resultElectricLow - Low Electric Results 2035
2023resultWarmte - Warmte Results 2023
2023resultWarmteHigh - High Warmte Results 2023
2035resultWarmteHigh - High Warmte Results 2035
2035resultWarmteLow - Low Warmte Results 2035
2023NetbeheerkostenLow - Low Netbeheer Costs 2023
2023NetbeheerkostenHigh - High Netbeheer Costs 2023
2035NetbeheerkostenLow - Low Netbeheer Costs 2035
2035NetbeheerkostenHigh - High Netbeheer Costs 2035
2023resultTeruglevering - Teruglevering Results 2023
2035resultTerugleveringLow - Low Teruglevering 2035
2023resultTerugleveringHigh - High Teruglevering 2023
2035resultTerugleveringHigh - High Teruglevering 2035
calculate - Calculate Button
Stroom - Electricity Input
Stroom-2 - Gas Input
Stroom-3 - Warmte Input
resultHighRed - High Cost Indicator Red
resultHighGreen - High Cost Indicator Green
resultLowRed - Low Cost Indicator Red
resultLowGreen - Low Cost Indicator Green
electricHighGreen - High Electric Green Indicator
electricHighRed - High Electric Red Indicator
electricLowGreen - Low Electric Green Indicator
electricLowRed - Low Electric Red Indicator
gasHighGreen - High Gas Green Indicator
gasHighRed - High Gas Red Indicator
gasLowGreen - Low Gas Green Indicator
gasLowRed - Low Gas Red Indicator
warmteHighGreen - High Warmte Green Indicator
warmteHighRed - High Warmte Red Indicator
warmteLowGreen - Low Warmte Green Indicator
warmteLowRed - Low Warmte Red Indicator
netbeheerkostenLowGreen - Low Netbeheerkosten Green
netbeheerkostenLowRed - Low Netbeheerkosten Red
netbeheerkostenHighGreen - High Netbeheerkosten Green
netbeheerkostenHighRed - High Netbeheerkosten Red
belastingenHighGreen - High Belastingen Green
belastingenHighRed - High Belastingen Red
belastingenLowGreen - Low Belastingen Green
belastingenLowRed - Low Belastingen Red
terugleveringLowGreen - Low Teruglevering Green
terugleveringLowRed - Low Teruglevering Red
terugleveringHighGreen - High Teruglevering Green
terugleveringHighRed - High Teruglevering Red
barElectric2023LowFill - Electric Bar 2023 Low
barElectric2035LowFill - Electric Bar 2035 Low
barElectric2023HighFill - Electric Bar 2023 High
barElectric2035HighFill - Electric Bar 2035 High
barGas2023LowFill - Gas Bar 2023 Low
barGas2035LowFill - Gas Bar 2035 Low
barGas2023HighFill - Gas Bar 2023 High
barGas2035HighFill - Gas Bar 2035 High
barWarmte2023LowFill - Warmte Bar 2023 Low
barWarmte2035LowFill - Warmte Bar 2035 Low
barWarmte2023HighFill - Warmte Bar 2023 High
barWarmte2035HighFill - Warmte Bar 2035 High
barNetbeheerkosten2023LowFill - Netbeheerkosten Bar 2023 Low
barNetbeheerkosten2035LowFill - Netbeheerkosten Bar 2035 Low
barNetbeheerkosten2023HighFill - Netbeheerkosten Bar 2023 High
barNetbeheerkosten2035HighFill - Netbeheerkosten Bar 2035 High
barBelastingen2023LowFill - Belastingen Bar 2023 Low
barBelastingen2035LowFill - Belastingen Bar 2035 Low
barBelastingen2023HighFill - Belastingen Bar 2023 High
barBelastingen2035HighFill - Belastingen Bar 2035 High
barTeruglevering2023LowFill - Teruglevering Bar 2023 Low
barTeruglevering2035LowFill - Teruglevering Bar 2035 Low
barTeruglevering2023HighFill - Teruglevering Bar 2023 High
barTeruglevering2035HighFill - Teruglevering Bar 2035 High

