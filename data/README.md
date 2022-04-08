# Data Sources and Structure

## Links

* Bolukbasi et al.: [nondebiased](https://code.google.com/archive/p/word2vec/), [debiased](https://github.com/tolga-b/debiaswe).
* Zhao et al.: [nondebiased](https://drive.google.com/file/d/1jrbQmpB5ZNH4w54yujeAvNFAfVEG0SuE/view), [debiased](https://github.com/uclanlp/gn_glove)
* [Webster](https://github.com/google-research-datasets/gap-coreference)
* [Manzini](https://github.com/TManzini/DebiasMulticlassWordEmbedding)
## Directory Structure

data
├── Bolukbasi
│	├── hard_debiased_w2v-002.npy
│	├── hard_debiased_w2v.vocab
│	├── orig_w2v.vocab
│	└── orig_w2v.wv-001.npy
├── Manzini
│	├── data_gender_attributes_optm_json_role_softDebiasedEmbeddingsOut.w2v
│	├── data_race_attributes_optm_json_role_softDebiasedEmbeddingsOut.w2v
│	├── data_religion_attributes_optm_json_attribute_softDebiasedEmbeddingsOut.w2v
│	├── data_vocab_gender_attributes_optm_json_role_hardDebiasedEmbeddingsOut.w2v
│	├── data_vocab_race_attributes_optm_json_role_hardDebiasedEmbeddingsOut.w2v
│	├── data_vocab_religion_attributes_optm_json_attribute_hardDebiasedEmbeddingsOut.w2v
│	├── reddit.US.txt.tok.clean.cleanedforw2v_0.w2v
│	├── reddit.US.txt.tok.clean.cleanedforw2v_1.w2v
│	├── reddit.US.txt.tok.clean.cleanedforw2v_2.w2v
│	├── reddit.US.txt.tok.clean.cleanedforw2v_3.w2v
│	└── reddit.US.txt.tok.clean.cleanedforw2v_4.w2v
├── Webster
│	└── gap-test.tsv
└── Zhao
    ├── gn_glove.vocab
    ├── gn_glove.wv.npy
    ├── orig_glove.vocab
    └── orig_glove.wv.npy