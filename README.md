# Project4-3rdsemester
A final project of the 3rd semester - an embedded "Smart Home" system for reptiles with a website.

This is the code for a "Smart Home for reptiles" prototype which I co-developed. 

The prototype constantly monitors temperature and humidity conditions in an enclosure. On a website, the user can choose which animal he wants to monitor. 
The system is equipped with a library of animals as well as the option for the user to input a custom animal, in case the user's animal is not on the list.

After the animal is selected, the system makes sure its living conditions stay in the specific animal's range. If the temperature is too low, it will turn on a heat lamp. 
Once the temperature is in the correct range, it will keep it there.
If the humidity is too high, the system will turn on a fan.

The current conditions are displayed on a website and the user can manually adjust the range, turn off the automatic control alltogether or see warnings log. 

I was in charge of developing the website for the prototype, establishing communication between Arduino and the website and making sure the system responds to user's actions.

See https://www.youtube.com/watch?v=hjGQXgT-ots&ab_channel=Th%C3%B8gerAbildgaard for a demo. 
