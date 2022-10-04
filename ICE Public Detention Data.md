Validating ICE's Public Detention data
Data source:

# About

ICE releases new detention data in an Excel sheet once each two weeks (approximately). TRAC uses this data to update its Quick Facts tools that make this data more legible to the public. Before using the data, TRAC validates the data to ensure that it represents accurate data (or at least plausibly accurate data, since TRAC is not able to validate these summary data using detailed data).

# Preparation

1. Obtain Current ICE Detention Data File

  - Download the Excel file from ICE’s detention data page online: [https://www.ice.gov/detain/detention-management](https://www.ice.gov/detain/detention-management).

2. Open TRAC’s Current Detention Quick Facts Data

  - TRAC’s Current Detention Quick Facts Data is available here: [https://trac.syr.edu/immigration/quickfacts/](https://trac.syr.edu/immigration/quickfacts/).

# Validation Level 1

For Validation Level 1, we need to confirm that ICE's Excel file contains new data. To do this, we compare the dates on ICE's data with the dates on TRAC's Quick Facts tools.

1. Make a note of the date in ICE's Excel file name.
2. Make a note of the date listed in TRAC's Quick Facts.
3. Open the Excel file.
4. Go to the last tab named "Footnotes."
5. Find the date for which data was extracted from the EID.

Using these three dates, you should be able to determine whether the current Excel file includes new data or whether it is identical to previous data. You can confirm this by comparing the underlying numbers in the Excel sheet with the numbers in TRAC's Quick Facts tool.

If the data is new, continue to Validation Level 2. If the data is not new, end the validation process.

# Validation Level 2

For Validation Level 2, we need to confirm that the data in ICE's Excel file is actually complete. To do this, we compare the actual data on ICE's data with the data in TRAC's Quick Facts tools.

We use three touch-points for comparison:
1. Compare the total number of people currently detained in ICE's ATD program in ICE's Excel file and in TRAC's Quick Facts tools.
1. Compare the total number of people enrolled in ICE's ATD program in ICE's Excel file and in TRAC's Quick Facts tools.
1. Compare the total number of people detained at the facility with the highest population in ICE's Excel file and in TRAC's Quick Facts tools.

If the numbers in ICE's Excel sheet differ in a rational way from the numbers in TRAC's Quick Facts tools, the data is likely adequate to put into production; move on to Validation Level 3. If the data are identical (indicating that it is not, in fact, new data) or if the data differ in a way that is illogical (such as doubling or halving within a short time-frame), end the validation process.

# Validation Level 3

For Validation Level 3, we need to update TRAC's validation sheet with four dates, which allows TRAC technology team to process the data with accurate dates.
