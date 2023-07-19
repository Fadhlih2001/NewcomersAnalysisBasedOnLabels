# Research Artifacts: Newcomers Analysis Based on Labels

https://github.com/Fadhlih2001/NewcomersAnalysisBasedOnLabels

This research for the paper Newcomers Analysis Based on Labels --histogram for Code Changes. This artifact is a repository of (a) Code; code for taking newcomer and expert data from the repository and using it for doing document clustering using Latent Dirichlet Allocation (LDA) so we can analyze it (b) Dataset including (i) 18,212 issues on AWS-CDK repository (ii) 368 issues on SIX repository (iii) 4,649 issues on FLASK Repository (iv) 22165 issues on NUMPY repository 

## Contents

* `Code` - a directory of the code
  *  `AWS-CDK` - a directory of AWS-CDK code
  *  `FLASK` - a directory of FLASK code
  *  `NUMPY` - a directory of NUMPY code
  *  `SIX` - a directory of SIX code
* Every directory contains:
    *   `Document Clustering` - TXT file from `Tools for change CSV to TXT with delimiter` that is used for Document Clustering using LDA and analyzing it
    *   `Take Newcomers and Experts data` - Take all Newcomers and Expert issues from the dataset
    *   `Tools for change CSV to TXT with delimiter` - Change Newcomers and Experts data format to TXT
* For additional `NUMPY` has:
    * `Compare two CSV` - For Comparing CSV the result from Newcomers and Expert issues of Numpy

* `Dataset` - a directory of the dataset
  * `aws_aws-cdk_close.json` - all issues that take from AWS-CDK repository on Github 
  * `benjaminp_six.json` - all issues that take from Six repository on Github 
  * `numpy_numpy.json` - all issues that take from Numpy repository on Github 
  * `pallets_flask.json` - all issues that take from Flask repository on Github 
    
* `README.md` - this file 

## Author
* [Yusuf Sulistyo Nugroho](https://yusufsn.github.io/)
* Raula Gaikovina Kula
* Kenichi Matsumoto

## Related Paper

## MIT License for code
Our Code implementation is licensed under the MIT License.


