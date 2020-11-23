# NdW2020
Repository for code used in the Online Code Along-Workshop in connection with the 2020 Nacht der Wissenschaft in Kiel. 

# Aim 
The aim of this online code along workshop is to introduce code based text mining to newcomers. This is done by letting attendes work directly with the methods and material themselves. In this workshop the material is text and metadata from the old newspaper Lyna(1797-1848) which was published in Haderslev/Hadersleben. This newspaper is used in this workshop due to it's language being a mix between Danish and German. In particular we will be working with the year 1847, which places the workshop in a historical setting amidst national identity formation, war and changing borders. 

# Data 
The dataset is as mentioned text from the newspaper Lyna. A few remarks should be mentioned on the genesis of this data. The old printed newspaper har of course be collected to an library back in the days. At some point the collected newspapers started filling up to much space in the libraries. This resulted in the photographing of the individual newspaperpages and following transferal to microfilm. Leafing through microfilm can however be abit cumbersome.  
This is why a digitisation process was started in 2014. The process encompassed amongst other things a proces of text recognition (called Optical Character Recognintion(OCR)) on the now digital copies of the photographed newspapers. This made it possibel to do free text searches throug a news paper, which was a great improvement compared to turning your self through a mikrofilm.  
This proces of OCR works very well on 'modern' characters, but has some dfficulties reading the fonts used in newspapers in the 18th century, the so-called fraktur:

![](http://hax.odsbjerg.dk/fraktur.png)

This difficulties results in so-called OCR-mistakes, where the printed text has not been recognised properly. Since our dataset is from 1847 we must expect some OCR-mistakes.  

Data is made available through the Library Open Access Repository (LOAR) under the Royal Danish Library. Even though we read in the data from Lyna from 1847 directly from an URL to the ressource in LOAR, you should be aware that every year of the newspaper's life time is avaiable here: 
https://loar.kb.dk/handle/1902/7736
LOAR also contains alot more open access data - it is worth a look. 

# Dataprocessing 
The dataprocesssing, in our case text mining, will be done with the statistical coding language, R. In order to save time on installation and so on this is done through the browser-based rstudio.cloud. This runs R and RStudio in your browser and you will be up and running once you've signed up! 

## Methods and approaches
The methods and approaches to text mining that we work with in this workshop is based on the tidytext-principle. In this priciple each word of your target text-element will be put on it's own rown, while retaining all other meta-data. For more information and also as post-workshop inspiration see:  
https://www.tidytextmining.com
