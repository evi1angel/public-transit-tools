# generate-GTFS-shapes

The Generate GTFS Shapes toolbox produces a shapes.txt file for your GTFS dataset.  You give the tool a valid, existing GTFS dataset, and the tool creates a new shape.txt file and updates the shape_id field in trips.txt and the shape_dist_traveled field in stop_times.txt.

## Features
* Create a shapes.txt file for your GTFS dataset.
* Start from a reasonable estimate of the shapes and use the editing tools in ArcGIS to make them perfect.
* ArcGIS toolbox - No coding is required to use this tool.  Just add the toolbox to ArcMap and use the tools like any other geoprocessing tools.

## Instructions

1. To simply use the tool, download the latest release and follow the included User's Guide. 
2. If you want to play with the code, fork it and have fun.

## Requirements

* ArcGIS 10.2.1 or higher with a Desktop Basic (ArcView) license. This tool does not work in ArcGIS Pro yet.
* Network Analyst extension. (You can run a limited version of the tool without the Network Analyst extension.)

## Resources

* [User's Guide](https://github.com/ArcGIS/public-transit-tools/blob/master/generate-GTFS-shapes/UsersGuide.md)
* [GTFS specification](https://developers.google.com/transit/gtfs/reference)

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Contributing

Esri welcomes contributions from anyone and everyone. Please see our [guidelines for contributing](https://github.com/esri/contributing).

## Licensing
Copyright 2015 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt](https://github.com/mmorang/generate-GTFS-shapes/blob/master/License.txt) file.

[](Esri Tags: ArcGIS GTFS public transit transport transportation routes shapes shapes.txt editing shape_id shape_dist_traveled toolbox geoprocessing)
[](Esri Language: Python)​