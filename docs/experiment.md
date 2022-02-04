# Experiments

* Download [experiment](tool/experiment.zip) to do experiments.
* The four directories ```random```, ```skillexplorer```, ```user```, ```vitas``` show the communication logs obtained by random testing, Skillexplorer, manually testing and Vitas respectively. 
* ```experiment.py``` contains the scripts to get figure 5 to figure 9 in paper.
* Excel files save the raw data of figure 5 to figure 9 in paper.

## Figure 5

Figure 5 shows the comparison of state coverage with random testing. Skills that can be opened normally and have consistent behavior are selected in ```fig5_coverage_Vitas_vs_random.xlsx```. To get the state coverage achieved by Vitas and random testing, run: 

	python experiment.py 5

The result will be shown in ```fig5_coverage_Vitas_vs_random.xlsx```.

## Figure 6

Figure 6 shows the comparison of state coverage with Skillexplorer. Skills that can be opened normally and have consistent behavior are selected in ```fig6_coverage_Vitas_vs_Skillexplorer.xlsx```. To get the state coverage achieved by Vitas and Skillexplorer, run: 

	python experiment.py 6

The result will be shown in ```fig6_coverage_Vitas_vs_Skillexplorer.xlsx```.

## Figure 7

Figure 7 shows the average state coverage achieved by manually testing, Vitas, random testing, and Skillexplorer.  Skills that can be opened normally and have consistent behavior are selected in ```fig7_coverage_rate_four.xlsx```. To get the state coverage achieved by these four techniques and the union of them, run:

	python experiment.py 7

The result will be shown in ```fig7_coverage_rate_four.xlsx```.

## Figure 8

Figure 8 shows the number of interaction rounds required to achieve a certain percentage of the state-space between Vitas and context-enhanced random testing. We only select those skills whose final sizes of state-space obtained by two techniques are within -10%-10% in the comparison,  can be opened normally and have consistent behavior. They are shown in ```fig8_coverage_round_Vitas_vs_random.xlsx```. To get the interaction rounds, run:

	python experiment.py 8

The result will be shown in ```fig8_coverage_round_Vitas_vs_random.xlsx```. Sheet 'Vitas' and sheet 'random' shows the interaction rounds required by Vitas and random testing respectively.

## Figure 9

Figure 9 shows the number of interaction rounds required to achieve a certain percentage of the state-space between Vitas and Skillexplorer. We only select those skills whose final sizes of state-space obtained by two techniques are within -10%-10% in the comparison,  can be opened normally and have consistent behavior. They are shown in ```fig9_coverage_round_Vitas_vs_Skillexplorer.xlsx```. To get the interaction rounds, run:

	python experiment.py 9

The result will be shown in ```fig9_coverage_round_Vitas_vs_Skillexplorer.xlsx```. Sheet 'Vitas' and sheet 'Skillexplorer' shows the interaction rounds required by Vitas and Skillexplorer respectively.
