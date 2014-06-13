##What is Metadata?:

Metadata, literally “data about data,” is everything that can be said about an information object or asset at any level of aggregation (item, folder, or entire system). An information asset is a discrete entity that can be addressed and manipulated by an information system or user, such as an electronic file. In general, all information assets have three features that can and should be described through metadata—content, context, and structure.

##Why Metadata?

Metadata helps ensure that information systems are accessible, interoperable, and scalable. It provides important context about an informational asset’s source and manner of creation, as well as in what applications or environments the asset is relevant. Metadata also has the following purposes:

* certifies the authenticity and degree of completeness of the content;
* establishes and documents the context of the content;
* identifies and exploits the structural relationships within and between information objects;
* provides a range of intellectual access points for an increasingly diverse range of users.

##A Few More Words

Information is often imperfect, whether produced by members of Open Development Mekong or by others. Details may be missing, badly defined, or completely wrong. Sometimes it is possible to improve the quality of the information by contacting its source. But, even then, problems may remain.
 
Still, we aim for the metadata to be as correct as possible. What does that mean? How can metadata be correct if the information it is describing is flawed?
 
Metadata describes the extent of our knowledge about an asset. It states what we know and how we know it. It also explains what we do not know, confusions we have, and the steps (if any) we are taking to address this. Metadata is alive! It changes when the asset itself or our knowledge of the asset changes.

The template below serves as a guide as we continue to build our catalog of information. It details the information we wish to include as part of out metadata and the steps needed to describe this information.

##Open Development Mekong Metadata Template

###Title

* *Definition*: Name given to the information asset.
* *Guidelines*: Short phrase, written in plain language. Should be sufficiently descriptive to allow for search and discovery.

###Description

* *Definition*: Short description explaining the content and origins of the asset.
* *Guidelines*: Description of a few sentences, written in plain language. Should provide a sufficiently comprehensive overview of the asset for anyone to understand its content, origins, and any continuing work on it. This can be filled out at the end, since it summarizes the key information from the other metadata fields.

###Format

* *Definition*: List of file formats in which the asset is available.
* *Guidelines*: Lowercase list of file format abbreviations, separated by semicolons. Most common: ```csv; doc; geojson; json; pdf; shp; txt```.

###Language

* *Definition*: List of languages in which the asset is available.
* *Guidelines*: Lowercase list of [ISO 639-1](http://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) language name abbreviations, separated by semicolons. Most common: ```en (English); km (Khmer); lo (Lao); my (Burmese); th (Thai); vi (Vietnamese)```.

###Download URL

* *Definition*: Unique URL for the current information asset.
* *Guidelines*: If multiple versions of the asset are available (i.e. in different formats and languages), list them as: ```url (format, language)```.

###Access and Use Constraints

* *Definition*: 
* *Guidelines*: Standard language, written by a lawyer.

###License

* *Definition*: The license under which the asset is published.
* *Guidelines*: All assets wholly created by Open Development Mekong are licensed under a Creative Commons Attribution-Sharealike (CC BY SA) license. Assets that were sourced elsewhere retain their original license, as does each component from an asset aggregated using multiple sources. If necessary, contact the source to determine its license.

###Date Created

* *Definition*: Date the asset was first published by its creator.
* *Guidelines*: Write as ```YYYY-MM-DD```. If an element is unknown, write a 0 in place of the digit.

###Date Uploaded

* *Definition*: Date the asset was first added to the Open Data Network catalog.
* *Guidelines*: Write as ```YYYY-MM-DD```. If an element is unknown, write a 0 in place of the digit.

###Date Last Updated

* *Definition*: Date a new version of the asset was added to the data catalog.
* *Guidelines*: Write as ```YYYY-MM-DD```. If an element is unknown, write a 0 in place of the digit. If no new version has been uploaded, then write NA.

###Temporal Coverage

* *Definition*: The period of time for which the asset is relevant.
* *Guidelines*: Write as ```YYYY-MM-DD:YYYY-MM-DD```, where the first date is the start of coverage and the second date is the end. If a date element is unknown, write a 0s in its place. If the asset covers an entire calendar year, just write the year of its relevance: ```YYYY```.

###Spatial Coverage

* *Definition*: The geographic area for which the asset is relevant.
* *Guidelines*: Provide all countries for which the asset is relevant, separated by a semi-colon. For instance, if the asset pertains to all countries in the Lower Mekong Region, write ```Cambodia; Laos; Myanmar; Thailand; Vietnam```.

###Accuracy

* *Definition*: Details on the level of accuracy of the asset and any existing issues.
* *Guidelines*: Accuracy can refer to the spatial resolution of a satellite image, disagreements others have expressed about the asset’s contents, any other references that contain contrary information, and other issues. Should be written in plain language sentences, with numbers when appropriate.  If you are not aware of any problems, write: ‘There are no known issues with accuracy.’ If the asset or some of its content describes something that is changing in a way that affects accuracy, add ```Information subject to change``` and, if possible, describe the nature of the change.

###Logical Consistency

* *Definition*: Issues with logical consistency in the asset and the steps, if any, being taken to validate its content.
* *Guidelines*: Human-readable description. Can be a mix of numbers and words (e.g. ```Concessions A and B overlap 50 hectares. We anticipate conducting field validation of these concessions by 2014-10-31.```). If you are not aware of any problems, write: ```There are no known issues with logical consistency```. If the asset or some of its content describes something that is changing in a way that affects logical consistency, add ```Information subject to change``` and, if possible, describe the nature of the change.

###Completeness

* *Definition*: The level of completeness of the asset’s contents and the steps, if any, being taken to make the asset more complete.
* *Guidelines*: Human-readable description. Can be a mix of numbers and words (e.g. ```Locations are included for 30 of 50 concessions in the dataset. We are in the process of acquiring official government documentation on the remaining 20.```). If you are not aware of any problems, write: ```There are no known issues with completeness```. If the asset or some of its content describes something that is changing in a way that affects completeness, add ```Information subject to change``` and, if possible, describe the nature of the change.

###Processes

* *Definition*: The steps taken to acquire, aggregate, or transform the information asset into the form the metadata describes.
* *Guidelines*: Human-readable description, written in plain language. Include any details regarding updates occurring to the asset (e.g. ```Cambodia's province boundaries were geo-referenced from the 2008 Economic Census of Cambodia. Phnom Penh and Kandal province boundaries were updated after geo-referencing the 2011 Economic Census of Cambodia. Boundaries for the newly created province, Tbong Khmum, and resulting changes to Kampong Cham province will be added once the National Institute of Statistics releases the 2014 Economic Census in September.```).

###Sources

* *Definition*: Ordered citations for all information sources that went into producing the information asset described by the metadata.
* *Guidelines*: Use [Chicago citation style](http://www.chicagomanualofstyle.org/tools_citationguide.html), with sources listed alphabetically.

###Contact

* *Definition*: Contact information for the individual or organization that is responsible for or most knowledgeable about the asset.
* *Guidelines*: Include all of the information below that can be found: 

				Name
				Organization
				Email
				Phone
				Website
				Street Address

###Metadata Reference

* *Definition*: Information on the currentness of the metadata information provided and the individual(s) responsible for maintaining it.
* *Guidelines*: Write as:

				Metadata last updated on YYYY-MM-DD. For inquiries contact:
				
				Name
				Organization
				Email
				Phone
				Website
				Street Address

###Attributes

* *Definition*: Details about the attributes contained in the information asset
* *Guidelines*: List of attributes, the organization that defined them, and what the attribute describes (including any units of measurement in parentheses).

				Attribute Name / Organization : Attribute Definition
