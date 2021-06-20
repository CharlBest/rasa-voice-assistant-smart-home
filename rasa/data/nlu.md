## intent:light_switch
- turn [on](action) the [light](device)
- turn [on](action) the [light](device) in the [bedroom](room)
- [light](device) [on](action)
- switch the [light](device) [on](action)
- switch [on](action) my [light](device) 
- can you turn [on](action) the [light](device)?
- could you turn [off](action) the [light](device)
- i would like the [light](device) [off](action)
- the [light](device) needs to be [off](action)
- turn [off](action) the [kitchen](room) [lights](device)
- turn [off](action) all the [lights](device)
- turn [on](action) the [tv](device)

## intent:light_dim
- dim the [light](device) to [20%](dim_percentage) in the [bedroom](room)
- dim my [lights](device) to [50%](dim_percentage)
- dim [light](device) to [20%](dim_percentage)

## intent:light_color
- turn the [light](device) [red](color) in the [bedroom](room)
- turn the [light](device) to color [blue](color)
- change the [light](device) color to [blue](color)

## intent:color
- [red](color)
- [blue](color)
- [yellow](color)
- [black](color)
- [white](color)

## intent:room
- [bedroom](room)
- [living room](room)
- [bathroom](room)
- [kitchen](room)

## intent:climate_temperature
- what is the temperature?
- what is the temperature in the [bedroom](room)?
- how warm is it?
- how cold is it?
- temperature?
- how many degrees is it in here?

## intent:climate_humidity
- what is the humidity?
- what is the humidity in the [bedroom](room)?
- humidity?

## intent:weather
- what is the weather?
- what is the temperature outside?

## intent:alarm_create
- set an alarm for [7:30PM](alarm_time)
- set an alarm for [every](alarm_repeat) [monday](alarm_day) at [18:00](alarm_time)
- set an alarm for [next week](alarm_repeat) [tuesday](alarm_day) at [10:00AM](alarm_time)
- create alarm for [monday](alarm_day) [18:00](alarm_time) called [wake up](alarm_name)
- create alarm called [sleep time](alarm_name) at [18:00](alarm_time) [every](alarm_repeat) [monday](alarm_day)

## intent:alarm_day
- monday
- tuesday
- wednesday
- thursday
- friday
- saturday
- sunday
- today
- tomorrow
- day after tomorrow

## intent:alarm_read
- show me all my alarms
- what time is my [morning](alarm_name) alarm
- give me my alarms

## intent:alarm_update
- change my [01:55](alarm_time) alarm to [04:30](alarm_time_second)
- change [bedtime](alarm_name) alarm to [04:20PM](alarm_time)
- change my [06:55](alarm_time) alarm to repeat [next week](alarm_repeat)
- change my [07:55](alarm_time) alarm to repeat [next week](alarm_repeat) [tuesday](alarm_day)
- change alram called [bedtime](alarm_name) to [19:55](alarm_time) [every](alarm_repeat) [sunday](alarm_day)

## intent:alarm_delete
- delete [bedtime](alarm_name) alarm
- remove [01:55PM](alarm_time)

## intent:broadcast
- broadcast [some text](broadcast_text)

## intent:bot_challenge
- are you a bot?
- are you a human?
- am I talking to a bot?
- am I talking to a human?