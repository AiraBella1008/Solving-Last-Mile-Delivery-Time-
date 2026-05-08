Solving Last-Mile Delivery Time Uncertainty Through Discrete-Event Queue Simulation  

 
Description
This project simulates the uncertainty of last-mile delivery operations using Python, Monte Carlo simulation, and probability distributions. The program models real-world delivery conditions for courier services such as:
•J&T Express
•Shopee Express
•LBC Express
•Ninja Van
The simulation generates 10,000 delivery scenarios to estimate delivery arrival times, failed delivery attempts, rider travel delays, and time-slot probabilities.
Using histograms and probability charts, the project visualizes how delivery uncertainty behaves in real logistics systems, especially in urban environments such as Manila.


Objectives
1. Simulate realistic last-mile delivery operations using stochastic models.
2. Analyze delivery time uncertainty through Monte Carlo simulation.
3. Visualize probability distributions using histograms and charts.
4. Compare courier performance based on estimated arrival distributions.
5. Predict delivery windows and time-slot probabilities.
6. Apply Discrete-Event Queue Simulation concepts to logistics systems.
7 Demonstrate practical applications of probability distributions in real-world operations.

Features
• Monte Carlo simulation with 10,000 runs
• Histogram visualization for multiple probability distributions
• Composite delivery arrival prediction
• Courier comparison analysis
• Percentile-based delivery estimates (P10, P25, P50, P75, P90)
• Time-slot probability analysis
• Dark-themed professional dashboard
• Automatic image export (last_mile_delivery_histograms.png)
• Error handling for safe figure saving
• Realistic Philippine logistics modeling

Concepts Applied
1. Monte Carlo Simulation
Randomized simulation method used to model uncertain delivery conditions thousands of times.

2. Discrete-Event Queue Simulation
Models the sequence of delivery events such as:
• parcel sorting
• dispatching
• transportation
• failed delivery attempts
• rider routing


3. Probability Distributions
Exponential Distribution
Used for rider inter-arrival times between delivery stops.

Normal Distribution
Used for total delivery pipeline delay.



Poisson Distribution
Used for failed delivery attempts.
 
	
 
Binomial Distribution
Used for delivery success/failure outcomes.

 
Triangular Distribution
Used for rider travel time estimation when exact traffic data is unavailable.

Requirements
Software Requirements
• Python 3.x
• Visual Studio Code (VS Code)

Python Libraries
Install the following libraries before running the program:
• pip install numpy matplotlib

How to Run
Step 1 — Open VS Code
Launch Visual Studio Code.

Step 2 — Create Python File
Create a new file named:
delivery_simulation.py

Step 3 — Copy the Code
Paste the entire simulation code into the file.

Step 4 — Save the File
Press:
Ctrl + S (Windows)
Cmd + S (Mac)

Step 5 — Run the Program
Open the VS Code terminal and run:
•python delivery_simulation.py

Step 6 — View Results
The program will:
display histograms and charts
print delivery summaries in the terminal
save the visualization image automatically as:
• last_mile_delivery_histograms.png

Example Usage
A logistics analyst wants to estimate the probability that a parcel arrives before evening.
The simulation:
• generates 10,000 possible delivery outcomes
• analyzes traffic delays
• models failed delivery attempts
• estimates arrival time probabilities

Example output:
P10 Earliest Likely  : 2:15 PM
P50 Most Likely      : 6:40 PM
P90 Worst Case       : 10:05 PM

Time-slot probability example:
Morning     8.2%
Noon        18.5%
Afternoon   37.1%
Evening     36.2%

Conclusion
This project demonstrates how probability distributions, Monte Carlo simulation, and Discrete-Event Queue Simulation can be used to analyze uncertainty in last-mile delivery systems.
By combining statistical modeling with data visualization, the simulation provides realistic predictions for delivery arrival times and operational delays. The project also highlights how logistics companies can use simulation techniques to:

• improve delivery planning
• optimize rider scheduling
• reduce uncertainty
• enhance customer satisfaction

Overall, the system serves as a practical application of statistics, operations research, and computer simulation in modern e-commerce logistics.
