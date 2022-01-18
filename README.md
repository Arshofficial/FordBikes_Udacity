# FordBikes Data Exploration

## Dataset

The data consisted of prices and attributes of approximately 183,412 trips. The attributes included the characterstics such as : duration_sec, tart_time, end_time, user_type, start_station_name and end_station_namefour. Eight thousand four hundred and sixty two data points were removed from the analysis due to inconsistencies or missing information.
The dataset can be found in the repository : https://github.com/Arshofficial/FordBikes_Udacity

## Summary of Findings

In the exploration, I found that dataset includes 183,412 trips 'rows' with 16 features 'columns'. Out of 16 features, seven are float64, two are int64, and seven objects. Also, start and end time have the wrong datatype( string instead of date-time object).
According to me, the main features are the duration of the trip, origination and conclusion of trips, the user-type and most used stations.
Trip duration per type of user shows that the customers average duration is higher than the subscribers. While as seen in the univariate plot the subscribers bike ride count is higher than the customers bike ride count. Also, the start station and end station does not much determine the duration. It suggests that some starting stations are having higher visited as the starting point and some end stations are having higher visited as the ending point.
Graphs suggest, bigger number of users prefer ride bike in the morning at 8. On the other hand, the users end the trip usually at 5 pm.
 
## features in the dataset I think will help support my investigation into your feature(s) of interest

    * duration_sec
    * start_time
    * end_time
    * user_type
    * start_station_name
    * end_station_name


## Key Insights for Presentation

For the presentation, I focus on finding patterns between types of users and their trip behaviour. 
Starting Off, I find ratio of Users falling into each of two categories, Customers/Subscribers. 

Afterwards, I study the distribution of passengers based on station of Journey Origination and station of Journey Conclusion.
I Further, discuss about most rush hours for comopany, i.e, tendency of traffic followed by passengers for onboarding and deboarding trips over 24hrs a day.
