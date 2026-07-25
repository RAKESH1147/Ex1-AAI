<H3> Name Rakesh K S </H3>
<H3>Register No. 212224040264</H3>
<H3> Experiment 1</H3>
<H3>DATE: 25/07/2026</H3>
<H1 ALIGN=CENTER> Implementation of Bayesian Networks</H1>
## Aim :
    To create a bayesian Network for the given dataset in Python
## Algorithm:
Step 1:Import necessary libraries: pandas, networkx, matplotlib.pyplot, Bbn, Edge, EdgeType, BbnNode, Variable, EvidenceBuilder, InferenceController<br/>
Step 2:Set pandas options to display more columns<br/>
Step 3:Read in weather data from a CSV file using pandas<br/>
Step 4:Remove records where the target variable RainTomorrow has missing values<br/>
Step 5:Fill in missing values in other columns with the column mean<br/>
Step 6:Create bands for variables that will be used in the model (Humidity9amCat, Humidity3pmCat, and WindGustSpeedCat)<br/>
Step 7:Define a function to calculate probability distributions, which go into the Bayesian Belief Network (BBN)<br/>
Step 8:Create BbnNode objects for Humidity9amCat, Humidity3pmCat, WindGustSpeedCat, and RainTomorrow, using the probs() function to calculate their probabilities<br/>
Step 9:Create a Bbn object and add the BbnNode objects to it, along with edges between the nodes<br/>
Step 10:Convert the BBN to a join tree using the InferenceController<br/>
Step 11:Set node positions for the graph<br/>
Step 12:Set options for the graph appearance<br/>
Step 13:Generate the graph using networkx<br/>
Step 14:Update margins and display the graph using matplotlib.pyplot<br/>

## Program:
''' Type your Code here '''
## Output:
<img width="788" height="557" alt="image" src="https://github.com/user-attachments/assets/be233b26-159f-495c-b739-2f4cb4607895" />
<img width="803" height="562" alt="image" src="https://github.com/user-attachments/assets/16345d07-3693-42b4-9484-3b0ff2269020" />
<img width="756" height="301" alt="image" src="https://github.com/user-attachments/assets/9f02537a-afed-44be-9675-a0f010739f75" />
<img width="907" height="667" alt="image" src="https://github.com/user-attachments/assets/8a1d7432-8ac9-4a85-ba09-3619aca729a5" />
<img width="1752" height="145" alt="image" src="https://github.com/user-attachments/assets/11ff661e-6f0c-4410-928f-e8207c2d2723" />






## Result:
   Thus a Bayesian Network is generated using Python

