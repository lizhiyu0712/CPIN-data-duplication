"Group1-5040 final project.docx" is the final report
"Group1-5040 final project.pptx" is the final presentation 

"Code" file contains all the files of the code to do the matching
	"Dedupe" file is the file to make the matching and create the golden table
		"Dedupe.ipynb" is the main code for ER method
		"Duplicates.xlsx" is the original duplicates record
		"final table.csv" is the golden table with the confidence and cluster id labeled
		"Main Records.xlsx.csv" is the original main record

	"Supervised learning" file is the file to do the supervised learning task
		"Golden table with the threshold" file is the file using the threshold 0.6
			Run "final table 0.6 threshold.ipynb" first to take the threshold
			Next run "Label Main.ipynb" to label the main records
			Next run "Label Duplicate.ipynb" to label the duplicate records
			Lastly, run "Build Model.ipynb" to build the supervised learning model and evaluate its performance 
		"Golden table without the threshold" is the file without using the threshold
			The processes will be similar to the one above

	"Unsupervised learning" is the file to do the clustering task
		"Unsupervised learning-Clustering.ipynb" is the code for the clustering