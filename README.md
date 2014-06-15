IOS Boilerplate
===============

Boilerplate for IOS universal apps that contains:

- **Workspace** that contain a target project (boilerplate) and Pods project.
- **Single View application template**.
- **Core Data Model Editor** http://goo.gl/fLGlE8
- **Folder structure** following http://akosma.com/2009/07/28/code-organization-in-xcode-projects/
- **Gitignore** base in https://gist.github.com/mmorey/6931793
- **CocoaPods** for dependencies projects that include:
  - **ObjectiveRecord**: to managing Core Data objects https://github.com/supermarin/ObjectiveRecord 
  - **BRCocoaLumberjack**: logging framework https://github.com/CocoaLumberjack/CocoaLumberjack
  - **AFNetworking**: networking library https://github.com/AFNetworking/AFNetworking
  - **Kiwi**: Behavior Driven Development library https://github.com/kiwi-bdd/Kiwi
  - **Unit Test Target Configuration** following kiwi documentation https://github.com/kiwi-bdd/Kiwi/wiki/Getting-Started-with-Kiwi-2.0

### Installation:

Clone the repository:

    $ git clone https://github.com/adrianortuzar/boilerplate_ios.git

Install cocoapods http://cocoapods.org/

    $ cd boilerplate_ios
    $ pod install
