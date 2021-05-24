# machine-learning-challenge
Machine Learning UCD

Cleaning Data:
First and foremost I needed to clean and understand the data:
This is my understanding of what the data means:
koi_disposition: Confirmed means that the potential plannet has not yet been proved to not be a planet. This means we only care about confirmed data
koi_fpflag_nt, koi_fpflag_ss, koi_fpflag_co, and TT_koi_fpflag_ec: 1 means the potenial planet has planet like charatersitcs and 0 means that it does not. This means we care about 0.
koi_period: How long it takes to complete a planeteary cycle around that sun. These columns can be deleted. 
Koi_time: When "planet" was discovered. These columns can be deleted. 
Koi_imact: Sky calculation, . This is difficult to undestand, so I will not use.
Koi_duration: How long the planet's data was collecte. Higher data means better results so I will keep these columns. 
Koi_depth, model: Transit depths. This seems not related to if this is or is not a planet, so I will not use. 
prad: Radious. Delete, as this could be a star or other non planetary object. 
Kei_tech, insol: Estimated temprature. Will delete, as this does not help in determing planet or not. 
koi_tce: Planet like featueres. The more the merrier. 
Steff, Slogg, srad: Star temp. We are not looking for starts so delete. 
KIC, not sure what these measn so I will delete. 
