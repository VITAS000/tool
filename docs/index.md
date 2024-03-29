# Vitas: VUI Testing of VPA Apps

Vitas is a model-based framework to handle VUI testing of VPA apps. Vitas interacts with the app VUI, and during the testing process, it retrieves semantic information from voice feedbacks by natural language processing. It incrementally constructs the finite state machine (FSM) model of the app with a weighted exploration strategy guided by key factors such as the coverage of app functionality.

## Files Tree

```text
├── README.md
├── code
│   ├── main.py
│   ├── Step1_parseWeb.py
│   ├── Step2_1_GetDocuRetrvComd.py
│   ├── Step2_2_TF_IDF.py
│   ├── Step3_1_InputAndResponse.py
│   ├── Step3_2_GetCommands.py
│   ├── Step3_3_ProblemDetection.py
│   └── Step3_Communication.py
├── corpus
│   ├── 19 files make up the corpus for TF-IDF
├── skill_data_set_2021
│   ├── BenchMark.xlsx
│   ├── 20 excel files related to skills' documents
├── chrome
│   ├── chromedriver
├── config
│   ├── config.ini
└── cookie
```

* code: contains the source code for Vitas
* corpus: contains 19 files used for TF-IDF
* skill_data_set_2021 
  * BenchMark.xlsx: The benchmark mentioned in the paper.
  * other 20 excel files: The large-scaled dataset mentioned in the paper. They are part of skills' documents on the Amazon skills store. The second column "path" shows the origin website, you can refer to the website for more information. The column "comments" are commands provided by the developers, not generated by Vitas or other tools.
* config: contains a config.ini, where you can set your own configurations.

## Requirement

1. Change the ```config.ini``` inside ```config``` directory to add your own account, or you can use the one we provide.
2. We need to login to the amazon developer account to start using the simulator. In most of the cases amazon will send an email to your linked email address for verifications. We use `pop` to read the emails, so make sure the 110 port is open.

## How to run Vitas

1. Enter the ```code``` directory for codes. Use ```python main.py``` to start using Vitas. Vitas will test the skills in ```business_and_finance.xlsx```, save the logs in ```../business/``` directory and the problems in ```../result``` directory by default.

2. Add ```-e + <excel name>``` to change the excel file of skills' document (they are saved in the ```skill_data_set_2021``` directory)
	
	Add ```-l + <path>``` to set a path to store logs.
	
	Add ```-o + <path>``` to save the problem list. 
	
	Use ```-c``` to start using the chatbot, but we recommend not to because the UI of the chatbot is always changing. 
	
	For example, run:
	
	```python main.py -e kids_skill_data_set_1.xlsx -l kids/ -o kids_problem/```
	
	to test ```kids_skill_data_set_1.xlsx``` in the ```skill_data_set_2021``` directory, save the logs in the ```kids``` directory and problems list in the ```kids_problem``` directory.
	
## How to do experiments

See the detailed introduction [here](experiment.md). 

The comparison of coverage between Vitas and its competitors is shown [here](coverage.md).

## Case Study

See the detailed information [here](case.md).

## Download
* [Vitas](tool/VITAS.zip) See the Vitas directory for running Vitas. You can get the problems list of skills in the benchmark and large-scaled dataset.
* [Experiment](tool/experiment.zip) See the detailed introduction [here](experiment.md).
* [Dataset](cases/skill_dataset.zip) The skills' documents are collected in the excel files by different categories.
* [Outputs](outputs/output.zip) The logs and problems list on the benchmark and large-scaled dataset are saved in output directory.