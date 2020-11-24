# Nacht der Wissenschaft 2020
Repository for code used in the Online Code Along-Workshop in connection with the 2020 [Nacht der Wissenschaft](https://67km.eu/) in Kiel. 

## Aim 
The aim of this online code along workshop is to introduce code based text mining to newcomers. This is done by letting attendees work directly with the methods and material themselves. In this workshop the material is text and metadata from the old newspaper Lyna (1797-1848) which was published in Haderslev/Hadersleben. This newspaper is used in the workshop due to its language being a mix between Danish and German. In particular we will be working with the year 1847, which places the workshop in a historical setting amidst national identity formation, war and changing borders. 

## Data 
As mentioned, the dataset consists of text from the newspaper Lyna. A few remarks should be made on the genesis of this data. The old printed newspapers have of course been collected to a library back in the days. At some point the collected newspapers started taking up too much space in the libraries. To remedy this each individual newspaper page was photographed and subsequently transferred to microfilm. Leafing through microfilm can however be a bit cumbersome.

For these reasons, a digitisation process was started in 2014. The project encompassed amongst other things a process of text recognition (called Optical Character Recognition; OCR) on the now digital copies of the photographed newspapers. This made it possible to do free text searches through a newspaper, which was a great improvement compared to reviewing the microfilm manually.  
The process of OCR works very well on 'modern' characters, but has some difficulties reading the fonts used in newspapers in the 18th century; the so-called Fraktur:

![](http://hax.odsbjerg.dk/fraktur.png)

These difficulties result in OCR-mistakes, where the printed text has not been recognised properly. Since our dataset is from 1847 we must expect some OCR-mistakes.  

Data is made available through the Library Open Access Repository (LOAR) under the Royal Danish Library. Even though we read in the data from Lyna from 1847 directly from an URL to the resource in LOAR, you should be aware that every year of the newspaper's life time is available here: 
https://loar.kb.dk/handle/1902/7736  
LOAR also contains a lot more open access data - it is worth a look. 

## Data processing 
The data processing, in our case text mining, will be done with the statistical coding language, R. In order to save time on installation and so on this is done through the browser-based [RStudio Cloud](https://rstudio.cloud/). This runs R and RStudio in your browser and you will be up and running once you've signed up! 

## Methods and approaches
The methods and approaches to text mining that we work with in this workshop is based on the tidytext-principle. In this principle each word of your target text-element will be put on its own row, while retaining all other meta-data. For more information and also as post-workshop inspiration see:  
https://www.tidytextmining.com
