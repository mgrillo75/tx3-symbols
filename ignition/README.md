# Perspective Faceplate Library - Version 1.0.0

This resource includes a starter pack for pumps, tanks, and valves. It includes a gateway simulator, UDTs, tags, symbols and faceplates. The .zip includes the tags, UDTs and simulator as separate files from the project backup. 

## Installation

### Custom Instructions
How to install:
1. Install the simulator and name it "Perspective Library Simulator"
2. Import the UDTs
3. Import the tags
4. Import the project
5. That should do it!

### Common Instructions

**Project (.zip/.proj)**  
Project backup and restoring from a project backup is referred to as Project Export and Import. Projects are exported individually, and only include project-specific elements visible in the Project Browser in the Ignition Designer. They do not include Gateway resources, like database connections, Tag Providers, Tags, and images. The exported file (.zip or .proj) is used to restore / import a project.

.zip = Ignition 8+
.proj = Ignition 7+

There are two primary ways to export and import a project:

Gateway Webpage - exports and imports the entire project.
Designer -  exports and imports only those resources that are selected.

When you restore / import a project from an exported file in the Gateway Webpage, it will be merged into your existing Gateway.

The import is located in:
Ignition Gateway > Configuration > System > Projects > Import Project Link

If there is a naming collision, you have the option of renaming the project or overwriting the project. Project exports can also be restored / imported in the Designer. Once the Designer is opened you can choose File > Import from the menu. This will even allow you to select which parts of the project import you want to include and will merge them into the currently open project.

### Requirements

## Release Notes
Developed on 8.1.10
Did not test on other versions although it should work on anything above 8.1

## Authors and Acknowledgment
Built for the [Ignition Exchange](https://inductiveautomation.com/exchange) by Reese Tyson

## Support
View [Perspective Faceplate Library](https://inductiveautomation.com/exchange/2209) for more information, and other [versions](https://inductiveautomation.com/exchange/2209/versions)

## License
+ [MIT](https://choosealicense.com/licenses/mit/)
+ [Terms & Conditions](https://inductiveautomation.com/exchange/terms)
+ [Acceptable Use](https://inductiveautomation.com/exchange/use)
