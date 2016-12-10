<h1>Alexa skill - FleetBriefing v1.0</h1>
This skill speaks some top KPIs for a fictitous car rental company. The skill also dispays additional information, a card, when activated from FireTV. Launch the skill with "Alexa, open Fleet Briefing." No login or account linking is needed for this POC skill.

<h2>Source Files</h2>
<b>IntentSchema.json</b><br>
This schema defines the intents and word formats for which our skill will listen. This code needs to be entered into the skill configuration on the Alexa page of your Amazon Developer Account.
<br>

<b>FleetBriefing.py</b><br>
This is the Python source code for the Lambda function that powers the skill.
<br>

<b>SampleUtterances.txt</b><br>
This code needs to be entered into the skill configuration on the Alexa page of your Amazon Developer Account.

<b>IntentSchema.json</b><br>
This json needs to be entered into the skill configuration on the Alexa page of your Amazon Developer Account.

<p>
<b>KPIs for the Rental Car Industry</b><br>
<ul>
<li>RPD<br>
Rental Paid.<p>

<li>Utilization<br>
Average percentage of utilization of a vehicles in the fleet. Uilization calculated based on 365 days in a year, 350 available rental days assumed (15 days of service, maintenance etc) and 1 day to turn around car between rentals).<p> 

<li>Total Fleet Utilization</li>
Percentage of the fleet that is in use during a given time period (for example the current quarter).<p>

<li>Rental Locations<br>
Rental locations, typically airports or train stations<p>

<li>Rental Type<br>
Business or liesure -- with the trend to more liesure rentals which, in general, are longer in dureation and thus drive up overall fleet utilization. Liesure rentals account for appoximately 53% of all rentals in 2016.

