# Naming Conventions
Let's keep our repository directory as clear and easy to search as possible for others by sticking to the following naming conventions.

## The commandments of naming
1. All names shall be in lower case with a hypen inbetween each word.
```
vr-surveyor-meta-quest
```
2. Use the following project-platform structure
```
{project-name}-{platform}
e.g: amazing-app-windows
e.g: amazing-app-ios
```
3. Indicate backend, front end and full stack projects
```
For backends: amazing-app-api
For fronends: amazing-app-fe
For full stack: amazing-app-app
```
4. Every project should have a 'main' and 'development' branch, with main being regularly updated with functional and well tested code.
```
      ____.____._____.____.development
___./___________\.main
```
5. Branches for new features must branch off from development and should be preceeded by 'feature-'
```
                       ___.___.___.feature-animated-progress-bar
      ____.____._____./____.development
___./___________\.main
```
6. Branches for bug fixes must branch off from development and should be preceeded by 'fix-'
```
                       ___.___.___.fix-page-not-loading
      ____.____._____./____.development
___./___________\.main
```
