# MKS Data Catalogue

The MKS Data Catalogue component is a plugin for the Wordpress content management system (https://wordpress.org/) which enhance it with data cataloguing capabilities, similar to popular data catalogue, registry or repository platforms. It creates a new type of posts for datasets and another one the licences (redistribution policies) associated with the datasets. It also include page templates for searching and browsing the data, as well as creating forms to register new basic datasets. 

Amongst the advantages of the MKS Data Catalogue component is the very easy deployment (as long as you have a Wordpress platform installed, which is straighforward), as well as the ease of customisation and extension (by modifying the stylesheets and templates available, or creating wordpress plugins interacting with the catalogue).

## Installation 

You should have Wordpress running and configured before installing the MKS Data Cataloguing component. Once that's done, download or clone this repository and copy the "mks-data-cataloguing" repository in the "wp-content/plugin/" folder of your wordpress installation. The plugin will then appear in the plugin area of the Wordpress admin interface, and you should be able to activate it.

## How to use

Once activited, the MKS Data Cataloging plugin will create a new type of post called "Datasets" available from the right hand side menu of the Wordpress admin interface. This acts like a typical Wordpress post, which can be described using text, tags and categories. In addition, fields are added that are specific to datasets, including the data owner, format, status, and licences (redistribution policies).

Available licences (redistribution policies) can be edited through another type of post, which can include the text of the licence document, as well as a basic description of its clauses in terms of duties, permissions and prohibitions. 

You can also point directly to the dataset by including it as a source file or link, and attach to the dataset a number of services that use or give access to the data in a specific way.

The plugin will also create a number of page templates that can be used to create dedicated pages, including "Data Catalogue Public Page" (for searching and browsing datasets) and "New Dataset Page" (for a form to create a new dataset without using the Wordpress admin interface).

## Licence and attribution

Being a Wordpress plugin, MKS Data Cataloguing inherit the GPL licence from it. It is therefore available here under the GPL V3 licence (https://www.gnu.org/licenses/gpl-3.0.en.html). 

Whenever making a website that include the MKS Data Cataloguing function in a public way, please include in a visible place (e.g. you "About" page) a setence attributing the source of the plugin and linking back to this repository, e.g.

"This website makes use of the Data Cataloguing plugin developed by datahub.technology (http://datahub.technology), with contributions from the MK:Smart project (http://mksmart.org) - see https://github.com/datahub-technology/datahub-catalogue/"

## Compatibility with CKAN API

This is currently being developped and will be made available soon.
