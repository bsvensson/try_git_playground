# arcgis-viewer-flex

This is the source code for the ArcGIS Viewer for Flex (a.k.a Flex Viewer). Learn more about Flex Viewer at [ArcGIS Viewer for Flex resource center](http://links.esri.com/flexviewer).

[View live app here](http://resources.arcgis.com/en/help/flex-viewer/live/index.html)

[App](https://raw.github.com/Esri/arcgis-viewer-flex/master/arcgis-viewer-flex.png)

## Features
* Illustrates how to change basemaps
* Many basemaps to choose from: Streets, Satellite, Topography, Oceans, Gray...
* Widgets provide specific funtionality, but their source code can also be used as samples for other apps

## Instructions (Getting Started)

See http://links.esri.com/flexviewer-gettingstarted-developers for more details.

1. In Adobe Flash Builder 4.5/4.6/4.7, go to "File" -> "Import Flash Builder project..."
2. Keeping "File" option selected, click "Browse..." button.
3. Select flexviewer-3.1-src.zip downloaded in step 1, e.g. "C:\Documents and Settings\jack\My Documents\flexviewer-3.1-src.zip".
4. "Extract new project to:" textbox will be automatically set to location where the project source will reside, e.g. "C:\Documents and Settings\jack\Adobe Flash Builder 4.6\FlexViewer.
5. Click "Finish" button. Project will be created and displayed in the Package Explorer window of Adobe Flash Builder, e.g. in this case FlexViewer.
6. If prompted to upgrade the project (because it was created with a previous version of Flash Builder), click "OK"
7. If prompted to choose Flex SDK version, select "Flex 4.6.0" or higher
8. If needed, download API Library from http://links.esri.com/flex-api/latest-download.
9. Go to "Project" -> "Properties" -> "Flex Build Path". 
10. Click "Add SWC" and navigate to the agslib-3.[*]-[YYYY-MM-DD].swc file.

Optionally:

1. Right click on this project (FlexViewer) -> Click "Properties" -> Click "Flex Build Path".
2. In the "Output folder" textbox at bottom, specify the location of your web server where your
    Flex Viewer should be deployed, e.g. in case of IIS web server, C:\Inetpub\wwwroot\flexviewerdebug.
3. In "Output folder URL" text box, specify the URL that matches with your output folder specified in last step, e.g. http://localhost/flexviewerdebug/
4. Click OK
5. Rebuild the project.
6. Select the project. Now let's run it - there are multiple ways of doing this: one way is to click green triangle button on top, another way is click Ctrl-F11 and a third way is to click "Run" menu, then select "Run Index".
7. Browser will open and Flex Viewer application will be displayed.

## Non-source code compiled versions

1. Download and unzip the .zip file.
2. Web-enable the directory or copy/paste the source to your own .html file.
3. Access the .html page.

## Requirements

* Knowledge of Flex development.
* A little background with Adobe/Apache Flex SDK.
* Experience with the [ArcGIS API for Flex](http://links.esri.com/flex) would help.

## Resources

* [ArcGIS Viewer for Flex Resource Center](http://links.esri.com/flexviewer)
* [ArcGIS API for Flex Resource Center](http://links.esri.com/flex)
* [Flex Viewer License agreement](http://www.apache.org/licenses/LICENSE-2.0.html)
* [Flex API License agreement](http://www.esri.com/legal/pdfs/mla_e204_e300/english.pdf)
* [ArcGIS Blog](http://blogs.esri.com/esri/arcgis/)
* [twitter@esri](http://twitter.com/esri)

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Contributing

Anyone and everyone is welcome to contribute. 

## Licensing
Copyright 2012 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt]( https://raw.github.com/Esri/arcgis-viewer-flex/master/license.txt) file.
