<center> ![alt text](img/sysofcog.png) </center>


asdsak


# Selective Influence

# Mean Interaction Contrast (MIC)

# Survivor Interaction Contrast (SIC)

# D` Statistic
The  D statistic is a non-parametric test for assessing the empirical SIC(t)'s departure from zero (Houpt & Townsend, 2010). The D statistic is calculated for both the maximum and minimum points of the empirical SIC(t), giving a D+ and D- statistic. 

The D statistic utilises comparison of the SIC(t) to the maximum and minimum value of a Brownian Bridge, a stochastic process occurring over time with pdf drawn from the conditional probability of a Wiener process with start (t=0) and end points (t=T) anchored at zero and uncertainty greatest in the middle of the distribution. As such, interpretation of the D statistic should be understood as D+ denoting the largest positive value of a Brownian Bridge and D- the magnitude of the smallest value. 

Given the D statistic's calculation from a Brownian Bridge, a null hypothesis test can be ascertained with the null assuming the maximum SIC(t) positive and negative inflection resulting from the uncertainty of the underlying Brownian Bridge. 

The D statistic should be interpreted in conjunction with the MIC, as the presence of a D statistic alone is only weak evidence against the null (Houpt & Townsend, 2010).

## D-Hat vs MIC Significance Testing
_____________________________________________________________________
<font size=5 color=dodgerblue><b> Parallel Exhaustive </font></b>
<center> ![alt text](img/Architectures_SI_PE.tif) </center>
<footer><font size=2> Figure </footer></font> 

<font size=4 color=dodgerblue><b> Theoretical Expectations </font></b>

Measure         | Expect Significance | Description
:-------        |:----------:| :----------
MIC (mean)      |        | MIC should be negative
MIC Interaction |  True    | MIC Interaction should be significant. Hallmark of Parallel Processing
D+              |  False   | No significant positive deviation should be observed. See above SIC figure.
D-              |  True    | A significant negative deviation should be observed.

<font size=4 color=dodgerblue><b> Simulated Observations - Dhat vs MIC </font></b>

<center> ![alt text](img/IntersectedDensityPlots/Parallel_Exhaustive_Dpval_vs_MICpval_50_Trials.jpg) </center>
<center> ![alt text](img/IntersectedDensityPlots/Parallel_Exhaustive_Dpval_vs_MICpval_100_Trials.jpg) </center>
<center> ![alt text](img/IntersectedDensityPlots/Parallel_Exhaustive_Dpval_vs_MICpval_200_Trials.jpg) </center>
<center> ![alt text](img/IntersectedDensityPlots/Parallel_Exhaustive_Dpval_vs_MICpval_1000_Trials.jpg) </center>

<font size=4 color=dodgerblue><b> Simulated Observations - Corresponding SICs </font></b>

<center> ![alt text](img/SICdensity/Parallel_Exhaustive_SIC_50_Trials.tif) </center>
<center> ![alt text](img/SICdensity/Parallel_Exhaustive_SIC_100_Trials.tif) </center>
<center> ![alt text](img/SICdensity/Parallel_Exhaustive_SIC_200_Trials.tif) </center>
<center> ![alt text](img/SICdensity/Parallel_Exhaustive_SIC_1000_Trials.tif) </center>



_____________________________________________________________________
<font size=5 color=dodgerblue><b> Parallel Self Terminating </font></b>
<center> ![alt text](img/Architectures_SI_PST.tif) </center>
<footer><font size=2> Figure </footer></font> 

<font size=4 color=dodgerblue><b> Theoretical Expectations </font></b>

Measure         | Expect Significance | Description
:-------        |:----------:| :----------
MIC (mean)      |        | MIC should be positive
MIC Interaction |  True    | MIC Interaction should be significant. Hallmark of Parallel Processing
D+              |  True   | A significant positive deviation should be observed. See above SIC figure.
D-              |  False    | No significant negative deviation should be observed.

<font size=4 color=dodgerblue><b> Simulated Observations - Dhat vs MIC </font></b>


<center> ![alt text](img/IntersectedDensityPlots/Parallel_Self_Terminating_Dpval_vs_MICpval_50_Trials.jpg) </center>
<center> ![alt text](img/IntersectedDensityPlots/Parallel_Self_Terminating_Dpval_vs_MICpval_100_Trials.jpg) </center>
<center> ![alt text](img/IntersectedDensityPlots/Parallel_Self_Terminating_Dpval_vs_MICpval_200_Trials.jpg) </center>
<center> ![alt text](img/IntersectedDensityPlots/Parallel_Self_Terminating_Dpval_vs_MICpval_1000_Trials.jpg) </center>

<font size=4 color=dodgerblue><b> Simulated Observations - Corresponding SICs </font></b>

<center> ![alt text](img/SICdensity/Parallel_Self_Terminating_SIC_50_Trials.tif) </center>
<center> ![alt text](img/SICdensity/Parallel_Self_Terminating_SIC_100_Trials.tif) </center>
<center> ![alt text](img/SICdensity/Parallel_Self_Terminating_SIC_200_Trials.tif) </center>
<center> ![alt text](img/SICdensity/Parallel_Self_Terminating_SIC_1000_Trials.tif) </center>

_____________________________________________________________________
<font size=5 color=dodgerblue><b> Serial Exhaustive </font></b>
<center> ![alt text](img/Architectures_SI_SE.tif) </center>
<footer><font size=2> Figure </footer></font> 

<font size=4 color=dodgerblue><b> Theoretical Expectations </font></b>

Measure         | Expect Significance | Description
:-------        |:----------:| :----------
MIC (mean)      |        | MIC should be equal to zero
MIC Interaction |  False    | MIC Interaction should not be significant.
D+              |  True   | A significant positive deviation should be observed. See above SIC figure.
D-              |  True    | A significant negative deviation should be observed.

<font size=4 color=dodgerblue><b> Simulated Observations - Dhat vs MIC </font></b>


<center> ![alt text](img/IntersectedDensityPlots/Serial_Exhaustive_Dpval_vs_MICpval_50_Trials.jpg) </center>
<center> ![alt text](img/IntersectedDensityPlots/Serial_Exhaustive_Dpval_vs_MICpval_100_Trials.jpg) </center>
<center> ![alt text](img/IntersectedDensityPlots/Serial_Exhaustive_Dpval_vs_MICpval_200_Trials.jpg) </center>
<center> ![alt text](img/IntersectedDensityPlots/Serial_Exhaustive_Dpval_vs_MICpval_1000_Trials.jpg) </center>

<font size=4 color=dodgerblue><b> Simulated Observations - Corresponding SICs </font></b>

<center> ![alt text](img/SICdensity/Serial_Exhaustive_SIC_50_Trials.tif) </center>
<center> ![alt text](img/SICdensity/Serial_Exhaustive_SIC_100_Trials.tif) </center>
<center> ![alt text](img/SICdensity/Serial_Exhaustive_SIC_200_Trials.tif) </center>
<center> ![alt text](img/SICdensity/Serial_Exhaustive_SIC_1000_Trials.tif) </center>
_____________________________________________________________________
<font size=5 color=dodgerblue><b> Serial Self Terminating </font></b>
<center> ![alt text](img/Architectures_SI_SST.tif) </center>
<footer><font size=2> Figure </footer></font> 

<font size=4 color=dodgerblue><b> Theoretical Expectations </font></b>

Measure         | Expect Significance | Description
:-------        |:----------:| :----------
MIC (mean)      |        | MIC should be equal to zero
MIC Interaction |  False    | MIC Interaction should not be significant.
D+              |  False   | No significant positive deviation should be observed. 
D-              |  False    | No significant negative deviation should be observed. See above SIC figure.

<font size=4 color=dodgerblue><b> Simulated Observations - Dhat vs MIC </font></b>


<center> ![alt text](img/IntersectedDensityPlots/Serial_Self_Terminating_Dpval_vs_MICpval_50_Trials.jpg) </center>
<center> ![alt text](img/IntersectedDensityPlots/Serial_Self_Terminating_Dpval_vs_MICpval_100_Trials.jpg) </center>
<center> ![alt text](img/IntersectedDensityPlots/Serial_Self_Terminating_Dpval_vs_MICpval_200_Trials.jpg) </center>
<center> ![alt text](img/IntersectedDensityPlots/Serial_Self_Terminating_Dpval_vs_MICpval_1000_Trials.jpg) </center>

<font size=4 color=dodgerblue><b> Simulated Observations - Corresponding SICs </font></b>

<center> ![alt text](img/SICdensity/Serial_Self_Terminating_SIC_50_Trials.tif) </center>
<center> ![alt text](img/SICdensity/Serial_Self_Terminating_SIC_100_Trials.tif) </center>
<center> ![alt text](img/SICdensity/Serial_Self_Terminating_SIC_200_Trials.tif) </center>
<center> ![alt text](img/SICdensity/Serial_Self_Terminating_SIC_1000_Trials.tif) </center>

