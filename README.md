# Investigation-into-the-Popularity-of-Classes-at-UC-Davis

Having taken so many units that I'd have to choose some classes after everyone else, this short, personal project came about from the frustration of not knowing which classes to choose first. Using GET requests, I aim to gather chronological data on the aggregate amount of students registered for a variety of classes, across different majors (during registration period). Currently, this project has been halted due to its personal lack of necessity (as well as the expected length of time gathering data in order to get accurate results). 

However, in the code, I gather and reformat the class data into a csv which was initially intended to predict the popularity of a class given the:

- Season (if the first class of a series is only available in fall, it's likely students will take the next class in that series in winter)
- Grade (understanding that certain grade levels can register on certain days, we can infer when and by-who a class is most likely to get registered for)
- Professor (with RateMyProfessor as the primary site for students to gather data on a professor, it's likely that some students choose not to / to register for a class based on the professor)
- Other classes (given that most students take 12-15 units, the presence of "more desirable" classes would lead to other classes being chosen less)

Currently, I don't have enough data for clear inference. Furthermore, one fault of this project is I don't have a server to automatically update the code (though I've looked into the Amazon Cloud Computing services). Thus, in order to gather information, I need to re-open the code. Lastly, I also need to manually update the GET requests in order to get accurate information (specifically on the quarter, year, etc). If completed though, this project could even be used to predict whether or not a student should stay on the waitlist.

Nonetheless, the summaries proved useful to me in understanding which classes tend to be in high demand: whether it was a major class, minor class, or GE.
