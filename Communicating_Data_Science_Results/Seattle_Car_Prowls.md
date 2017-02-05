
# Car Prowls Trouble Seattle Nights

While the assumption that more crimes are committed at night than during the day seems self-evident, I want to analyze the prevalence of car prowls by time of day. Car prowls are the most common reported incident (at least according to the "Seattle Summer 2014" dataset) &mdash; with nearly twice the number of reported incidents as the runner-up, property incidents.

To analyze the distribution of car prowls by time of day, I've grouped the reported incidents by their occurrence date, aggregating the incidents into 2-hour periods so the resulting statistics is easier to interpret. For every 2-hour period of the time of the day, I've then computed the average number of reported incidents over all days, as well as the average number of reported car prowls.


![png](Seattle_Car_Prowls_files/Seattle_Car_Prowls_2_0.png)


Looking at these figures, one can see that the average number of reported offenses is at its lowest in the early morning, i.e., between 4:00 and 6:00. It then increases until 12:00, and remains at an average of 35&ndash;45 reported offenses until midnight, when it starts to go down again quite drastically.

The average number of reported car prowls seems to follow a similar pattern, though given that car prowls are only one of many different types of offenses, the first figure does not allow to assess whether the average number of car prowls might exhibit a different pattern than the average number of all offenses. Thus the second figure shows the number of car prowls as a _percentage_ of all reported offenses. From this figure, one can see that the share of car prowls in all offenses is larger in the evening and at night&mdash;i.e., between 18:00 and 6:00&mdash;than during the day, although the difference is not that pronounced. The peak that can be observed between 4:00 and 6:00 is probably an artifact, as the average number of offenses is at a minimum during that time of the day (cf. first figure), and small variations in the number of reported car prowls vs. all other offenses will therefore cause large variations in the car prowl percentage.

To be able to asses how car prowl prevalence varies during the day, the third figure below depicts the percentage of car prowls committed during the various times of the day. One can clearly see that many more car prowls occurr at night (between 18:00 and 0:00), and that the fewest car prowls are committed in the (early) morning, between 4:00 and 8:00.


![png](Seattle_Car_Prowls_files/Seattle_Car_Prowls_4_0.png)


It is also interesting to note that car prowl prevalence only starts increasing after 16:00, whereas the overall number of offenses has already peaks between 12:00 and 14:00. This indicates that other offenses dominate the early afternoon, which is confirmed by the low car prowl share for that time of the day, see figure two.
