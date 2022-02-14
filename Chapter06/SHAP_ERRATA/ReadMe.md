## Please Check - SHAP ERRATA

Although, I really liked the idea of the SHAP algorithm, but unfortunately the SHAP Python framework has alot of issues, especially with the latest version.

There are many pending pull requests which the project owners would need to review and approve and it was sad for me to see that the project owners are not actively taking care of the project.
If you run across any issue, please check the open issues for SHAP first at: https://github.com/slundberg/shap/issues
Currently, when I am writing this book, there are more than 1.3K open issues and close to 100 unreviewed pull requests.

I myself, have come across few issues which running the framework and had to dig deep into the code of the framework, and make necessary changes to remove the error. Although the errors are quite trivial, but it is difficult for novice learners to identify and fix these by themselves. So, I am including the SHAP ERRATA section to resolve the known issues encountered by me, during the writing process.

My suggestion and sincere request for you, is to similar take the files, where the error is spotted and copy paste with the files having the necessary corrections, which I have added in the SHAP ERRATA section.
The exact steps have been mentioned here:
1. Check the location where the SHAP framework is installed for you. You can try the following lines of code:
`import shap`
`shap.__file__`
2. Once you detect the `shap` root folder, replace `_explanation.py` present with the `_explanation.py` provided in the SHAP_ERRATA folder of this reporsitory. 
This will help to solve an issue observed with shap barplots.
GitHub Issue - https://github.com/slundberg/shap/issues/2325
3. To solve the issue observed with Waterfall plots, please navigate to the shap root folder and then navigative to the plots folder and replace `_waterfall.py` with `plots/_waterfall.py` file provided in the SHAP_ERRATA folder of this repository.
GitHub Issue - https://github.com/slundberg/shap/pull/2342

**Please note** - The issues are observed with the Shap framework of `0.40.0` which is the version that I am using. These issues can be rectified in future versions, or even new issues can come for which my solutions might not work. So, please apply the corrections only when you encounter an error. If my solutions doesn't help, please open an issue for this project and accordingly I can try providing the solution. Apologies if this affects your learning experience. 