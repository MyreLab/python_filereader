# Python File Reader

*Background*: My team and I are responsible for the data analysis and management of hundreds of mortality data files received from the Chief Medical Examiner's Office on a monthly basis. A solution was needed to continually rename incoming files with required information, including a case identifier number unique to each mortality case.

*Solution*: This Python script uses OS, Pandas, and PyPDF2 to read unique case identifiers from each file. The identifiers are temporarily stored in a data frame. The information then populates each file name, and data manipulation is done to rename files with their respective case year and date received. The files are batch-renamed in-place.
