IOS Boilerplate
===============

Boilerplate for IOS universal apps that contains:

- **Workspace** that contain a target project (boilerplate) and Pods project.
- **Single View application template**.
- **Core Data Model Editor** http://goo.gl/fLGlE8
- **Folder structure** following http://akosma.com/2009/07/28/code-organization-in-xcode-projects/
- **Gitignore** base in https://gist.github.com/mmorey/6931793
- **Podfile** with some libraries that I recommend:
  - **ObjectiveRecord**: to managing Core Data objects https://github.com/supermarin/ObjectiveRecord 
  - **BRCocoaLumberjack**: logging framework https://github.com/CocoaLumberjack/CocoaLumberjack
  - **AFNetworking**: networking library https://github.com/AFNetworking/AFNetworking
  - **Kiwi**: Behavior Driven Development library https://github.com/kiwi-bdd/Kiwi
  - **Unit Test Target Configuration** following kiwi documentation https://github.com/kiwi-bdd/Kiwi/wiki/Getting-Started-with-Kiwi-2.0

### Installation:

**Rename the project**

Start your new project with the correct name.

Follow the instruction in the wiki.
https://github.com/adrianortuzar/boilerplate-ios/wiki/How-to-change-the-project-name

**Clone the repository**:

    $ git clone https://github.com/adrianortuzar/boilerplate_ios.git

**Install cocoapods**: http://cocoapods.org/

*You can run the project without install cocoapods.*

*Before installing CocoaPods I recommend you to check all the libraries and framework in the Podfile. Remove the pods that you do not think you are going to use.*

    $ cd boilerplate_ios
    $ pod install

### Licence

**Copy Paste Licence**. Fell free, enjoy this project, and if you have time improve it.
