# Description of qual_SE_16-18

This is a file with 35 variables and 258 observations.  It is the data from the Western Wheat Quality lab for the Soft Elite nursery entries from my breeding program in 2019.  The quality data is compiled from tests run from 2016-2018 when they lines were moving through the breeding program.  The data is unbalanced, and the samples were grown at multiple locations.  There are check cultivars in the file.  The check cultivars are everthing that had a name and is not a numbered line.  I have removed outliers from the data more or less.

###Here is a description of the variables:

###Descriptive traits

Nursco: quality lab coding for each of the nurseries that they run (neutral)

Nurname: The name that the breeder assigned to the experiment (neutral)

Sample: quality lab sample number (neutral)

Entry: The entry number assigned to the breeding line in a given location-year.  These are not unique (neutral)

Class:  the class of wheat for marketing purposes

NameT:  similar to name but names are trimmed and all formatted the same use this as the line designator.(neutral)

Pedigree:  the breeding line pedigree (neutral)

Location: location in which samples were grown

Locode: the code given to the location and experiment in our program (neutral)

Year1:  year that the selections were made (neutral)

Year0: year in which plots were grown and quality samples obtained (neutral)

###Micromill physical traits - used in early generations

MMbran: the weight of bran derived from micromilling.  (Lower)

MMflour:  the weight of breakflour derived from micromilling (higher)

MMmids:  the weight of other flour derived from micromilling (higher in combination with higher MMflour)

###Solvent traits - used in early generations

Microsd:  Microsedimentation.  Measures gluten strength (lower for club wheat)

FSDS: Flour sedimentation.  Sould be similar to micro sedimentation. Run on larger sample. Measures gluten strength (lower for club wheat)

FSR-C: Sodium Carbonate flour solvent retention capacity.  Measure of damaged starch (lower for club wheat)

FSR-L: Lactic acid flour solvent retention capacity.  Measure of gluten strength (lower for club wheat)

FSR-W: Water flour solvent retention capacity.  Measure of absorption (lower for club wheat)

FSR-S: Sucrose flour solvent retention capacity.  Measure of pentosans (lower for club wheat)

LDOPA: The LDopa test measures polyphenol oxidase which is a measure of the tendency for a batter to brown (lower)

### Kernel traits - used in early generations

TWT:  test weight of sample. (Higher)

SKHRD:  the texture of the sample based on the single kernel characterization system (Lower for club)

Skhrdsd: the standard deviation of the sample for SKHRD (lower)

SKWT:  The weight of a kernels as measured on the single kernel characterization system (higher)

SKWTSD: the standard deviation of the sample for SKWT (lower)

SKSIZE:  the width of the kernels as measured on the single kernel characterization system (higher for club)

SKSIZESD: the standard deviation of the sample for SKWT (lower)

FPROT: the flour protein concentration (lower for club)

FASH:  The flour ash derived after burning.  (lower is better for functionality but higher ash may be associated with higher mineral value)

###Milling traits requires more grain - later generations

FYELD: straight grade flour yield as a percentage.  (higher is better)

MSCOR: an index comprised of FYELD and FASH. (higher is better)

BKFYELD:  Break flour yield,  The yield of the first pass of flour.  (higher is better, key trait for club wheat)

###Product traits requires grain and time - later generation

CODI:  The diameter of the test sugar snap cookie. (Higher for soft and club wheat)

CAVOL:  The volume of the test sponge cake (higher - key trait for club wheat)



### Questions:

My main question is to what extent can we use early generation traits to predict the Milling and product traits.

What are the correlations among the traits?  

What are the heritabilities?

How does the variation due to environment differ among the traits?

Are there any pedigrees that perform particularly well or particularly bad?  Any clusters?

What should I select?  A good club wheat has high cake volume, low gluten strength, high test weight, high break flour and high flour yield.  Our stakeholders have asked me to increase kernel size and test weight and reduce LDOPA as well.  Can you make any suggestions for crosses that I might want to make?



