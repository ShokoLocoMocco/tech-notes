## Showee's Epic Datasets List

During my data exploration in the last few years, I collected datasets literally from anywhere in my reach.  With lots of support from my network, the list is getting longer and thought I'd share it with my data fellas tp pay it forward.  
I'd also appreciate if you have more data sources you'd want me to add. :)
<br>


Disclaimer: This is a randomly formatted personal list (may include duplicates) and appears to be entirely US centered (especially of NYC), but you may get the idea. Your local communities/governments should have similar open datasets. 
Good luck with your data journey!

<br>


## Proxy data examples

Sometimes the data to support a business objective isn’t readily available. This is when proxy data is useful. Take a look at the following scenarios and where proxy data comes in for each example:

**Business scenario**|**How proxy data can be used**
-|-
A new car model was just launched a few days ago and the auto dealership can’t wait until the end of the month for sales data to come in. They want sales projections now.|The analyst proxies the number of clicks to the car specifications on the dealership’s website as an estimate of potential sales at the dealership.
A brand new plant-based meat product was only recently stocked in grocery stores and the supplier needs to estimate the demand over the next four years. |The analyst proxies the sales data for a turkey substitute made out of tofu that has been on the market for several years.
The Chamber of Commerce wants to know how a tourism campaign is going to impact travel to their city, but the results from the campaign aren’t publicly available yet.|The analyst proxies the historical data for airline bookings to the city one to three months after a similar campaign was run six months earlier.

ref: [Google Data Analytics course: What to do when there is no data](https://www.coursera.org/learn/process-data/supplement/dOyv7/what-to-do-when-there-is-no-data)

## Open (public) datasets

If you are part of a large organization, you might have access to lots of sources of data. But if you are looking for something specific or a little outside your line of business, you can also make use of open or public datasets. (You can refer to this [Towards Data Science article](https://towardsdatascience.com/is-there-a-difference-between-open-data-and-public-data-6261cd7b5389 "This link takes you to an article describing the difference between open and public data.") ✔️ for a brief explanation of the difference between open and public data.)

Here's an example. A nasal version of a vaccine was recently made available. A clinic wants to know what to expect for contraindications, but just started collecting first-party data from its patients. A **contraindication** is a condition that may cause a patient not to take a vaccine due to the harm it would cause them if taken. To estimate the number of possible contraindications, a data analyst proxies an open dataset from a trial of the injection version of the vaccine. The analyst selects a subset of the data with patient profiles most closely matching the makeup of the patients at the clinic. 

There are plenty of ways to share and collaborate on data within a community. Kaggle ([kaggle.com](https://www.kaggle.com/ "This link takes you to the Kaggle home page.")) which we previously introduced, has datasets in a variety of formats including the most basic type, Comma Separated Values (CSV) files.


### **CSV, JSON, SQLite, and BigQuery datasets**

-   CSV: Check out this [Credit card customers](https://www.kaggle.com/sakshigoyal7/credit-card-customers "This link takes you to a Kaggle dataset with anonymized credit card data. ") dataset, which has information from 10,000 customers including age, salary, marital status, credit card limit, credit card category, etc. (CC0: Public Domain, Sakshi Goyal).
    
-   JSON: Check out this JSON dataset for [trending YouTube videos](https://www.kaggle.com/datasnaek/youtube-new "This link takes you to a Kaggle dataset for trending YouTube videos.") (CC0: Public Domain, Mitchell J).
    
-   SQLite: Check out this SQLite dataset for 24 years worth of [U.S. wildfire data](https://www.kaggle.com/rtatman/188-million-us-wildfires "This link takes you to a Kaggle dataset for U.S. wildfires.") (CC0: Public Domain, Rachael Tatman).
    
-   BigQuery: Check out this [Google Analytics 360](https://www.kaggle.com/bigquery/google-analytics-sample "This link takes you to a sample Google Analytics dataset in Kaggle.") sample dataset from the Google Merchandise Store (CC0 Public Domain, Google BigQuery).
    

Refer to the Kaggle [documentation for datasets](https://www.kaggle.com/docs/datasets "This link takes you to the Kaggle documentation for datasets.") for more information and search for and explore datasets on your own at [kaggle.com/datasets](https://www.kaggle.com/datasets "This link takes you to the main Kaggle datasets page.").

As with all other kinds of datasets, be on the lookout for duplicate data and ‘Null’ in open datasets. Null most often means that a data field was unassigned (left empty), but sometimes Null can be interpreted as the value, 0. It is important to understand how Null was used before you start analyzing a dataset with Null data.

<br>

---

ref: [How to Find Accurate and Compelling Data (hubspot.com)](https://blog.hubspot.com/marketing/find-good-data?_ga=2.28485689.484125200.1630730850-1480187183.1627539989)
### General Data/Research

-   [UNData](http://data.un.org/): A statistical database of all UN data.
-   [Amazon Public Data Sets](https://www.google.com/webhp?sourceid=chrome-instant&ion=1&espv=2&ie=UTF-8&__hstc=20629287.917289041b2ba025a365c38550e42a32.1627549730597.1630802834507.1630843372787.33&__hssc=20629287.10.1630843372787&__hsfp=3429884198#q=amazon%20data%20sets): A repository of large data sets relating to biology, chemistry, economics, etc., including the the Human Genome Project.
-   [Pew Research](http://www.pewresearch.org/): Public opinion polls, demographic research, media studies, etc. 
-   [Find Open Datasets and Machine Learning Projects | Kaggle](https://www.kaggle.com/datasets)

### Academic Studies/White Papers

-   [Google Scholar](http://scholar.google.com/?__hstc=20629287.917289041b2ba025a365c38550e42a32.1627549730597.1630802834507.1630843372787.33&__hssc=20629287.10.1630843372787&__hsfp=3429884198): A wide array of information, including articles, theses, books, abstracts, white papers, court opinions,etc.

### Financial Data

-   [Google Finance](https://www.google.com/finance?__hstc=20629287.917289041b2ba025a365c38550e42a32.1627549730597.1630802834507.1630843372787.33&__hssc=20629287.10.1630843372787&__hsfp=3429884198): Real-time stock market data.
-   [Google Public Data Explorer](http://www.google.com/publicdata/directory?__hstc=20629287.917289041b2ba025a365c38550e42a32.1627549730597.1630802834507.1630843372787.33&__hssc=20629287.10.1630843372787&__hsfp=3429884198): Searchable large datasets on economic development worldwide.

### Government/World Data

-   [The CIA World Factbook](https://www.cia.gov/library/publications/the-world-factbook/): Global information on history, people, government, economy, geography, communications, transportation, military, etc.
-   [U.S. Census Bureau](http://www.census.gov/): Demographics, geographic information, and education for U.S. population.
-   [Data.gov](http://www.data.gov/): An open data source for U.S. government data. 

### Social Data

-   [SocialMention](http://www.socialmention.com/): Real-time social data.
-   [Google Trends](http://www.google.com/trends/explore?__hstc=20629287.917289041b2ba025a365c38550e42a32.1627549730597.1630802834507.1630843372787.33&__hssc=20629287.10.1630843372787&__hsfp=3429884198): Explore search data and trends.
-   [Topsy](http://topsy.com/): Search social trends and tweet history.

### Health Data

-   [Healthdata.gov](https://www.healthdata.gov/): Data on Medicaid, Medicare, clincial studies, treatments, etc.
-   [CDC.gov](http://www.cdc.gov/datastatistics/): Public health data from the Centers for Disease Control & Prevention.

---

#### General Interdisciplinary Repositories

[DRYAD](https://datadryad.org/search): https://datadryad.org/search

[Data is Plural](https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit#gid=0): https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit#gid=0 (*xlsx sheet saved, signed up for newsletter*)

[figshare](https://figshare.com/): https://figshare.com/ Scroll to the bottom to search

[HARVARD Dataverse](https://dataverse.harvard.edu/): https://dataverse.harvard.edu/

[Mendeley Data](https://data.mendeley.com/): https://data.mendeley.com/ ✔️ GC email, M!

[OSF (Open Science Framework)](https://osf.io/): https://osf.io/

[Opportunity Insights](https://opportunityinsights.org/data/): https://opportunityinsights.org/data/

<br>

#### NYC

[NYC OpenData](https://opendata.cityofnewyork.us/): https://opendata.cityofnewyork.us/

CapStat - Lawsuits against police: https://www.capstat.nyc/

NYPL Labs Menus: http://menus.nypl.org/data

NYPL Digital Collections: https://digitalcollections.nypl.org/

Citibike Ridership Data: https://www.citibikenyc.com/system-data

NYC Taxis: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page

StreetEasy: https://streeteasy.com/blog/data-dashboard/
<br>

#### Covid & Health

Covid Tracing from The Atlantic: https://covidtracking.com/

National Insitute of Health: https://datascience.nih.gov/covid-19-open-access-resources

NYTimes Data (covid-19-data): https://github.com/nytimes/covid-19-data (*GitHub, forked*)

OpenICPSR: https://www.openicpsr.org/openicpsr/covid19

World Health Organization: https://apps.who.int/gho/data/node.home

<br>

#### Race & Policing
#race 

Center for Racism, Social Justice & Health from UCLA: https://www.racialhealthequity.org/data

DiversityData from Brandeis: http://diversitydata.org/ ✔ Adults aged 18+ who are foreign-born naturalized citizens by race/ethnicity, & Racial/ethnic composition, adults aged 18-64 (percent) [DATA73200 JS FALL2020/Tutorial 1 - Introduction to d3.js](%E2%9C%94Tutorial1%20-%20Introduction%20to%20d3.js.md)

Stanford Open Policing: https://openpolicing.stanford.edu/data/

Urban Institute: https://datacatalog.urban.org/search/type/dataset

<br>

#### Social Sciences
Census data - American Fact Finder: "*American FactFinder has been decommissioned and is no longer available*." -> https://data.census.gov/cedsci/

Census Data - Historic (NHGIS): https://www.nhgis.org/

Census data - citysdk: https://uscensusbureau.github.io/citysdk/

World Bank data catalog: https://datacatalog.worldbank.org/

Campaign Finance Data: "*Page not found*"

H1B: https://h1bsalary.online/

psychometrics data (Raw data from online personality tests): https://openpsychometrics.org/_rawdata/

gun violence (Gun violence database): https://www.kaggle.com/gunviolencearchive/gun-violence-database

<br>

### Books, Culture & Humanities
Project Gutenberg: http://www.gutenberg.org/

Library of Congress: https://www.loc.gov/rr/news/

Association of Religion Data Archives: http://www.thearda.com/

National Archive of Data on Arts and Culture: https://www.icpsr.umich.edu/web/pages/NADAC/index.html
<br>

### Blogs & Websites

Visualizing Data: https://www.visualisingdata.com/

Flowingdata: https://flowingdata.com/

Periscopic: https://periscopic.com/#!/

Visualizing.org: https://www.visualizing.org/

Accurat: https://www.accurat.it/

Moritz Stefaner: http://truth-and-beauty.net/

Nocholas Felton: http://feltron.com/

Infosthetics: "*This site can’t be reached*"

Visualcomplexity: http://www.visualcomplexity.com/vc/

The Economist - Graphic Detail: https://www.economist.com/graphic-detail/

New York Times - The Upshot: https://www.nytimes.com/section/upshot

Visualoop: http://visualoop.com/



FiveThirtyEight: https://fivethirtyeight.com/features/our-33-weirdest-charts-from-2014/

Huffington Post (The Year In Graphics 2014): https://www.huffpost.com/entry/huffpost-infographics-201_n_6351828

LA Times (2014: The year in graphics): https://graphics.latimes.com/2014-in-graphics/

Wall Street Journal (The Year in Interactive Graphics 2014): http://graphics.wsj.com/wsj-interactives-2014/
(2015): http://graphics.wsj.com/wsj-interactives-2015/

Washington Post (The year in graphics 2014): https://www.washingtonpost.com/graphics/national/2014-in-graphics/

Quartz (charts in 2014): https://qz.com/318339/all-of-the-charts-we-made-in-2014/

New York Times - Interactive Storytelling (2014): https://www.nytimes.com/interactive/2014/12/29/us/year-in-interactive-storytelling.html?_r=0#data-visualization

Fathom: https://fathom.info/

Data Canvas: http://datacanvas.org/sense-your-city/#

Waze Global Driver Satisfaction Index (2016): https://inbox-static.waze.com/driverindex.pdf

Lapham's Quaterly Maps: https://www.laphamsquarterly.org/archive/maps

Lapham's Quaterly Charts and Graphs: https://www.laphamsquarterly.org/archive/charts-graphs

Territory: http://themapisnot.com/

Quartz Atlas Charts: https://theatlas.com/

Sensory Maps: https://sensorymaps.com/

Library of Congress - Maps: https://www.loc.gov/maps/collections/

The National Geologic Map Database: http://ngmdb.usgs.gov/ngmdb/ngmdb_home.html
<br>

### Podcasts:
Data Stories: https://datastori.es/

PolicyViz: https://policyviz.com/podcast/the-policyviz-podcast/
<br>

#### Potential Data Sources:
#dataset_all

- Twitter Data (contact Ellie for more info)
- NYC Open Data: https://opendata.cityofnewyork.us/
- Information is Beautiful: https://informationisbeautiful.net/data/
- Google public data: https://www.google.com/publicdata/directory
- Google Dataset Search: https://datasetsearch.research.google.com/
- FiveThirtyEight data: https://data.fivethirtyeight.com/ 🔖
- Kaggle “friendly” datasets: https://www.kaggle.com/rtatman/fun-beginner-friendly-datasets
- Cool datasets: https://www.cooldatasets.com/#Science-Datasets
- Driven Data competitions: https://www.drivendata.org/competitions/
- Free public datasets: https://www.springboard.com/blog/free-public-data-sets-data-science-project/
- Datasets subreddit: https://www.reddit.com/r/datasets/
- Pew research datasets: https://www.pewresearch.org/internet/?post_type=dataset
- Makeover Monday: https://www.makeovermonday.co.uk/data/
note: [Makeover Monday 📈📊](Makeover%20Monday%20📈📊.md)
- Tidy Tuesday: https://github.com/rfordatascience/tidytuesday/tree/master/data
- Data is Plural dataset resource: https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit
- [Data – Center for Effective Lawmaking (thelawmakers.org)](https://thelawmakers.org/data-download)
- 


**from textbook**

[Index of /~aa/cat/data (ufl.edu)](http://users.stat.ufl.edu/~aa/cat/data/)
<br>

**from Google course**
- [Patel Events data](https://docs.google.com/spreadsheets/d/1QLAbTqgD6dbVoFvdujk1kpENi4CL7dNTBEau_miWzDE/edit#gid=1888255122)
- [Customer Survey](https://docs.google.com/spreadsheets/d/1VPtYDKmPErwWboAI89evSdO0e8GsznfYenA1NRdge2c/edit#gid=49214881)
- [Historical Sales](https://docs.google.com/spreadsheets/d/1MiosTdcYzec_A4kkppOONT2E3YZplDd9b1uPFbl1iYc/edit#gid=324071257)

1.  [**U.S. government data site**](https://www.data.gov/ "U.S. government data site"): Data.gov is one of the most comprehensive data sources in the US. This resource gives users the data and tools that they need to do research, and even helps them develop web and mobile applications and design data visualizations. 
    
2.  [**U.S. Census Bureau**](https://www.census.gov/data.html "U.S. Census Bureau"): This open data source offers demographic information from federal, state, and local governments, and commercial entities in the U.S. too. 
    
3.  [**Open Data Network**](https://www.opendatanetwork.com/ "Open Data Network"): This data source has a really powerful search engine and advanced filters. Here, you can find data on topics like finance, public safety, infrastructure, and housing and development.
    
4.  [**Google Cloud Public Datasets**](https://cloud.google.com/public-datasets "Google Cloud Public Datasets"): There are a selection of public datasets available through the Google Cloud Public Dataset Program that you can find already loaded into BigQuery.  
    
5.  [**Dataset Search**](https://datasetsearch.research.google.com/ "Dataset Search")**:** The Dataset Search is a search engine designed specifically for data sets; you can use this to search for specific data sets.

-   The [Google Cloud Public Datasets](https://cloud.google.com/public-datasets "This link takes you to the Google Cloud Public Datasets site.") allow data analysts access to high-demand public datasets, and make it easy to uncover insights in the cloud. 
    
-   The [Dataset Search](https://datasetsearch.research.google.com/ "This link takes you to Google's dataset search engine.") can help you find available datasets online with keyword searches. 
    
-   [Kaggle](https://www.kaggle.com/datasets?utm_medium=paid&utm_source=google.com+search&utm_campaign=datasets&gclid=CjwKCAiAt9z-BRBCEiwA_bWv-L6PpACh6RzmrJjQjmNGCCE7kky1FCtc6Jf1qld-4NwDMYL0WsUyxBoCdwAQAvD_BwE "This link takes you to the Kaggle Datasets page where you can explore, analyze, and share data.") has an Open Data search function that can help you find datasets to practice with.
    
-   Finally, [BigQuery](https://cloud.google.com/bigquery/public-data "This link takes you to the BigQuery public datasets documentation.") hosts 150+ public datasets you can access and use. 
    

### **Public health datasets**

1.  [Global Health Observatory data](https://www.who.int/data/collections "This link takes you to the World Health Organization's data collections site."): You can search for datasets from this page or explore featured data collections from the World Health Organization.  
    
2.  [The Cancer Imaging Archive (TCIA) dataset](https://cloud.google.com/healthcare/docs/resources/public-datasets/tcia "This link takes you to the Google Cloud Cancer Imaging Archive (TCIA) overview page."): Just like the earlier dataset, this data is hosted by the Google Cloud Public Datasets and can be uploaded to BigQuery.
    
3.  [1000 Genomes](https://cloud.google.com/life-sciences/docs/resources/public-datasets/1000-genomes "This link takes you to the Google Cloud Life Sciences 1000 Genomes project page."): This is another dataset from the Google Cloud Public resources that can be uploaded to BigQuery. 
    

### **Public climate datasets**

1.  [National Climatic Data Center](https://www.ncdc.noaa.gov/data-access/quick-links "This link takes you to the NOAA data access page with quick access to climate and weather datasests."): The NCDC Quick Links page has a selection of datasets you can explore. 
    
2.  [NOAA Public Dataset Gallery](https://www.climate.gov/maps-data/datasets "This link takes you to a NOAA dataset gallery from climate.gov."): The NOAA Public Dataset Gallery contains a searchable collection of public datasets.
    

### **Public social-political datasets**

1.  [UNICEF State of the World’s Children](https://data.unicef.org/resources/dataset/sowc-2019-statistical-tables/ "This link takes you to statistical tables for children's health published by Unicef."): This dataset from UNICEF includes a collection of tables that can be downloaded.
    
2.  [CPS Labor Force Statistics](https://www.bls.gov/cps/tables.htm "This link takes you to the U.S. Bureau of Labor Statistics page."): This page contains links to several available datasets that you can explore.
    
3.  [The Stanford Open Policing Project](https://openpolicing.stanford.edu/ "This link takes you to the Stanford open policing project page and datasets."): This dataset can be downloaded as a .CSV file for your own use.

<br>

[DataSF](https://datasf.org/)
datasets from the City and County of San Francisco
[Film Locations in San Francisco](https://data.sfgov.org/Culture-and-Recreation/Film-Locations-in-San-Francisco/yitu-d5am?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkDB0201ENSkillsNetwork20127838-2021-01-01)


<br>

from Johns Hopkins course for capstone

[https://ourworldindata.org/](https://ourworldindata.org/) - This is a massive source of data driven graphics and articles, on a huge range of topics. At the bottom of the articles, you will find links to data sources >>> not sure if there is anything i want... 🤔 
![](Pasted%20image%2020220601033711.png)

[https://learn.g2.com/open-data-sources](https://learn.g2.com/open-data-sources) - A great list of data sources, some of which are repeated below

[https://www.data.gov/](https://www.data.gov/) - The US government's central data website, with link to data from many federal agencies

[https://www.census.gov/data.html](https://www.census.gov/data.html) - US Census data

[https://data.unicef.org/](https://data.unicef.org/) - UNICEF

[https://data.worldbank.org/](https://data.worldbank.org/) - World Bank data

[https://www.imf.org/en/Data](https://www.imf.org/en/Data) - International Monetary Fund Data

[https://www.bjs.gov/index.cfm?ty=dca](https://www.bjs.gov/index.cfm?ty=dca) - criminal justice data from the US

[https://www.who.int/data/gho/data/indicators](https://www.who.int/data/gho/data/indicators) - World Health Organization data

[https://healthdata.gov/](https://healthdata.gov/) - US health data

[https://www.kaggle.com/datasets](https://www.kaggle.com/datasets) - another inventory of data sets of various kinds and topics

[https://data.europa.eu/euodp/en/data/](https://data.europa.eu/euodp/en/data/) - the European Union Open Data Portal

[https://www.worldvaluessurvey.org/wvs.jsp](https://www.worldvaluessurvey.org/wvs.jsp) - The World Values Survey, international survey data

[https://www.vanderbilt.edu/lapop/survey-data.php](https://www.vanderbilt.edu/lapop/survey-data.php) - the Latin American Public Opinion Project, survey data from many Latin Americans countries.


June 2022 datasets from Data is Plural

"https://www.bls.gov/cpi/
https://www.bls.gov/cpi/data.htm
https://www.bls.gov/cpi/additional-resources/index-publication-level.htm"
"https://www.prisonersofthecensus.org/NYS_A9710-D.html
https://latfor.state.ny.us/data/?sec=2010amendpop
https://latfor.state.ny.us/data/?sec=2020amendpop
https://www.prisonpolicy.org/origin/ny/2020/report.html
https://www.prisonpolicy.org/about.html
https://vocal-ny.org/about-us/
https://www.prisonpolicy.org/origin/ny/2020/report.html#appendix
https://www.prisonpolicy.org/origin/ny/2020/county.html
https://www.prisonpolicy.org/origin/ny/2020/city.html
https://www.prisonpolicy.org/origin/ny/2020/zipcode.html
https://www.prisonpolicy.org/origin/
https://www.prisonersofthecensus.org/news/2021/10/26/state_count/"
"https://www.nature.com/articles/s41597-022-01360-z
https://icc.ise.bgu.ac.il/medical_ai/CDCDB/
https://clinicaltrials.gov/
https://www.data-is-plural.com/archive/2018-05-09-edition/
https://www.fda.gov/drugs/drug-approvals-and-databases/approved-drug-products-therapeutic-equivalence-evaluations-orange-book
https://www.data-is-plural.com/archive/2017-03-08-edition/"
"https://www.faa.gov/about/initiatives/lasers
https://www.faa.gov/aircraft/safety/report/laserinfo/
https://www.faa.gov/about/initiatives/lasers/laws"
"https://www.aeaweb.org/articles?id=10.1257/app.20180521
https://www.sethgbenzell.com/
http://kmcooke.weebly.com/
https://www.openicpsr.org/openicpsr/project/117045/version/V2/view
https://www.hull.ac.uk/staff-directory/brian-tompsett
http://web.archive.org/web/20120505084622/http://www3.dcs.hull.ac.uk/genealogy/royal/
https://www.journals.uchicago.edu/doi/pdf/10.1086/715065
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/M2E5OI
https://thebackend.dev/monarchs/
https://www.data-is-plural.com/archive/2019-06-19-edition/"
"https://www.stephenpettigrew.com/
https://www.westga.edu/profile.php?emp_id=91943
https://www.augie.edu/academics/majors-and-programs/government-and-international-affairs/political-science/faculty
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/26448
https://www.michaelgmiller.com/
https://twitter.com/nickicamberg
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/CXVMSY"
"https://www.nber.org/papers/w30088
https://www.openicpsr.org/openicpsr/project/170381/version/V3/view
https://en.wikipedia.org/wiki/List_of_core-based_statistical_areas
https://twitter.com/JohnConz/status/1531633773103677448"
"https://hkdc.us/about/
https://hkdc.us/political-prisoners-latest-update/
https://en.wikipedia.org/wiki/Hong_Kong_national_security_law
https://hkdc.us/political-prisoners-research-report/"
"https://journals.sagepub.com/doi/full/10.1177/00220027211072528
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/TOFZ09"
"https://isaw.nyu.edu/people/faculty/isaw-faculty/sebastian-heath
https://dlib.nyu.edu/awdl/isaw/isaw-papers/20-13/
https://github.com/roman-amphitheaters/roman-amphitheaters"
"https://www.chds.us/ssdb/
https://www.chds.us/ssdb/about/
https://www.chds.us/ssdb/methods/
https://www.cnn.com/interactive/2019/07/us/ten-years-of-school-shootings-trnd/
https://github.com/cnnlabs/cnn-school-shooting-data
https://github.com/washingtonpost/data-school-shootings
https://www.washingtonpost.com/graphics/2018/local/school-shootings-database/
https://www.data-is-plural.com/archive/2018-04-25-edition/
https://www.theviolenceproject.org/mass-shooter-database/
https://www.gunviolencearchive.org/
https://www.motherjones.com/politics/2012/12/mass-shootings-mother-jones-full-data/
https://www.data-is-plural.com/archive/2021-03-24-edition/
https://www.data-is-plural.com/archive/2015-12-09-edition/"
"https://congress.ippsr.msu.edu/congress/
https://twitter.com/MattGrossmann/status/1527287170515410945
https://ippsr.msu.edu/about-ippsr
https://raw.githubusercontent.com/IPPSR/congressData/main/congress_codebook_1.pdf"
"https://globalenergymonitor.org/about/our-story/
https://globalenergymonitor.org/projects/global-wind-power-tracker/
https://globalenergymonitor.org/press-release/new-trackers-showing-country-by-country-build-out-of-utility-scale-solar-and-wind/
https://globalenergymonitor.org/projects/global-solar-power-tracker/
https://globalenergymonitor.org/about/our-story/
https://globalenergymonitor.org/projects/
https://globalenergymonitor.org/projects/global-coal-tracker/
https://globalenergymonitor.org/projects/global-steel-plant-tracker/
https://globalenergymonitor.org/projects/global-oil-gas-extraction-tracker/"
"https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3873972
https://dataverse.harvard.edu/dataverse/mega-events;jsessionid=ac44ac785d9741f492283c74df49
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/F0MNC9"
"https://lib.bsu.edu/wmr/about.php
https://lib.bsu.edu/wmr/index.php
https://www.bsu.edu/Academics/CentersandInstitutes/Middletown.aspx
https://en.wikipedia.org/wiki/Middletown_studies
https://www.theguardian.com/membership/2016/oct/18/view-from-middletown-us-muncie-america
https://shelftalkblog.wordpress.com/2017/02/14/for-the-love-of-data-an-open-data-release/
https://www.data-is-plural.com/archive/2017-03-01-edition/"
"https://www.top500.org/project/authors/
https://www.top500.org/
https://www.top500.org/project/linpack/
https://www.acm.org/media-center/2022/march/turing-award-2021
https://blog.datawrapper.de/the-race-to-build-the-fastest-supercomputer/
https://twitter.com/EdurneMG
https://www.bsc.es/marenostrum/marenostrum
https://www.top500.org/lists/top500/list/2021/11/"


https://www.nber.org/research/data/us-intercensal-population-county-and-state-1970

https://www2.census.gov/programs-surveys/popest/datasets/2010-2018/counties/totals/ 

https://www2.census.gov/programs-surveys/popest/datasets/2020-2021/counties/totals/

https://www.irs.gov/statistics/soi-tax-stats-migration-data

https://www.irs.gov/statistics/soi-tax-stats-migration-data-2019-2020

<br>

world >>> [UNdata](http://data.un.org/)
[Global Industry Market Sizing - ==NationMaster==](https://www.nationmaster.com/)

==national== >>> [Data.gov](https://www.data.gov/)
state >>> [State of New York | Open Data | State of New York (ny.gov)](https://data.ny.gov/)
[StateMaster - US Statistics, State Comparisons](http://www.statemaster.com/index.php)

city >>> [NYC Open Data - (cityofnewyork.us)](https://opendata.cityofnewyork.us/)

by category >>> [Americans for the Arts |](https://www.americansforthearts.org/)
[Google Trends](https://trends.google.com/trends/?geo=US)
[Yahoo Finance - Stock Market Live, Quotes, Business & Finance News](https://finance.yahoo.com/)

<br>

#### network analysis

**Stanford Large Network Dataset Collection**: https://snap.stanford.edu/data/




<br>

https://www.stats.govt.nz/large-datasets/csv-files-for-download/
covers ↓ 
-   Business
-   Census
-   Economy
-   Environment
-   Government finance
-   Health
-   Industries
-   Labour market
-   Population
-   Society
