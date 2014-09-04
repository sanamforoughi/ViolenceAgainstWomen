ViolenceAgainstWomenAndChildren
===============================
Project by Nicholas Neuteufel while working for Tremendous Hearts (Cape Town, South Africa)


Written in R language, using UN Women data: http://www.endvawnow.org/uploads/browser/files/vawprevalence_matrix_june2013.pdf

STEP 1: Mapping Out Violence (see Mapping) -- COMPLETE 

http://imgur.com/H0W1OoO

*****


STEP 2: The "Missing" Statistics--trying to predict missing data

A) Experimentally -- COMPLETE-ish 

a) Random Forests (RF) -- complete (see ExperimentingDataImputation)


B) Empirically -- NEXT STEP

a) Using older data from WDI to fill-in incomplete cases (NAs)

b) Comparing empirical data to RF predicted imputation


C) Overall

a) Try to get war/polity scores working. Then re-run both imputations.

b) Region analysis (Statistically analyzing trends by continent and regions within continents)

*****

STEP 3: Predicting key countries with missing data (with both 95% confidence and prediction intervals)

No particular order:

a) Asia: China, Koreas, Saudi Arabia, Iraq, Iran, Pakistan, Indonesia.

b) Latin America: Argentina.

c) Africa: South Africa, Libya.

d) Europe: Spain, France.

e) North America: Cuba.

*****

STEP 4: Mapping the world; project evaluation.
