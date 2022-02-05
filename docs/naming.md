[Learning Center Home](http://learning.cyverse.org/)

# Data Commons Naming Conventions 
CyVerse Curated Data datasets are searchable and discoverable based on their metadata.
While the dataset itself can have any name chosen by the creator (within
reason), the folder that contains the dataset must follow the naming
practices described on this page.

## General guidelines
- Folder names must be unique. In the case of a conflict with an existing dataset, your subject
can be modified slightly. 
- No invalid characters: Be sure there are **no spaces or special characters in the folder name**; for more
information, see [Using Special Characters in the DE](https://wiki.cyverse.org/wiki/display/DEmanual/Using+Special+Characters+in+the+DE). 
- Use underscores between each segment.

------------------------------------------------------------------------

## Format

**\$Creator_\$subject_\$date**

**\$Creator:**

-   The Creator entry should be the same as entered in the Creator field
    of the DOI request - DataCite Metadata request form.

- The Creator is the lead author, the senior author, or the
organization with the primary responsibility for the dataset. Start the
field (the creator's name) with a capital letter.

**Co-creators:**

-   If two co-creators, okay to use both names, separated by an
    underscore or using camel case.
-   If three or more co-creators, select only one name or use a
    consortium name. Other contributors should be acknowledged in the
    metadata (as creators or contributors), which will display on the
    dataset landing page.

**$subject:**

-   Very briefly describes what the dataset is about.
-   If the subject is more than one word, use either camel case
    (example: camelCase) or underscores (example:
    underscore_between_words) to separate the words.
-   If another folder has the exact same name, you may modify the
    subject slightly to maintain uniqueness.

**$date:**

-   Either just the year, or the month and year, in which the dataset
    was created.
-   Month and year should be used only if there is likely to be more
    than one dataset with the same creator and subject within the same
    year.
-   Month must be a three-letter abbreviation: Jan, Feb, Mar, Apr, May,
    Jun, Jul, Aug, Sep, Nov, Dec

------------------------------------------------------------------------

## Examples

### Correct examples

The following will pass the folder name validation check:

-   Walls_yam_variation_2015
-   DeBarry_yamGenomicVariation_2016
-   Esteva_yam_variation_Mar2016
-   Esteva_Walls_yam_genomic_variation_Jun2016
-   YamConsortium_Dioscorea_variation_Nov2017

### Counter examples

#### Invalid

The following will fail the folder name validation check:

-   WallsYamVariation_2016 (Missing underscore between the creator and
    the subject)
-   Esteva_yam_variation_June2016 (Month should be three letters: Jun)
-   YamConsortium_Nov2017 (No subject)
-   Walls_yam_variation_2016#1 (Contains a special character)
-   Walls YamVariation 2020 (Contains spaces)

#### Not recommended

Although the following will pass validation, they are not recommended
because the subject is too vague or too detailed:

-   Walls_variation_2016 (Subject too vague)
-   Esteva_yam_Mar2016 (Subject too vague)
-   DeBarry_yam_genetic_and_environmental_variation_with_phenotype_data_version3_Dioscorea_2016
    (Too detailed)

------------------------------------------------------------------------

[Learning Center Home](http://learning.cyverse.org/)