# CMPG-323-Overview--28331869
Detailed module plan to follow throughout the semester , so that I know what is expected from me for each submission and how long each requirement should take me to complete it.

## Branching Strategies

Branching stategy that will be used for Project 1 and 3 is GitHub Flow , as it focuses on agile principles and it is a fast and streamlined branching strategy with very short production cycles and frequent releases. Additionally this strategy allows for fast feedback loops, enabling teams to rapidly identify issues and resolve them. Since there is no development branch as one is testing an d automating changes to one branch which allows for quick and contionuos deployment. This strategy is suitable for small teams and ideal when needing to maintain a single production version.


Branching stategy for Project 2, 4 and 5 is the Featuring branching strategy as the team can choose to exclude or delay a feature completely from a particular release if it is not ready yet or dependent on other components not ready. Developers can work on their own features in isolation from changes happening elsewhere. They can pull in changes from the master branch at certain intervals if they need to incorporate those changes in their work or to simply make the future integration less painful. When the feature is ready and tested, it can be integrated with the master branch. Giving the team an opportunity to review and commment on the proposed changes.  The “pull request” or “merge request” process is way more of an advantage than using direct commits on the master branch.


## Project and Repository Structure
structure looks like  ...see diagram below


## Repositories 

 CMPG 323 Project 1- <28331869> : https://github.com/users/MecayllaBeukes/projects/3
 
 
 CMPG 323 Project 2 -<28331869> : https://github.com/MecayllaBeukes/cmpg-323-Project-2---28331869
 
 
 CMPG 323 Project 3 -<28331869> : https://github.com/MecayllaBeukes/CMPG-323-PROJECT-3---28331869-
 
 
 CMPG 323 Project 4 -<28331869> : https://github.com/MecayllaBeukes/CMPG-323-Project4---28331869-
 
 
 CMPG 323 Project 5 -<28331869> : https://github.com/MecayllaBeukes/CMPG-323-Project-5--28331869-


## Use of .gitgnore File

A .gitignore file is a plain text file where each line contains a pattern for files/directories to ignore. It is placed in the root folder of the repository or it can be stored in another file and multiple .gitignore files ar allowed. The patterns in the files are relative to the location of that .gitignore file.

## Credentials And Sensitive Information

 Credentials and sensitive information should never be stored on GitHub as the purpose of GitHub is to host code repositories.Past the consents you set for you, there could be no other technique for security that will guarantee that your secret keys, private credentials, and sensitive information reamin inside a controlled and secured environment.
 
 Storing sensitive credentials for projects will be done as mentioned below :

 1. I’ll utilize a .JSON file for project 2 and 3 API Development and Standards & Patterns.
    
 2.  In Project4 Testing & RPA, credentials will be stored in UiPath Orchestrator.
    
 3. In Project5 Reporting, there will not be credentials that need to be stored.


## References
https://www.googlecloudcommunity.com/gc/Cloud-Product-Articles/Source-Control-for-API-Proxy-Development/ta-p/75620#:~:text=Branching%20Strategy,all%20the%20way%20to%20production.


1. https://www.pluralsight.com/guides/how-to-use-gitignore-file


2. https://spectralops.io/resources/how-to-choose-a-secret-scanning-solution-to-protect-credentials-in-your-code/

3. https://github.com/users/JacquiM/projects/16

4. Nick Chapsas. (2021, Aug 10). Getting started with branching workflows, Git Flow and GitHub Flow. [Video]. YouTube. https://youtu.be/gW6dFpTMk8s

5. Galaxy Technologies. (2020, Oct 6).Branching Strategies on Git | Real-time Git Branching Strategy for a DevOps project. [Video]. YouTube https://youtu.be/Bg8tiOLZw4A

6. Adam Marczak. (2020, Oct 21). AZ-900 Episode 27 | Azure Key Vault | Secret, Key and Certificate Management. [Video]. YouTube https://youtu.be/AA3yYg9Zq9w

7. Devchild. (2018, Sept 2). The gitflow workflow - in less than 5 mins. [Video]. YouTube https://youtu.be/1SXpE08hvGs

