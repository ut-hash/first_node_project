# Notes for My First Node project


**npm init**: the command to initialise the node project

**version: x.y.z major.minor.patch**

When to change which version
When you are providing just a pacth to the project update the patch version
When you are providing a feature update which is compatible with previuos version, you update the minor version.
When you are providing the entire new update with features that are not compatible with previous version, you update the major version. 

**How use versioning when importing a package as a dependency**
1. Exact version: "2.3.4"
2. Greater than version: ">2.3.1"
3. Compatible version: "^2.*3.21*" (In this case minor and patch version may chane but not the major version based on the availability of the dependent project)
4. Patch accepted version: "~2.3.*2*" (Only the latest package with minor version updated will be downloaded as a dependency).


## Dependency installation
'npm install' is the command that is used to download all the dependencies listed in package.json file under node_modules folder. 

If you want to install a specific dependency in the project, you can use npm install {project name}. This will add a entry in the dependecies section inside package.json and download the dependency in the node_modules folder.
