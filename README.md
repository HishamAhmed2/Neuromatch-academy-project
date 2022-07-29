# Neuromatch-academy-project
<br/> This project was done during Neuromatch academy computational neuroscience summer school by Brass Rattlesnake pod entitled "History Choice Dependence". 
we build a logistic regression model to predict response time (Fast/Slow) of mice in a reward-based learning task
## Data
<br/> Data from Steinmetz et al, 2019. The mouse is surrounded by three computer screens and the mouse has a wheel that he can turn left or right and a tube through which a drop of water is given to him when he answers correctly and there was two stimulus location on each of right and left screen and stimulus could be on one, the other, both or neither screen. 
if the stimulus was higher contrast on the right he should turn the wheel counterclockwise and if the stimulus was higher contrast on the left 
he should turn the wheel clockwise and if the stimulus was equal on both sides he had to stay still for 1.5 second and visual 
stimulus move on the screen as he moves the wheel and his goal is to bring the high contrast visual stimulus to the screen in the center. 
Time bins for all measurements are 10ms, starting 500ms before stimulus onset.
## Results
<br/> The mouse took a long time (>0.7sec) when his feedback type in the previous trial were 57% "No Reward". while the mouse took a short time(<0.7sec) when his feedback 
type in the previous trials were 90% "Reward"
## Limitations and speculations
<br/> We used only one session for one mouse which resulted in little and insufficient data.
