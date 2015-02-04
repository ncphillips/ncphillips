# Nolan Phillips
## Contact Information
* Phone: 902-394-1549
* Email: ncphillips@upei.ca
* [Github: www.github.com/ncphillips](www.github.com/ncphillips)
* [Resume: www.github.com/ncphillips/resume](www.github.com/ncphillips/resume)
* [LinkedIn](ca.linkedin.com/pub/nolan-phillips/68/935/702/)

## Skills

* **Development Processes:** Agile/Scrum
* **Programming Languages:** Javascript, Python, PHP, Objective-C, C, Java
* **Markup:** XML, XPath, XML Schema, HTML & CSS, Markdown, LaTeX
* **Frameworks and Platforms:**
	* **Python:** Django
	* **PHP:** Drupal, Islandora
	* **Javascript:** NodeJS, AngularJS
* **Operating Systems:** Ubuntu Linux, Mac OSX, iOS, Android
* **Data Storage:** MySQL, MongoDB, Fedora Commons, HDF5
* **Server:** Apache, Tomcat
* **Search:** Solr, SQL, SPARQL
* **Other:** Vagrant

## Experience
### UPEI Research Assistant
Working under Dr. Scott Bateman in researching crowdwork. 

#### Crowdsourcing
 * Reasearching two Crowdsourcing platforms: **Crowdflower**, and **Amazon's Mechanical Turk**.
 * Contributing to the **nodejs-crowdflower** library developed by Scott Bateman's former employee.
 * Created a **meanjs-crowdflower**, a web service for linking Crowdflower together Job's into workflows. 

### Robertson Library Programmer - May to August 2014
A continuation of the CS 482 Project. 

Developed three modules for the Islandora project, and used those module's to help build the new UPEI Marine & Natural Products Lab website. 

#### Islandora CModel Drupal Module
* Introduces CModel subtyping/polymorphism
* Introduces CModel relationship definitions
* A CModel creation UI (In Progress)

[Github Link:](https://github.com/ncphillips/islandora_cmodel)  /ncphillips/islandora_cmodel

#### Islandora Related Content Drupal Module
* Drupal tab for viewing a data object's related content.
* Takes advantage of the Islandora CModel function to populate this tab dynamically.
* Defines new drupal hooks for altering the way related content is displayed and filtered upon.
* Allows users to create child content on the fly, instead of manually setting the relationship after the object 

[Github Link:](https://github.com/ncphillips/islandora_related_content) /ncphillips/islandora_related_content


#### Islandora Solr Queryset Drupal Module
* Provides classes for building and executing Solr queries.
* Solr queries are defined using arrays, in a grammar I developed.

[Github Link:](https://github.com/ncphillips/islandora_solr_query_set) /ncphillips/islandora_solr_query_set

### CS 482 Islandora Bioinformatics Project - Backend Team Lead - 2014
* **Team Lead:** 
	* Managed scrum team: reviewing deliverables, planning sprints, setting up meetings. 
	* Communicated with frontend team, Robertson Library developers, and Kerr Lab liason. 
* **Islandora/Drupal/Fedora:** 
	* Extended the open source Islandora project to work with bioinformatics data.
	* Developed novel Islandora features such as abstract content types, relationships between content types, and a UI for managing related content.
	* Began updating the UPEI Kerr Labs website to Drupal/Islandora 7 and implemented the new Bioinformatics features for storing bioassay, lcms, and genesequence data pertaining to specimen in the lab.

### Bell Aliant - Network Operations Technician - Summer/Fall 2013
Performed various tasks related to several of Bell Aliant's services: Video OnDemand; Home Security; IP Security; physical & digital network.

**Video OnDemand:** 

* Verified functionality of Video On Demand servers, and investigated issues with Set Top Box applications.
* Acted as liason between alpha testers and developers of the Bell Aliant Beam App.


**Home Security:** 

* Aided field technicians with the installation and management of Home Security System. 
* Called customers in response to unusual or absent activity.

**Bell Network:** 

* Translated technical details of network outages for use by executives and PR.
* Detected and contacted customers who have virus infected machines, or are acting as sources of spam email traffic.

**Documentation:**

* Updated and formatted documents intended for new employees explaining how to perform various tasks using Bell Aliant systems.


**Tools Used:** 

* **Awk/Sed:** Wrote scripts to quickly pull required information from various reports and format them correctly.
* **Microsoft Outlook/:** Outlook for emails and scheduling, along with Word for creating documentation.

### Whole Cell DB - Developer - Summer 2013
* **Python/Django:** 
	* Used the Django ORM and H5Py to create a custom HDF5/MySQL hybrid database. 
	* Stores output from the Whole Cell Model simulation runs (>400Mb)
	* Output is stored as a set of n-dimensional arrays within the HDF5 files. Natively these HDF5 files are not searchable.
	* Made HDF5 files searchable by indexing their arrays in MySQL and coupling the records with  HDF5 objects via the Django ORM and H5Py library.

__Related Links__
 
 * [WholeCellDB](http://wholecelldb.stanford.edu)
 * [Git Repository](https://github.com/CovertLab/WholeCellDB)
 
### Hoplite Labs, UPEI - Student Researcher/Programmer - Summer 2012
* **Ruby (OnRails, Sinatra)/Apache:** Set up a _RubyOnRails/Sinatra_ website for storing cDNA sequences and making them searchable using the BLAST aglorithm. Website was hosted using an *Amazon EC3* virtual machine with the Apache2 webserver.
* **Python:** Identified Flounder cDNA genes by writing a _Python Mechanize_ script to BLAST against NCBI website, and scrape the results for the best match.
* **Blast2Go:** Confirmed the identity of winter flounder genes and analyzed those which were differentially expressed using Blast2Go. Provided various diagrams showing what chemical pathways were being noticeably affected.

 

## Education
#### University of Prince Edward Island, 2010 - 2014
* Bachelors of Computer Science, with a Biology Minor - 2014
* Recipient of the Harrison McCaine Scholarship, 2010-2014

## Publications
#### WholeCellSimDB: a hybrid relational/HDF database for whole-cell model predictions
Jonathan R. Karr; Nolan C. Phillips; Markus W. Covert

Database 2014;

doi: 10.1093/database/bau095

[Link to Abstract](http://database.oxfordjournals.org/cgi/content/abstract/bau095?
ijkey=zWkdaKziz1kFmPt&keytype=ref)
