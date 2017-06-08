# The PERRINN Application Repository
Welcome Internet rider to the PERRINN Mobile Application's repository. The decision has been made to enhance the development by creating a cross-platform application.
## Project's Organisation
The project is organised as a Xamarin PCL "Solution" (like a big bundle of different projects) meaning that it contains a project dedicated to each mobile platform. For now the Windows Phone part has been put aside since the team is concentrating on the Android and iOS platforms. 
Three different projects are contained in the Solution, one for each platform targetted and an additional for the common code, the one that will be shared. The Portable Class Libraries project contains the logic that the views will then use.
If you want more information on Xamarin just go there: [https://developer.xamarin.com].
## Branch Policy
This project has a specific branch policy (or workflow) that allows anyone to better understand what is going on at the moment. It also helps each developers to avoid conflicts. So you MUST comply with these rules (and you will see that it will change your life).
The basic branches are as follows:

* master: this branch will contain only working commits, meaning that the code has been validated for a release.
* hotfix: hotfixes of problems that could come from a master release (involves only minor bug fixes).
* release: will contain the release candidates.
* develop: the main development branch, so commits comming from features development once they are finished, or quick fixes.

Then one has to create a branch for the feature he is working on. And the naming of the branch should be:
VersionName_DeveloperFirstName_FeatureName
The actual version name is chosen by the development team is **AmbitiousArtichoke**, the Developer's firstname helps to know which developer to refer to in case of a problem comming from his commits, obviously the feature name helps to understand what the code is for. Once a feature has reached a usable state the developer can push it to the develop branch.

