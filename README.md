# **BlakePods** Podspecs
## Private CocoaPod Podspec Repo


## Add this repository to CocoaPods.
 * To make use of this PodSpec repo, from the terminal, run: `pod repo add blakepods https://github.com/BlakeBarrett/Podspecs.git`   
 * Next add `source "https://github.com/BlakeBarrett/Podspecs.git"` to the podspec of your consuming project.

## Adding a private pod
 * To push a pod to this repo, make sure you have created your new podspec `pod repo init MY_POD_NAME`.
 * When you are ready to push it, from the terminal, run: `pod repo push blakepods PODSPEC` (where `PODSPEC` is the path to your `.podspec` file)

## Using a private pod
 * Make sure your project is already using cocoapods. 
 * Add this repo as a "source" in the .podfile (see Section 1)
 * Add the private pod to your list of dependencies the way you normally would. CocoaPods will search through all associated source repos for your pod.  

### External Docs/References
 * Getting started wth CocoaPods: https://guides.cocoapods.org/using/getting-started.html
 * Integrating CocoaPods with a project: https://guides.cocoapods.org/using/using-cocoapods.html
 * Creating your own CocoaPod: https://guides.cocoapods.org/making/using-pod-lib-create.html
 * Creating a private podspec repo: https://guides.cocoapods.org/making/private-cocoapods.html
 