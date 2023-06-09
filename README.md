# weatherdebugged
✧.* dsa project 3 by *the system breakers* :-) ✧.*

col: [@emeckley](https://github.com/emeckley) and [@LysandraBW](https://github.com/LysandraBW)

`·˚ ༘₊· ͟͟͞͞꒰➳ ABOUT OUR PROJECT:`

`Problem:` With the changing climate, finding an area with weather patterns well-suited to a person can be a challenge. We want to design a program that suggests areas for users to live based on their preferred climate and displays those suggestions in an intuitive, easily understood manner.

`Motivation:` For people planning on moving (e.g. students pursuing internships, choosing graduate schools, choosing jobs), climate plays a subtle but important role. Living in an area that’s not suited for you weather-wise can be utterly miserable. This program is intended to draw attention to that consideration and offer useful suggestions to that effect.

`Features:` Our project features a clean, intuitive graphic interface where the user can input their preferences about temperature, humidity, amount of rainfall, type of climate, and which way the temperature is trending based on “historical data” (for the purposes of our randomly-generated dataset, this historical data is represented by a boolean value for “warmer” and “cooler”). The user can also input their preference for Quicksort or Radix Sort. The cities are then displayed with their stats, sorted according to how closely they match the user’s preferences. The website also includes an “About Me” page which introduces our team.

`Data:` We used randomly generated data which, for each city, was comprised of the following: latitude, longitude, minimum and maximum temperature, minimum and maximum rainfall, minimum and maximum humidity, temperature trend (i.e. warmer or cooler, simulating the analysis of historical data), climate (one of five different options common in the U.S.).

`Tools:` We used C++ for the back-end work (storing and sorting the data). For the front-end, we used Flask (written in Python) as a “micro web framework”. Furthermore, we also used HTML, CSS, JavaScript, and a library called jQuery. 

`Algorithms Implemented:` We implemented Quicksort and Radix Sort using vectors of City objects (City being a simple struct which had all the data members described in the “Data” section).

`ꕥ FUTURE OPTIMIZATION:`
<br>
In the future, we'd like to focus on lining up our yellow-men more accurately according to our data and communication with the back-end files. Attached is an image which was also clearly seen in our presentation, so we've decided to add this as one of our future goals for the project. 

![image](https://user-images.githubusercontent.com/81883243/235051249-f6bd32bd-71e7-43b7-8f61-2a95ebd1bc8e.png)
