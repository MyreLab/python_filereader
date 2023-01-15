# python_filereader

Context: My team and I are responsible for the data management and analysis of hundreds of mortality data files received from the Chief Medical Examiner's Office on a monthly basis. A solution was needed to continually rename incoming files with required information, including a case identifier number unique to each mortality case.

Methods: This Python script uses OS, Pandas, and PyPDF2 to read unique case identifiers from each file. The identifiers are temporarily stored in a data frame. The information then populates each file name, and data manipulation is done to rename files with their respective case year and date received. The files are batch-renamed in-place.

The template attached does not contain any personal identifying information.
