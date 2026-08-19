Gig Economy Earnings Analysis

Personal project digging into what actually makes gig delivery driving profitable, using a synthesized dataset based off real Uber Eats / DoorDash earnings data.

What this is

Leveraging AI, I built a synthetic dataset of 2,000 driver sessions. Then merged in EPA vehicle fuel economy data, EIA gas prices, insurance costs, and accident risk to get a fuller picture of driver profitability — not just gross pay, but what it actually costs to earn it. From there I ran exploratory analysis to figure out which factors matter most.

The standout result: driver utilization rate — the share of time a driver spends actively working a delivery versus idle — predicts hourly pay better than any other variable I tested, including market, vehicle type, or time of day. That finding is the basis for a ROI calculator I'm building so drivers can see how utilization changes affect their actual take-home pay.

Coming next
SQL section: querying the dataset directly to practice and demonstrate relational data analysis alongside the Python/Pandas work already here.
