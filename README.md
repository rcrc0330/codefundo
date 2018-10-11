# idea for codefundo

## What are we planning to build
    
    An Android app for alerting user and giving safety instructions in case of a flood forecast; Also providing their location and details to NGO's, goverment organisations and relatives.


## How does it work

    * The App takes some basic information from user and permission to monitor the user mobile's GPS location. 
    
    * The App is able to provide DO's and DONT's for emergency situations along with helpline numbers which will prove useful in case of emergency situations.
    
    * The App will ALERT the user about any nearby floods (in a specified diameter from location of user).
    
    * If user's GPS location and coincide with flood region for more than a specified period of time, the app will alert user and will switch to emergency mode. 
    
    * In case emergency mode activates (which can be determined by either user input or the monitored GPS position or both) app sends the user's basic information and GPS location to a different database consisting of other user's data that are affected by the same.This database can then be provided to different Goverment authorities and NGO's concerned with helping the flood victims.
    
    * Also, the App would forward the details and GPS coordinates of the person along with a SOS message through SMS to a list of contacts (provided by user), this feature will also help the one with poor or no internet connectivity.
    


## How users can get started with the project

    * First user will install the app.
    
    * User will be asked permission to allow using Real-Time GPS location (while installing the app) along with basic permissions.
    
    * User will be required to provide basic details (during first time login) about him/her which will be shared with appropriate agencies in case of emergency.
    
    * User will be asked to provide the list of contacts which will be sent the SOS message during an emergency.
    
## What dataset(s) are we using
    *List of websites used for collecting data:- 
1. For list of flood affected areas- [Flood forecast](http://www.india-water.gov.in/ffs/flood-forecasted-bulletins/for-level-forecasted-sites/)
2. For checking water level of rivers nearby- [Water level of river](http://india-water.gov.in/ffs/hydrograph/)
3. For checking previous forecasting effectiveness- [Previous Forecastings](http://www.india-wris.nrsc.gov.in/wrpinfo/index.php?title=CWC_National_Flood_Forecasting_Network)
4. For Instuctions for Emergency situations- [Measures for Emergency situations](https://ndma.gov.in/en/do-s-and-dont-s.html)
5. For List of NGO's- [Lists of NGO's](https://ngosindia.com/ngos-of-india/)
6. For List of Goverment agencies- [Lists of Disaster management authorities](https://www.gktoday.in/gk/disaster-management-agencies-of-india/)
        
 ## What Technologies are we using
 
    1. Android Studios:-
                        For making Android App
                        
    2. JSON:-
              For collection useful data from websites
              
    3. GPS API:-
                 For taking real-time location
     
     4. SMS API:-
                 For sending SOS during emergency
