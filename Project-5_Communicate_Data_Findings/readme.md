# (Ford GoBike System Data)
## by (Ahmed Said)


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area happened in April 2018 :-

- Each trip is anonymized and includes:
- Trip Duration (seconds)
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)

## Summary of Findings

> As we find that 
  - the trip duration is between (1 - 100) minutes and the most frequent value is 10 minutes
  - the most frequent type of user types are subscribers
  - the most frequent hours of start time in the day are 8 am and 5 pm
  - There are segnificant appear for both user types in the 5 pm Hr and the subscribers has segnificant appear at 8 am
  - The user type of the customer has the longest duration trip at 4 am and 5 am
  - The user type of the subscriber has the longest duration trip at 1 am and 11 pm


## Key Insights for Presentation

> The most minor value of trip duration is 10 minutes
> The average duration of customer types are higher than avarage duration of subscribers

## Resources
> https://www.lyft.com/bikes/bay-wheels/system-data
> https://www.delftstack.com/howto/python-pandas/how-to-convert-dataframe-column-to-datetime-in-pandas/#:~:text=Pandas%20to_datetime%20(%20pd.-,to_datetime()%20)%20function%20to%20convert%20DataFrame%20column%20to%20Pandas%20datetime,the%20given%20argument%20to%20datetime%20.&text=Pandas%20to_datetime%20format%20parameter%20specifies%20the%20pattern%20of%20the%20datetime%20string.
> https://chartio.com/resources/tutorials/how-to-check-if-any-value-is-nan-in-a-pandas-dataframe/
