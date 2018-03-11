To create a training file for SVM^Rank, do this:
java -jar create_training.jar "training_folder" "the_numer_of_negative_instance_per_bug_report" "a list of features"
For example, java -jar create_training.jar trining_folder 200 "1 2 3 4 5 6"