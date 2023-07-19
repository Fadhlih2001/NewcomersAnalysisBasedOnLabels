# HOW TO RUN

### Requirements
1. `python 3`
2. `jupyter notebook`

### Procedure:
1. Clone this repository into your userhome folder in the system :
   ```
   git clone https://github.com/Fadhlih2001/NewcomersAnalysisBasedOnLabels.git
   ```
   output: `/Users/<yourusername>/NewcomersAnalysisBasedOnLabels/`
2. Put a dataset example `aws_aws-cdk_close.json` into a project directory example `AWS-CDK` then `Take Newcomers and Experts data`  directory. 
4. Run `jupyter notebook`.
5. In the `jupyter notebook`, open the directory `Code` then project directory example `AWS-CDK`. Next, open `Take Newcomers and Experts data` directory.
6. In  `Take Newcomers and Experts data` directory, run the code  until you "List_of_Labels_No_Duplication.csv" with format CSV.
7. After you get "List_of_Labels_No_Duplication.csv", use it and clasify it to 5 category Unrelated, Expert Labels, Newcomers Labels, Critical, Non Critical. (How to Clasify: Read every issue based label and determined which on 5 category with true and false)
8. After classify it, save it (I named it "labels-fadhlih - Sheet1 new.csv") with CSV format and put it back to code.
9. Run it until finished. You will get for Newcomers data that is "data_title_newcomers.csv" and "data_body_newcomers.csv", for Expert data that is "data_title_experts.csv" and "data_body_experts.csv", for Combined (Newcomers and Experts) data that is "data_title_expert_newcomers_combined.csv" and "data_body_expert_newcomers_combined.csv".
10. After that, Change Newcomers, Experts and Combined data from CSV Format to TXT format using code that is from `Tools for change CSV to TXT with delimiter` directory.
11. Put Newcomers, Experts and combined data that is already TXT format to `Document Clustering` directory.
12. Then run Newcomers_Clustering.ipynb to know result of LDA of Newcomers data.
13. Then run Experts_Clustering.ipynb to know result of LDA of Experts data.
14. Then run Combined_Clustering.ipynb to know result of LDA of Combined data.
15. Repeat step 2 until 14 with a different project.
