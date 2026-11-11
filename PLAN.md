**Resources**
1) Open-meteo
https://open-meteo.com/en/docs/gfs-api

2) honeywell thermostat api
https://developer.honeywellhome.com/api-methods?%3B%3Bamp%3Bamp%3Bmocguem3akddqt2mdibyyewvoa=55rvct35ef6xy2hfmawfin57ou&%3Bfield_smart_method_tags_tid=56&field_smart_method_tags_tid=39

3) LLM 
https://console.groq.com/docs/api-reference#chat
- Going to use Qwen 3.8 27b

**Schedule**
NIGHTS 
weekdays: 8PM-5AM: 58F
weekends: 10PM-7AM: 58F

DAYS
Sunday-Monday: 7AM-8PM: 68F
Tuesday-Friday: 6AM-7AM: 68F, 7AM-4PM: 58F, 4PM-8PM: 68F 


**Script Logic**

DAY 1 
- Just automate the thermostats based on the schedule defined

- I want this to be an MCP that ties in AI for logic regarding advice on what to do to lower the electricity bill as much as possible
based on weather and forecasted weather. The base schedule is a start but it's a bit too old-school.
-data_collector.rs collects the data that I want from the weather and honeywell api


**Database Logic**
- need to find a small, lightweight database.
- the purpose of the database will be 
