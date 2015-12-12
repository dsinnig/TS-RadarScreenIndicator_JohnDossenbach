Hey John, 

I successfully used the Multi-TimeFrame Engine to convert the Knoxville divergence indicator to show multiple timeframes at the same time. 

I have enclosed two files: 

(1) An Easy language project (for import) that contains two new indicators: 
Knoxville Divergence 1.31: An "engine" indicator that detects Knoxville Divergence for a given timeframe in RadarScreen and writes it to the global dictionary
KnoxvilleDivergenceMTReader: A "getter" indicator which reads out the various divergence readings from the global dictionary and displays it on Radarscreen. 
(2) A sample workspace which shows the required setup for the "engine" and "getter" indicators. 
The below screen shot shows the sample workspace. The Radarscreen window on the upper left hand side shows the KnoxvilleDivergenceMTReader indicator applied to four symbols. For now I have configured it for: 1M, 5M, 10M, 15M, 30M, 1H, 2H, 4H, 1D. It is easy to extend it to other timesframes as well.
The lower RadarScreen window shows the "engine" indicators. In order to make it work, the Knoxville Divergence 1.31 indicator must be applied to any desired timeframe. 
The chart window on the right shows that a bullish Knoxville Divergence for AUD/NZD (1min) was detected for 4 bars ago. As you can see - this number is also shown in the respective engine and getter indicators. 

Inline image 1


Let me know if you can get it to work on your side!

On a different note, a few emails ago you asked me for my pricing model. Here is my take on it. I do not write TradeStation code for a living - I do it out of interest and to learn more about trading - which I would like to do for a living at some point. My key interest is in forming a mutually beneficial partnership. 

I therefore would suggest that you decide on a compensation that would allow us to continue collaborating (e.g., implementing the Ichi cloud strategy that you proposed in a previous mail). 

Cheers, 