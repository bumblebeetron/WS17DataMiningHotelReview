***Place 'Hotel_Reviews.csv' in the same folder as this notebook.

Dataset is divided into following tables and saved into corresponding .csv files

	Table 1: Hotel Index Table
		Hotel_ID
		Hotel_Address
		Hotel_Name

	Table 2: Reviewer Nationality Table:
		Reviewer_Nationality_ID
		Reviewer_Nationality

	Table 3: Numeric Hotel Reviews Table
		Hotel_ID
		Average_Score
		Total_Number_of_Reviews
		Additional_Number_of_Scoring
		Review_Total_Negative_Word_Counts
		Review_Total_Positive_Word_Counts
		Reviewer_Nationality_ID
		Total_Number_of_Reviews_Reviewer_Has_Given
		Reviewer_Score
		days_since_review
		lat
		lng

	Table 4: Textual Hotel Reviews Table:
		Hotel_ID
		Negative_Review
		Positive_Review
		
	Table 5: Tag Based Hotel Reviews Table:
		Hotel_ID
		Average_Score
		Total_Number_of_Reviews
		Additional_Number_of_Scoring
		Tags

Additional files for ease of access:

	hotel_name_list: Maps Hotel Index to Hotel Name
	hotel_name_dict: Maps Hotel Name to Hotel Index
	
	reviewer_nationality_list: Maps reviewer nationality index to reviewer nationality
	reviewer_nationality_dict: Maps reviewer nationality to reviewer nationality index
	
	These files are created and saved into corresponding .pkl files for ease of access. 
	In order to load them:
		