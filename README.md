# airbnb-project
preprocessing of airbnb dataset to make analysis of market trends and global travel trends .¶
###info about dataset
columns : 29
( 10 numerical cloumns , 18 categorical columns , 1 boolean column )
rows : 74111¶ 
### dataset has alot of missing values features and outliers 
## Manual
#### read the dataset  (airbnb.csv)
### #make some analysis (info , describe ) to understand the data 
#### detect the missing data and start handle it by drop and impute the data 
#### make some feature engineering to get new features 
from host since get host since year
from last review get last review year and last review maonth
from amenities get some features like tv , wirless , smartlock , iron ,dryer , etc..
#### save to (airbnb_fulll.csv)
#### read (airbnb_fulll.csv) 
#### make visualization by plotly  and seaborn libraries and 
#### detect the outliers of the features and handle it 
#### convert any feature object to numerical 
#### save to airbnb_finish.csv 
## features
#### log_price ــــــــ>  price of unit in dollar  per night 
#### property_type ــــــــ> type of property (apartment / villa /etc..)             
#### room_type   ــــــــ>  type pf room (share , private , etc ..)               
#### accommodates ــــــــ>  number of allowable  accommodates in the unit            
#### bathrooms   ــــــــ>  number of bathrooms in the unit        
   #### bed_type   ــــــــ>   type of bed in the unit ( couch , realbed , etc ..)     
  #### cancellation_policy ــــــــ>  the rules of cancelation (flexible , strict , etc..)
   #### cleaning_fee  ــــــــ>  fees of cleaning included (0) or excluded (1)
  ####  city   ــــــــ>  the city where the unit locate 
   #### first_review ــــــــ>   the first review date for the unit in airbnb
  #### host_has_profile_pic ــــــــ>   the host of unit has profile picture (1) or not (0)      
  #### host_identity_verified  ــــــــ>  the host of unit has identity verfied  (1) or not (0)
  #### host_response_rate  ــــــــ>  the score of host in airbnb from (0 to 100 %)
  #### host_since   ــــــــ>   the date when the host of the unit post the unit in airbnb  
  #### instant_bookable  ــــــــ>  feature that clarify the host of the unit has instant booking (1) or not (0) 
  #### last_review  ــــــــ>  the date when the unit take last review in airbnb
  #### latitude ــــــــ>    location of unit 
  #### longitude ــــــــ>    location of unit          
  #### neighbourhood ــــــــ>  the neighbourhood where the unit locate in the city
 #### number_of_reviews ــــــــ>  number of reviews which that unit take from its resident
  #### review_scores_rating  ــــــــ>  the score of unit in airbnb from (0 to 100 %)
 #### zipcode ــــــــ>  the postcode of the unit  
 #### bedrooms  ــــــــ> number of bedrooms in the unit
 #### beds  ــــــــ>    number of beds in the unit 
 ####  first_review_year  ــــــــ>  the year of first review 
 #### last_review_month ــــــــ>  the month of last review 
  #### last_review_year ــــــــ> the year of last review 
  #### TV  ــــــــ>   the unit has tv (1) or not (0)
 #### Wireless ــــــــ> the unit has wirless (1) or not (0)
  #### Air conditioning ــــــــ>  the unit has air conditioning (1) or not (0)
 #### dryer ــــــــ> the unit has dryer (1) or not (0)
  #### Iron  ــــــــ> the unit has iron (1) or not (0)
 #### Bathtub  ــــــــ>  the unit has bathtub (1) or not (0)
  #### Lockbox ــــــــ> the unit has lockbox (1) or not (0)
  #### Smart lock ــــــــ>  the unit has smart lock (1) or not (0)
 #### Smoking allowed ــــــــ> the smoking allowed in unit (1) or not (0)
 #### Free parking ــــــــ>  the parking free in unit  (1) or not (0)
 ####   Pets live on this property ــــــــ> pets allowed in the unit (1) or not (0)
