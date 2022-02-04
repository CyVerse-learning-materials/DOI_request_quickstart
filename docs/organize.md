[Learning Center Home](http://learning.cyverse.org/)

# 2. Organize data

There are several steps to properly organizing your dataset. These
include determining what data to include, how many identifiers to
request, how to organize the data into folders, and creating the ReadMe
file and data inventory.

------------------------------------------------------------------------

## 2.1. Determine what to include:

A data collection may be composed of multiple files and different
datasets. In preparing your data for publication identify the data and
other materials that you consider useful for validation and reuse of
your research:

-   Data associated to a research project may include multiple files
    with different roles.
-   If there are components of your dataset that belong in a public
    repository such as NCBI (e.g., fastq files), submit them to the
    repository, rather than to CyVerse Curated Data. You may want to
    include a list of external files in your dataset, with links.
-   Beyond data, you will include the ReadMe file (see Step 2.5), and
    you may include scripts or links to scripts to run your analysis.
    Links to analysis tools can also be included as metadata (see step
    3).

------------------------------------------------------------------------

## 2.2. Determine how many permanent identifiers to request:

To determine how many DOIs to request for a given data collection,
consider the following:

-   Size and number of components.
-   How many studies or publications does it represent?
-   Is your data collection formed by different datasets and are those
    likely to be used separately?
-   Do you want to create a data collection with one DOI for the entire
    project and additional related DOIs for distinct datasets so that
    they are cited individually? DOIs can be nested, so that one dataset
    is part of another.
-   If you are uncertain about how many DOIs to request, contact us at
    <doi@cyverse.org>.

------------------------------------------------------------------------

## 2.3. Organize your data into folder(s):

1.  Organize your data so that there is one folder for each DOI, named
    according to step 2.4.

2.  

    Within a folder, include all files in your data package plus the ReadMe file and the inventory.

    :   -   You may have subfolders within a data package.
        -   You may include compressed files in a package, as described
            on the Permanent Identifier FAQs, but do not compress the
            entire folder/package.

------------------------------------------------------------------------

## 2.4. Name your top level folder according to the guidelines:

The folder containing your dataset should be named using the
\$[Creator]()\$[subject]()\$date format.

For more details on folder naming, see the .

------------------------------------------------------------------------

## 2.5. Create a ReadMe file:

Create a text file labeled \"readMe\" with the following information:

-   How you obtained, organized, and labeled your dataset.

-   How to reuse the data, such as which apps can analyze the data.

-   The inventory (see step 2.6) may be included as part of the readme
    file.

-   

    Examples of good readme files:

    :   -   <http://datacommons.cyverse.org/browse/iplant/home/shared/commons_repo/curated/Carolyn_Lawrence_Dill_G2F_Mar_2017/_readme.txt>
        -   <http://datacommons.cyverse.org/browse/iplant/home/shared/commons_repo/curated/Liang_Schnable_UNLPlantVision_2017/readMe.txt>

------------------------------------------------------------------------

## 2.6. Create an inventory:

You must create a plain text document that includes an inventory of the
contents of the organized dataset (at a minimum, your dataset will
contain one data file and one ReadMe file).

The inventory may be part of the ReadMe file or a separate file.

The inventory should include the ReadMe file and any other additional
non-data materials you add to your dataset.

If your dataset contains folders with many files (e.g., large
collections of images), you do not need to list each file in the
inventory. Simply describe the folder and what it contains.

Describe the file naming conventions, if that is helpful.

------------------------------------------------------------------------

## 2.7. Example:

Example:

    Lyons_DOI-Example-Aug2020:  Top level directory name
    README.txt:          Plain text file that describes the origin of the data, experiments, data processing, etc.
                         Also contains a list and description for the contents of the top-level directory (unless a separate inventory file is provided)
    License.txt:         License file (e.g., GPL, MIT) that governs the use of the data
    a.data1/:            Directory containing data
    b.data2/:           Directory containing more data
    c.data3/:            Directory containing even more data
    d.analysis_graphs/:  Results, graphs, analyses, and other good stuff

## \-\-\-\-\-\-\-\-\--Next Steps:

> 3.  [Add metadata](metadata.html)
> 4.  [Submit request](submit.html)
> 5.  [After publication](after.html)

## Additional information, help

The UPenn library offers to organizing data.

DataONE best practices for .

------------------------------------------------------------------------

\_ [Learning Center Home](http://learning.cyverse.org/)

> \# Use this example to ensure that links open in new tabs, avoiding \#
> forcing users to leave the document, and making it easy to update
> links \# In a single place in this document

> \<a
> href=\"<https://learning.cyverse.org/projects/cyverse-doi-request-quickstart/en/latest/Additional/naming.html>\"
> target=\"blank\"\>CyVerse Curated Data Folder-Naming Guidelines\</a\>

> \<a href=\"<https://guides.library.upenn.edu/datamgmt/fileorg>\"
> target=\"blank\"\>this guide\</a\>

> \<a
> href=\"<https://www.dataone.org/best-practices/create-manage-and-document-your-data-storage-system>\"
> target=\"blank\"\>document storage systems\</a\>
