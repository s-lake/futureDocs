---
title: Pre-ingest bagging
layout: default
nav_order: 1
---

# Pre-ingest bagging

The aim of this step is to reliably organize the materials that will be ingest and create a first checksum to monitor fixity throughout the ingest process.
## Prepare the files
Create a new folder named “ingest” in the fonds or collection folder in Archival Holdings Management or in Digital Collections Archive. 

Move items to be ingest into the folder. Move preservation copies or born-digital materials only.

* Note that because of the large size of video files, it is best to create a single AIP for each video file. If the AIP is too large, Archivematica might run out of processing space and the transfer will fail.

* Audiovisual material will not be pushed to AtoM, therefore there is no need to ensure that the AIP structure matches the series structure in AtoM.

* Since we will most likely push some photos to AtoM, it is best to decide what will or won’t be published before creating the AIP, but it is possible to do a partial re-ingest on an AIP and create a DIP to push to AtoM

Rename digitized files according to file naming convention (see Appendix 1).
## Bag the files
Open Bagger and create a new bag with no profile. Click the green “+” button in the left-hand “Payload” pane. Navigate and select the items in the  Ingest folder.

Save the bag in the Ingest folder. Name the bag according to the AIP naming convention (see Appendix 1).

Set the “Tag Manifest Algorithm” and “Payload Manifest Algorithm” to md5 in the drop down menu.

Click Ok. Depending on the size of the bag this process can take time. Once this process is complete and the bag is saved you will receive a message saying “Bag Saved Successfully”.

