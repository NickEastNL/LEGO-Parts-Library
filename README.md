# LEGO Parts Library
## Description
This LEGO parts library is comprised of custom made parts, based on the LDraw library, optimized for use in game engines. All parts are exported as text-based .obj files so they can be stored more easily in a repository, with as minimal redundant metadata as possible.

All parts are named using their official part IDs according to the LEGO Group and as used in the LDraw system. A separate tool is in development to assign the actual part descriptions to the IDs using a catalog file downloaded from either Bricklink or Rebrickable.

For easy assembly of the model in 3ds Max, there's a tool written using Maxscript and C# that uses this library to find and import the parts and assemble the model according to an LDraw file. The tool is going to be available shortly.

The main library contains the parts as modeled using the LDraw library and optimized as much as possible. Various derived libraries will be created for various LOD levels and usages. All parts are sorted by major categories and single-level subcategories (these may not match (sub)categories from other catalogs).

## Development
This library was created for a personal project. Parts will only be added as I need them. I cannot comply to requests as I do not have the time to do so. If anyone wants to add parts to the library, it is of course allowed to fork the repository and offer push requests to update it. However, it also takes time to perform a quality check to ensure it is optimized properly and usable by the Importer, which again means I cannot comply to every request.

NOTE: Whenever a commit is titled "Added parts" or similar, one or more new parts are added and you can check the details of them. You can search for part IDs to find out if a part you want exists.

## Usage
Everyone may freely download and modify this library according to the GNU license. When using this library together with the 3ds Max LDraw Parser & Importer and the Parts Library Tool (released later), the following files are necessary:
* categories.xml: Used by the Library Tool to create and sort (sub)categories and by the Importer to validate the library.
* parts.xml/.csv: A downloaded version of the parts catalog from Rebrickable or Bricklink to get the names.
* Resources: This folder contains all material libraries used by the Importer to assign the correct colors. Also contains Photoshop swatches.

DO NOT edit or move these files/folders when using either tool. It will cause errors.

## Disclaimer
This project is for non-commercial use only. The LEGO Group supports "Fair Play". DO NOT abuse this by misusing this library, or any reference to the LEGO brand, for commercial gain.

LEGO® is a trademark of the LEGO Group which does not sponsor, authorize or endorse this project. ©2016 The LEGO Group. All Rights Reserved.
