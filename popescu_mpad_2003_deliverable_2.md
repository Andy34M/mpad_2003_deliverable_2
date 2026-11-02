**Nov 1st, 2026**<br>
**MPAD2003A Introductory Data Storytelling**<br>
**Andra Popescu**<br>
**Presented to Jean-Sébastien Marier**<br>

# Deliverable 2: Exploratory Data Analysis (EDA)

Use one hashtag symbol (`#`) to create a level 1 heading like this one.

# Deliverable 2: Exploratory Data Analysis (EDA)

## Foreword

For this assignment, you must clean and analyze the dataset from Deliverable 1, create exploratory charts/visualizations, and identify a potential story. Your assignment must clearly detail your process. You are expected to write about 1,000-1,200 words, and to include several screen captures showing the different steps you went through. Your assignment must be written with the Markdown format and submitted on GitHub.

I have been assigning different versions of this project to my digital journalism and data storytelling students for a few years now. Its structure was inspired by the main sections/chapters of [*The Data Journalism Handbook*](https://datajournalism.com/read/handbook/one/). This version was further inspired by the [Key Capabilities in Data Science](https://extendedlearning.ubc.ca/programs/key-capabilities-data-science) program offered by the University of British Columbia (UBC).

**Here are some useful resources for this assignment:**

* [GitHub's *Basic writing and formatting syntax* page](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [The template repository for this assignment in case you delete something by mistake](https://github.com/jsmarier/jou4100_jou4500_mpad2003_project2_template)

Did you notice how to create a hyperlink? In Markdown, we put the clickable text between square brackets and the actual URL between parentheses.

And to create an unordered list, we simply put a star (`*`) before each item.

## 1. Getting Data

Use two hashtag symbols (`##`) to create a level 2 heading like this one.
## I will analyze the City of Ottawa dataset that looks at Current Year Service Requests to see which parts of the city have the most difficulty to be accessible during the winter time. 

## I have come across problems when importing this dataset into Google Sheets. I used the =IMPORTDATA("") method, and kept getting an error. I then had to just download it and use Numbers on my Mac to organize the data to just display nov-march (wintertime). I did so by clicking organize, filter, then I hid all the months which aren't nov-march , like 2026-09 for example. Then, I downloaded it and imported it into Google Sheets. Sadly, it turned out to be a waste of time as all of it ended up exporting to the spreadsheet.

## Link to this year's data: https://open.ottawa.ca/documents/65fe42e2502d442b8a774fd3d954cac5/about

## Link to last year's data: https://open.ottawa.ca/documents/87abd7493677492f83295ec56e6a4929/about


To include a screen capture, use the sample code below. Your images should be saved in the same folder as your `.md` file.

![](Screenshot_1.png)<br>
*Figure 1: The "Import file" prompt on Google Sheets for this year's data.*
![](Screenshot_2.png)<br>
*Figure 2: The "Import file" prompt on Google Sheets for last year's data.*

## Link to this year's spreadsheet: https://docs.google.com/spreadsheets/d/1wNH6fUPj81aFi2rzRp6GTvcugoMNXg1k8KAyp53HXLw/edit?usp=sharing

## Link to last year's spreadsheet: https://docs.google.com/spreadsheets/d/1NcuhOlY8AEkwyX7-Ha-xpFqzldZGICvhLdP-LRDAzek/edit?usp=sharing

## There are 11 columns for both, titled: Service Request ID | Numéro de demande, Status | État, Type | Type, Description | Description, Opened Date | Date d'ouverture, Closed Date | Date de fermeture, Address | Adresse, Latitude | Latitude, Longitude | Longitude, Ward | Quartier, Channel | Voie de service. There are 372070 rows total in last year's dataset and 316776 rows for this year's dataset. The data is organized and easy to follow, however it is a lot of information and is awfully overwhelming.

## Column A contains nominal values since each service request ID is unique, but not in order. Column B contains ordinal variables, with the options being active, resolved, cancelled. I consider columns E and F to be intervals (elapsed time).

## Surprising information: a lot of addresses and wards are missing, which will make my project a lot harder to complete.

**Here are examples of functions and lines of code put in grey boxes:**

1. If you name a function, put it between "angled" quotation marks like this: `IMPORTHTML`.
1. If you want to include the entire line of code, do the same thing, albeit with your entire code: `=IMPORTHTML("https://en.wikipedia.org/wiki/China"; "table", 5)`.
1. Alternatively, you can put your code in an independent box using the template below:

``` r
=IMPORTHTML("https://en.wikipedia.org/wiki/China"; "table", 5)
```
This also shows how to create an ordered list. Simply put `1.` before each item.

## 2. Understanding Data

### 2.1. VIMO Analysis

Use three hashtag symbols (`###`) to create a level 3 heading like this one. Please follow this template when it comes to level 1 and level 2 headings. However, you can use level 3 headings as you see fit.

Insert text here.

Support your claims by citing relevant sources. Please follow [APA guidelines for in-text citations](https://apastyle.apa.org/style-grammar-guidelines/citations).

**For example:**

As seen in Bounegru & Gray (2011), a data visualization should be clear...

### 2.2. Cleaning Data

Insert text here.

### 2.3. Analyzing Data

Insert text here.

**This section should include a screen capture of your pivot table, like so:**

![](pivot-table-screen-capture.png)<br>
*Figure 2: This pivot table shows...*

**This section should also include a screen capture of your exploratory chart, like so:**

![](chart-screen-capture.png)<br>
*Figure 3: This exploratory chart shows...*

## 3. Delivering Data

Insert text here.

## 4. References

Include a list of your references here. Please follow [APA](https://apastyle.apa.org/style-grammar-guidelines/references) or [MLA](https://www.mla.org/MLA-Style) guidelines for references. Hanging paragraphs aren't required though.

**Here's an example:**

Bounegru, L., & Gray, J. (Eds.). (2021). *The Data Journalism Handbook 2: Towards A Critical Data Practice*. Amsterdam University Press. [https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153](https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153)
