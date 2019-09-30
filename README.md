# CrowdWSA2019
Crowdsourced Word Sequence Aggregation 2019

Data and code for "A Dataset of Crowdsourced Word Sequences: Collections and Answer Aggregation for Ground Truth Creation" by Jiyi Li and Fumiyo Fukumoto, EMNLP-IJCNLP 2019 Workshop of AnnoNLP (Aggregating and analysing crowdsourced annotations for NLP)

# data format:

*_label_anonymous.tsv: the crowdsourced word sequence data. We anonymize the worker ids used on the crowdsourcing platform.
[worker \t sentence \t worker_answer]

*_gt.tsv: the original sentences (true answer) in the target language, for evaluation of the answer aggregation methods.
[sentence \t true_answer]

## Citation (To Appear)
    
	@inproceedings{CrowdWSA2019,
		title = "A Dataset of Crowdsourced Word Sequences: Collections and Answer Aggregation for Ground Truth Creation",
		author = "Jiyi Li and Fumiyo Fukumoto",
		booktitle = "Proceedings of the 2019 {EMNLP} Workshop {A}nno{NLP}: Aggregating and analysing crowdsourced annotations for {NLP}",
		month = nov,
		year = "2019",
		address = "Hongkong, China",
		publisher = "Association for Computational Linguistics",
    }


## License
Creative Commons CC BY 4.0
