# Nova_Scotia-PEI-New_Brunswick
FlightGear Canada Land Cover Scenery for Nova Scotia, Prince Edward Island and New Brunswick Provinces

## License
This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301, USA.

The zip archives on the Releases page were created using the TerraGear and TerraGear-GUI programs developed by the FlightGear project. The git repository includes the source data. To download the resulting scenery, go to [to be determined] and download the zip archives.

## Nova Scotia, Prince Edward Island and New Brunswick Custom Scenery

Custom scenery for all of Nova Scotia and Prince Edward Island, Canada, and most of New Brunswick, Canada for the FlightGear Flight Simulator. This scenery includes:
- The area airports recommended as of December 2020 from the X-Plane Scenery Gateway. This includes many airports and heliports that have not previously been included in FlightGear.
- The area between the following coordinates: 
  - min lat 48.0
  - max lat 43.0
  - min lon -67.0
  - max lon -59.0 
- Custom Material definitions and Textures for the area to make the land cover more realistic.
- Updated NavData for some of the airports. It should be downloaded and installed with this custom scenery. The updated airports use this updated data.
- Custom OSM2City scenery objects that match the elevations of the new custom scenery.

### Data Sources

- Airports: X-Plane Scenery Gateway: https://gateway.x-plane.com/
- Landcover: 2010 Land Cover of Canada https://open.canada.ca/data/en/dataset/c688b87f-e85f-4842-b0e1-a8f79ebf1133
- Elevation: Shuttle Radar Topology Mission 3-arc-second (SRTM-3), void-filled version: https://earthexplorer.usgs.gov/
- Rivers and waterbodies: Lakes, Rivers and Glaciers in Canada - CanVec Series - Hydrographic Features: https://open.canada.ca/data/en/dataset/9d96e8c9-22fe-4ad2-b5e8-94a6991b744b
- Buildings, roads, pylons, other objects: OpenStreetMap using osm2city: https://www.openstreetmap.org/ https://osm2city.readthedocs.io/en/latest/
- FlightGear TerraSync objects

### To Download

To download the custom scenery files, go to [to be determined] page and download the zip archives.

## Installation

To install:
1.  Create a directory on your local hard drive
1.  Download Buildings.zip, Objects.zip, NavData.zip, Pylons.zip, Roads.zip, and Terrain.zip. 
1.  Extract the files into the local directory you've created. 

    For example, create a directory called "NS-PEI-NB" on your computer. Extract the downloaded files into this directory. 

1.  Add this directory to Additional Scenery Folders in the FlightGear GUI (launcher) 
1.  To use the custom materials definitions and custom textures created:
    1.  Download ns-pei-nb-data.zip and extract it. Rename the folder to "data.zip".
    1.  Copy this "data" folder, open "$FG_ROOT" and paste. In Windows, this is the data folder within the FlightGear 2020.4 directory. This should result in novascotia-pei-newbrunswick.xml residing in the "$FG_ROOT/Materials/regions/" directory and a folder labeled "NS-PEI-NB" in the "$FG_ROOT/Textures/Terrain/" directory.
 1.  Start FlightGear. While on the start-up screen click "Add-ons". Scroll to the "Additional scenery folders" section, the click the plus (+) sign on the right side of the screen. A dialog box will pop up. Browse to the folder you created in step 1. Highlight the folder, then click "Select Folder". Confirm that the folder was added to the bottom of "Additional scenery folders". You can now highlight and move the folder to a higher priority if necessary. 
 1.  Make the selections you want to use for your next flight then click "Fly", as usual.
 1.  Rendering Options enable OSM buildings, detailed roads and pylons under 

## Screenshots

### North of Sydney, Cape Breton Island, Nova Scotia, Canada
![North of Sydney, Cape Breton Island, Nova Scotia, Canada](https://github.com/LGBudd/Nova_Scotia-PEI-New_Brunswick/blob/main/Screenshots/North_of_Sydney_NS.png)

### Cape North, Cape Breton Island, Nova Scotia, Canada
![Cape North, Cape Breton Island, Nova Scotia, Canada](https://github.com/LGBudd/Nova_Scotia-PEI-New_Brunswick/blob/main/Screenshots/Cape_North_NS.png)

### Takeoff, Nova Scotia, Canada
![Takeoff, Nova Scotia, Canada](https://github.com/LGBudd/Nova_Scotia-PEI-New_Brunswick/blob/main/Screenshots/Nova_ScotiaD.png)
