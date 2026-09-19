# Distance Sampling for Rare Plants
R code for Evaluating Distance Sampling as a Tool for Monitoring Populations of Rare Plants (Cactaceae: Sclerocactus glaucus and Sclerocactus dawsoniae), DePrenger-Levin et al
    
    
## 1 | Conventional Distance Sampling    
*ConventionalDS* : Estimating the population size and effort (measured as spacing between transects) needed to maximize accuracy and precision assuming:        
      (1) Detection declines with increasing distance from the observer and is perfect at distance zero    
      (2) The plant does not move    
      (3) The perpendicular distance is measured perfectly   
      (4) Sufficient individuals are observed to estimate the relationship between distance and density       
      (5) The population is uniform in density in relation to the transects        
      (6) While some individuals are not observed, there is no double counting           
      (7) Individuals are independently observed      

## 2 | Addressing violations to (5) uniform density in relation to the transects     
*DensityGradient_Patchy* : Estimating the bias caused by a density gradient and patchy distribution common to plant populations    

## 3 | Addressing violations to (1) perfect detection at distance zero, (5) patchy distribution of plants, and (7) independently observing individuals.    
*MRDS_plants* : Tested a crossed design to allow for double observations. Plants are marked by mapping their location. 
  
