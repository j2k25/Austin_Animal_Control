# Austin_Animal_Control
Data Science Project Predicting Survival of Lost Dogs in Austin, TX

COSC 3337 - Data Science
Group 10: Alex, Jarrod, Thomas & Jerry

Our dataset is the Austin Animal Center Shelter Intakes and Outcomes by Aaron Schlegel on kaggle.com and contains about 80,000 shelter animal intakes and their resulting outcomes (https://www.kaggle.com/aaronschlegel/austin-animal-center-shelter-intakes-and-outcomes?select=aac_intakes_outcomes.csv).

The Austin Animal Center is the largest no-kill animal shelter in the United States that provides care and shelter to over 18,000 animals each year. As part of the AAC's efforts to help and care for animals in need, the organization makes available its accumulated data and statistics as part of the city of Austin's Open Data Initiative (https://data.austintexas.gov/).

This dataset is a merging of two other datasets, aptly named:

Austin Animal Center Intakes (https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Intakes/wter-evkm) and

Austin Animal Center Outcomes (https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Outcomes/9t4d-g238)

According to the author of the dataset, who copied from the original Outcomes dataset, the outcome type descriptions are as follows:

Outcome Types:

Adoption: the animal was adopted to a home

Barn Adoption: the animal was adopted to live in a barn

Offsite Missing: the animal went missing for unknown reasons at an offsite partner location

In-Foster Missing: the animal is missing after being placed in a foster home

In-Kennel Missing: the animal is missing after being transferred to a kennel facility

Possible Theft: Although not confirmed, the animal went missing as a result of theft from the facility

Barn Transfer: The animal was transferred to a facility for adoption into a barn environment

SNR: SNR refers to the city of Austin's Shelter-Neuter-Release program. I believe the outcome is representative of the     animal being released.

Because this list provided did not cover all of the outcome types, users on the site asked for further clarification on the terms used in the dataset. The author commented to the users with the following:

Disposal: I'm not too sure about this one; my guess is the animal died while in the shelter and its body was disposed       of.

Missing: The animal went missing from the shelter for unknown reasons and has not been located.

Relocation: The animal was transferred to a different location (usually the associated outcome subtype will have more       information as to what facility the animal was moved.

Rto-Adopt: Also not sure on this one, but I believe it represents the animal was returned to its owner through the shelter's adoption process.

(Schlegel): "I apologize, I am not familiar with the Aggressive Behavior, Court/Investigation, Medical and Underage subtypes. Here are the definitions for the remaining subtypes:"

Outcome Subtypes

In Kennel: The animal was transferred to a kennel

SCRP: Stray Cat Return Program. The cat was likely moved to be placed with that program rather than the shelter, though I am unable to say for sure.
(http://www.maddiesfund.org/austin-animal-services-stray-cat-return-program.htm)

SNR: Shelter, neuter, return. A variant of TNR (trap, neuter, release). More information can be found at Maddie's Fund.
(http://chewonthis.maddiesfund.org/2013/08/tnr-vs-snr-whats-the-difference/)

Intake Condition:

Feral: The animal was taken to the shelter as a feral (fearful and possibly aggressive to people)

Euthanasia Request: The animal was brought to the shelter to be euthanatized for unknown reasons.

Public Assist: I am also not sure about this one; my guess is the animal was brought in through an outside rescue organization.

We are only interested in the data from dogs as the dataset also contains several entries of non-adoption animals such as bats, skunks, and raccons.
