# Getting Started
 
To get started with cBioPortal, first go to:  https://www.cbioportal.org/.

From the home page, note the top navigation bar:

![cBioPortal Navigation Bar](img/navbar.png)

From here, you can drill-down to different sections of cBioPortal.  For beginners, the two most important tabs are "Tutorials" and "FAQ".

With that, you are ready to try your first query.  For this section, we will explore the [Cholangiocarcinoma study from MSKCC](https://www.cbioportal.org/study/summary?id=chol_msk_2018).  If you are interested, you can also access the paper on [PubMed Central](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6642361/).

From the home page, you have several options for getting started.

## Option 1:  Browse

In the first option, you can use the left navigation pane to **browse** by cancer type:

![Browse by Cancer Type](img/home_browse.png)

## Option 2:  Search

In the second option, you can use the search box to **search** by cancer type or study name:

![Search by Cancer Type](img/home_search.png)

{% hint style="info" %}
There are lots of tricks you can use within the search box.  For example, you can quickly find all Pan-Cancer TCGA studies by entering:  "tcga pancancer".  Or, you can quickly find all TCGA Studies, but remove the Pan-Cancer Studies by entering:  "tcga -pancancer".
{% endhint %}

## Branching

Once you have selected your study, you have the option of selecting one of two options:

![Branching](img/home_branch.png)

For now, click the "Query by Gene" button.

You should now see:

![Query By Gene](img/home_query_by_gene.png)

This panel provides several options, which you may wish to explore.

  1. **Select Genomic Profiles**:  Use these options to hone in on genomic data of interest.  For example, you can choose to analyze just mutation data or just copy number data.  Note that different options will appear here for each cancer study.

  2. **Select Patient/Case Set**:  Use these options to hone in on the patients of interest.  For example, you can choose all patients with mutation data or all patients with mutation and copy number data.  You can even enter a list of specific patient or sample identifiers.

  3. **Enter Genes**:  Use the pull-down menu to select from pre-defined gene sets, or use the text box to enter one or more genes.  You can enter HUGO gene symbols, gene aliases or Entrez Gene IDs.  The text box will also automatically validate your input and provide suggestions if we can't find an exact match.

When you are done, click the "Submit Query" button and continue on with the next section.