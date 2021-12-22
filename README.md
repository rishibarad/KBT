# kya-bolti-tu

## Branches:
main - stable app releases

staging - development branch, merge your feature branches here

## Dependencies:
This project is using cocoapods for managing external libraries and a Gemfile for managing the cocoapods version. You will need to run the following commands in terminal after cloning this repository to your local machine to get the project running inside of Xcode.

Get Bundler
```
sudo gem install bundler
```
To install the specific cocoapods version run
```
bundle install
```
Then install the pods
```
bundle exec pod install
```
## Core Dependencies
Swiftlint - A tool to enforce Swift style and conventions

R.swift - Get strong typed, autocompleted resources like images, fonts and segues in Swift projects

Firebase - A realtime database and backend as a service

## Project structure:
Resources - fonts, strings, images, generated files etc

SupportingFiles - configuration plist files

Models - model objects

Modules - contains app modules (UI + Code)

Helpers - protocols, extension and utility classes
