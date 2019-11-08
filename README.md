# Background:

This repository contains the Proof of Concept Technology Deployment for FOAR705. It will include a software package installer named RBTools for Mac that can be run that downloads and begins the installation process for Zotero and Open Semantic Search. The package will also open relevant websites to create accounts, download and provide instructions on how to install those tools and Hypothes.is for data organisation and references.

# Outline:

This package utilises and provides instructions for installing three tools for research: Zotero, Hypothes.is and Open Semantic Search. These tools can be used for the organisation of sources and reference management.

Zotero is an open-source reference management software to manage bibliographic data and related research materials.

Hypothes.is is a web annotation tool that is integrated with browsers.

Open Semantic Search is an open source enterprise-search research tools for faceted search, exploratory search, tagging & annotation, text analytics & mining.

VirtualBox is a virtual machine required to run Open Semantic Search.

An executable file named RBToolsPackageforMac was created in Bash that downloaded installation packages for Zotero and Open Semantic Search, created folders, opened websites to create Zotero and Hypothes.is accounts and prompt the reading of instructions to use the three tools when opened.

The instructions also explain how to connect Zotero to Overleaf and how to integrate Hypothes.is with Open Semantic Search.

# Requirements:

The installer for the package can only be run on an Apple macOS. It cannot be used on Windows or Linux. Approximately 4GB of disk space will be required.

To use this installer on another operating system, a virtual machine or the separate downloading of component tools will be required.

Zotero may be downloaded from https://www.zotero.org/download/.

Open Semantic Search can be downloaded from https://www.opensemanticsearch.org/download/

VirtualBox can be downloaded from https://www.virtualbox.org/wiki/Downloads

Open Semantic Search requires Virtual Box to be installed to operate.

# Installation:

After downloading and opening the zip file, please run the installer file named RBToolsPackageforMac.

When the installer software package is run, a folder named install-package will be created on your Desktop where installation files for Zotero, Open Semantic Search and VirtualBox will be downloaded to.

Your default browser will also open at the URLs to create Zotero and Hypothes.is accounts.

The package's Instructions will also open to guide you through the process of installing the software on all operating systems.

An online HTML version of the instructions are also available at https://ofchiumq.github.io/rbtoolsinstructions/

# Issues:

This software package has a number of limitations.

The software package does not provide instructions on how to use the full range of functionalities of Open Semantic Search and Zotero or how to link Zotero and Hypothes.is using the Hypothes.is API. For example, thesauruses can be uploaded to automatically tag documents based on keywords in Open Semantic Search. Instructions on these functionalities is not included as I have not been able to work out how to do these in the time available or that there is other existing documentation on tool websites.

The installer software package only downloads certain Mac versions of Zotero, Open Semantic Search and VirtualBox. Software for a different operating system or a newer updated version is not automatically downloaded. These programs will need to be manually downloaded if the installer does not work.

The installer software package may not open when clicked due to security settings as it was not created by an identified developer. To bypass these security settings, control-click the RBToolsPackageforMac file, then click Open. The app will be saved as an exception to security setings in the future. 
