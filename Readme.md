


# NHM Data Collection project - May 2017 

## South America Marsupial Collection

The aim of this project was to collect measurement and ecological data on a sample of South American marsupial specimens from the Natural History Museum (London): 

The species analysed were: 

* Buff-bellied Fat-tailed Mouse opossum (*Thylamys venustus*)
* Elegant fat-tailed mouse opossum (*Thylamys elegans*) 
* White-bellied fat-tailed mouse opossum (*Thylamys pallidior*) 
* Karimi's fat-tailed mouse opossum (*Thylamys karimii*) 


## Prerequisites for running our analysis 

Some packages you will need to install: 

````
if (!require("pacman")) install.packages("pacman")
pacman::p_load(c("dplyr", "tidyverse", "ggplot2), character.only = T)

````

## Running the analysis 

To run our code, go to [NAMEOFOURMD.md](link)



# Some things to note 

## Variables key 

Where avaiable, information was taken from specimen labels. When measurement data wasn't available, we took our own using a caliper. 


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


## Built With

* [R](https://cran.r-project.org/) - The comprehensive R Archive Network 



## Contributors: 

* [Jen Ball](https://github.com/JenBall)
* [Bruno Casanova](https://github.com/BrunoCasa)
* [Ellen Coombs](https://github.com/EllenJCoombs)
* [Emma Dunne](https://github.com/emmadunne)
* [Aislinn Pearson](https://github.com/aislinnpearson)


## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.


## License

This project is licensed under the Marsupial License - see the [LICENSE.md](LICENSE.md) file for details






