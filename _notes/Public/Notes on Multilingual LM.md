1. **Language Specific Neurons**
	1. setting: pre-trained foundation models; wikipedia parallel corpus
	2. Hypothesis: only specific neurons are activated when processing certain languages
		![[Screenshot 2025-01-24 at 10.33.43.png]]
	3. Method: $$
		\text{LAPE}_{i,j} = -\sum_{k=1}^{l} p'^{k}_{i,j} \log(p'^{k}_{i,j}).$$
	4. Baselines:
		1. Substitute entropy with values
		2. Substitute prob with mean values, then calculate entropy
		3. Compare before-after parameters of fine-tuning on single language, select neurons with great changes when fine-tuned on some languages and little changes on others.