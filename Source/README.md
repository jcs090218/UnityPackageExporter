# Package Exporter

Export multiple packages by just one click, with no need to uncheck the assets.

<p align="center">
  <img src="./etc/package-manage.png"/>
</p>

## :trophy: Features

* Export multiple packages in a project
* Export method similar to `.gitignore` (easy for coder)
* Lightweight, no other dependencies
* Clean, no files are generated
* Highly compatible to any Unity version

## :hammer: How to use?

Here explains how you use this package correctly.

### :mag: Step 1. Import Package

You will need to import the package to your project. The package 
can be download from [here](https://github.com/Pixisoft/PackageExporter/releases).

### :mag: Step 2. Start using Package Exporter Window

You can start the `PackageExporter` window from the menu bar `PackageExporter`.

### :mag: Step 3. Fill package info and generate `.unityignore` file

<img src="./etc/package-info.png"/>

After you fill the info, then hit `Generate Unity Ignore` button.

### :mag: Step 4. Edit `.unityignore` file

All the `.unityignore` files can be found under `PackageExporter/unityignore`
directory. 

### :mag: Step 5. Export...

Once the `.unityignore` file is generated, the according package 
export button should appear.

### :tada: Done, and Enjoy! :partying_face:

Now you can manage as many packages you want to export! :tada:

## `.unityignore` File Example

Generated `.unityignore` file for `Hello World` package.

```
# 
# Thank you for using `Package Exporter`. This is the generated 
# unityignore file.
# 
# Package Name: Hello World
# Version: 1.0.0
# Creation Date: 2017-10-25 06:58:14 
# 
# Package Link: https://github.com/Pixisoft/PackageExporter
# Author: Shen, Jen-Chieh
# Email: pixisoft.tw@gmail.com
# 

# Ignore this plugin itself.
ProjectExporter

```

## :rocket: Exporting

Export the package `Hello World`.

<p>
  <img src="./etc/export-package.gif"/>
</p>

## :pencil: Todo List

- [ ] Support ingore extension syntax. (*.meta)

## License

Copyright (c) Pixisoft. All rights reserved.

Licensed under MIT. See [LICENSE.txt](https://github.com/Pixisoft/PackageExporter/blob/master/LICENSE.txt) for details.
