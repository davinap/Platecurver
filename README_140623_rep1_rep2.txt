This folder contains platereader data for plotting the growthcurves for strains expressing sfGFP under the control of tool-selected promoters. There are two biological replicates (rep1 and rep2) in the same plate.

layout.csv
In the '...layout.csv' file, the two replicates are labelled '1' or '2' after the sample name and media condition.
Annotations:
ypd1/2 = ypd replicate 1/2
ypdx1/2 = ypd 10% glucose replicate 1/2
sm1/2 = ynb replicate 1/2
yepg1/2 = yepg replicate 1/2
ks2 = pFOX2
ks3 = pHCS1
ks4 = pHHT1
ks5 = pTDH2
ks6 = pCDC19
ks7 = pRPL28

rep1/2_plots folder:
Contain the growthcurves plotted from the platecurver script. 'raw' files show the growth curves with blank-corrected OD600 values. 'pc'files show growth curves that were plotted after using blank-corrected values and fitting them to a sigmoid curve using the growthcurver pacakge in the script. 



