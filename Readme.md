


# NHM Data Collection project - May 2017 

## South America Marsupial Collection

The aim of this project was to collect measurement and ecological data on a sample of South American marsupial speciemens: 

The species analysed were: 

![Species](https://github.com/EllenJCoombs/NHM_R_project/blob/master/Marsupial%20pic.jpg)

Photo credit: *Chris Momberg* 


* Buff-bellied Fat-tailed Mouse opossum (*Thylamys venustus*)
* Elegant fat-tailed mouse opossum (*Thylamys elegans*) 
* White-bellied fat-tailed mouse opossum (*Thylamys pallidior*) 
* Karimi's fat-tailed mouse opossum (*Thylamys karimii*) 


## Prerequisites for running our analysis 

Some package you will need to install: 

````
if (!require("pacman")) install.packages("pacman")
pacman::p_load(c("dplyr", "tidyverse", "ggplot2), character.only = T)

````

## Running the analysis 

To run our code, go to [NAMEOFOURMD.md](link)




# Some things to note 

## Variables key 

* Registration ID = NHM unique specimen number
* Genus
* Species
* Subspecies
* Binomial = Genus and species (and subspecies)
* Country
* Locality = state or county
* Collection_date = date specimen was collected
* Collector = name of who collected the specimen
* Collector2
* Altitude = (m)
* Sex = M or F
* Tail_length = length of tail only (mm)
* Head_body = length of head and body together (mm)
* Total_length = length of head, body and tail together (mm)
* Ear_length = length of ear (mm)
* Hind_foot = length of hind foot (mm)
* Weight = weight in grams 
* Age = juvenile or NA


## Contributors: 

* [Jen Ball](https://github.com/JenBall)
* [Bruno Casanova](https://github.com/BrunoCasa)
* [Ellen Coombs](https://github.com/EllenJCoombs)
* [Emma Dunne](https://github.com/emmadunne)
* [Aislinn Pearson](https://github.com/aislinnpearson)









