<!--------------------------------------------------------------------------------- Data -->
# Data
[Economy] > [Data]

<!--------------------------------------------------------------------------------- Diagram -->
<br><br>

## Diagram
![](https://github.com/kashanimorteza/economy_document/blob/main/design/data.png)



<!--------------------------------------------------------------------------------- Time -->
<br><br>

## Time

### Moment
    y   : Year
    moy : MonthOfYear
    wom : WeekOfMonth
    dow : DayOfWeek
    dom : DayOfMonth
    doy : DayOfYear
    hod : HourOfDay
    moh : MinuteOfHour
    som : SeccondOfMinute

### Period
    MO1 - W1 - D1 - H8 - H6 - H4 - H3 - H2 - H1 - m30 - m15 - m5 - m1

### Session
    New Zeland  : 00:00 08:00
    Australia   : 02:00 10:00
    Japan       : 03:00 11:00
    China       : 04:00 12:00 
    Germany     : 09:00 17:00
    UK          : 10:00 18:00
    USA         : 15:00 23:00



<!--------------------------------------------------------------------------------- Price -->
<br><br>

### Price

Layer 1 : Raw  
    Open  
    Close  
    High  
    Low  

Layer 2 : Distance  
    result              : close - open  
    excitement          : high - low  
    distance_open_high  : high - open  
    distance_open_low   : open - low  
    distance_close_high : high - close  
    distance_close_low  : close - Low  

Layer 3 : Ratio  
    result_excitement          : result / excitement  
    result_distance_open_high  : result / distance_open_high  
    result_distance_open_low   : result / distance_open_low  
    result_distance_close_high : result / distance_close_high  
    result_distance_close_low  : result / distance_close_low  
    excitement_distance_open_high  : excitement / distance_open_high  
    excitement_distance_open_low   : excitement / distance_open_low  
    excitement_distance_close_high : excitement / distance_close_high  
    excitement_distance_close_low  : excitement / distance_close_low  

Property  
    first_high_low  : Low | High



<!--------------------------------------------------------------------------------- Link -->
[Economy]: https://github.com/kashanimorteza/economy_document/blob/main/README.md
[Data]: https://github.com/kashanimorteza/economy_document/blob/main/data.md