# Ocean Protocol :: Storage Network Energy Consumption Data Challenge

## Files description

- README.md - task and files description.
- REPORT.md - solution description.
- REPORT.pdf - solution description (pdf version).
- data/ - folder with input data.
- pictures/ - folder with the pictures for solution description.
- startup.py - initial script that executed in every notebook when started.
- 1_Global_analysis_Correlations.ipynb - script with the global analysis and calculating correlations (first, second parts).
- 2_Modelling.ipynb - script with the modelling part.

---
## Task description

### Details

Storage network energy consumption is a global issue. Being energy-intensive, the data center industry accounts for around 4% of global electricity consumption and 1% of global greenhouse gas emissions. IT infrastructure operators need to adapt to the increasing growth in digital transactions resulting in challenging demands on energy supplies. There is a continuous need to develop more data storage and management capacity, where the volume of stored data in 2025 is expected to be 5.3 times more than in 2018.

To keep pace with the growth in IT activity, major digital operators have been implementing ambitious plans aimed at achieving carbon neutrality. As a decentralized storage network aiming to use 100% renewable energy, Filecoin aspires to empower other storage providers to meet a new standard for localized, clean energy usage and reporting, using Web3.

Filecoin Green is a Protocol Labs initiative to make Filecoin verifiably sustainable while building the world's best tools to measure and reduce environmental impacts. The initiative is spearheading a future of Web3 powered by verifiably clean energy.


### Challenge

In the challenge you are asked to perform four types of tasks: 
- (1) make a global analysis; 
- (2) determine a level of correlation;
- (3) write a prediction algorithm;
- (4) create a report that summarizes your findings from the first three tasks.

### Global analysis - What interesting insights can you derive? (20 points):
1. Analyze the energy performance and the evolution of Filecoin's storage (10 pts)
2. Analyze the evolution of the share of renewable energy used by Filecoin (10 pts)

### Correlation (20 points):
1. Determine the correlation between the energy used to seal the Filecoin data and the price of its FIL token (5 pts)
2. Determine the correlation between the capacity of storage added per day in the Filecoin network and the price of its FIL token (5pts)
3. Determine the correlation between the energy consumption rate of the Filecoin network and its FIL token price (5 pts)
4. What observations can you deduce from these 3 correlations? (5 pts)

### Algorithm (35 points):
Build an algorithm to predict the storage capacity added per day for the month of December  2022 (you can use any datasets to help you as long as you publish them on Ocean Market).

### Report (25 points):
Submit a report describing the above findings. Make sure to include qualitative insights in addition to the quantitative ones. Reports will be evaluated on presentation structure, approach, content, and completeness.

### Bonus (25 points):
Find a dataset on the energy consumption of conventional data center storage and publish it on the Ocean Market. Then, compare the energy performance of Filecoin storage to that of conventional data centers. What can you conclude?


