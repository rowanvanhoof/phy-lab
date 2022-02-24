# Lab 5/6 Resistors in Series and Parallel

Assumptions:


## Uncertainty:
Since we made the assumption that our DC power supply and that the LabQuest mini recording interface is accurate, we do not have any systematic uncertainties.
Values recorded from different methods (python, logger pro, fluke meter, and the resistor color codes) all fall within a range of 1-2 ohms of each other. Of the uncertainties displayed, those calculated by python and logger pro were much smaller than the fluke meter or color code predictions. Overall, the python uncertainties are the tightest and most trustworthy.

## Results Analysis:
Based on the formula to calculate resistance in series, we expected our 2 resistors in series and our 3 resistors to be 61 ohms (10 + 51) and 129 ohms (10 + 51 + 68) respectively. With our mathmatical model based on the fluke meter, we found these values to be 61 and 128.2 with uncertainties of .224 and .374 ohms. We found similar values with python (60.26 +/- .05688 and 126.4 +/- .00324) and logger pro (60.26 +/- .028 and 126.4 +/- .0237),  with this we can conclude that the theoretical model for resistance in series is accurate. As seen by the data displayed to the right, we can come to the same conclusion for our theoretical model to calculate resistance in paralell. 

## Future recommendations:
Test the available resistors with the fluke meter and choose whatever is the most accurate. Additionally, utilize the Logger Pro dataset and page options, since this experiment has several similar runs. 