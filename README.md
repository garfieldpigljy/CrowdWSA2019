# CrowdWSA2019
Crowdsourced Word Sequence Aggregation 2019

Data and code for "A Dataset of Crowdsourced Word Sequences: Collections and Answer Aggregation for Ground Truth Creation" by Jiyi Li and Fumiyo Fukumoto, EMNLP-IJCNLP 2019 Workshop of AnnoNLP (Aggregating and analysing crowdsourced annotations for NLP)

# Data format

1. *_label_anonymous.tsv: [worker \t sentence \t workeranswer]

the crowdsourced word sequence data. We anonymize the worker ids used on the crowdsourcing platform.

2. *_gt.tsv: [sentence \t trueanswer]

the original sentences (true answer) in the target language, for evaluation of the answer aggregation methods.

3. *_jp_en.tsv: [sentence \t sentence_in_source_language_Japanese \t sentence_in_target_language_English]

There files are not necessary for the original answer aggregation task which only utilizes the worker answers in target language (English) as the inputs. They are shared for using in other task settings or collecting your own data. 


## Citation

If you use this dataset, please cite any one of the following papers.  

	@inproceedings{CrowdWSA2019,
		title = "A Dataset of Crowdsourced Word Sequences: Collections and Answer Aggregation for Ground Truth Creation",
		author = "Li, Jiyi and Fukumoto, Fumiyo",
		booktitle = "Proceedings of the First Workshop on Aggregating and Analysing Crowdsourced Annotations for NLP (AnnoNLP2019)",
		month = nov,
		year = "2019",
		address = "Hong Kong",
		publisher = "Association for Computational Linguistics",
		url = "https://www.aclweb.org/anthology/D19-5904",
		doi = "10.18653/v1/D19-5904",
		pages = "24--28"
	}
	
	@inproceedings{CrowdHRRASA,
		author = {Li, Jiyi},
		title = {Crowdsourced Text Sequence Aggregation Based on Hybrid Reliability and Representation},
		year = {2020},
		isbn = {9781450380164},
		publisher = {Association for Computing Machinery},
		address = {New York, NY, USA},
		url = {https://doi.org/10.1145/3397271.3401239},
		doi = {10.1145/3397271.3401239},
		booktitle = {Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR2020)},
		pages = {1761–1764},
		numpages = {4},
		keywords = {reliability, crowdsourcing, text sequence aggregation},
		location = {Virtual Event, China},
		series = {SIGIR '20}
	}

## Links

[Other Types of Crowdsourcing Data](https://github.com/garfieldpigljy/ljycrowd)

[About Human-LLM Hybrid Answer Aggregation](https://github.com/garfieldpigljy/HumanLLMHybridAggregation)

## License
Creative Commons CC BY 4.0
