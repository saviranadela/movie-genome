# Movie Genome Analysis


## Dataset  

This project uses the **[MovieLens Tag Genome 2021 dataset](https://grouplens.org/datasets/movielens/tag-genome-2021/)** published by [GroupLens](https://grouplens.org/). The dataset is derived from earlier work on tag relevance prediction by [Vig et al., 2012](https://dl.acm.org/doi/abs/10.1145/2362394.2362395) and [Kotkov et al., 2021](https://doi.org/10.1145/3404835.3463019).  

The Tag Genome dataset provides **movie–tag pair scores**, which indicate how strongly a tag applies to a given movie. To generate these scores, the original authors combined metadata (title, directors, actors), reviews from [IMDb](https://imdb.com/), [MovieLens](https://movielens.org/) ratings and tags, and user survey judgements about tag relevance.  

- [Vig et al., 2012] applied regression models for prediction.  
- [Kotkov et al., 2021] introduced **TagDL**, a neural network–based approach using the same features.  

GroupLens processed and released this dataset version in 2021. While it differs slightly from the datasets used in the original publications, experimental results based on this release closely match those reported in the papers.  

## License  

The dataset is distributed under the **[Creative Commons Attribution-NonCommercial 3.0 License](https://creativecommons.org/licenses/by-nc/3.0/)**.  

If you use this dataset, please cite:  

- Kotkov, D., Maslov, A., & Neovius, M. (2021). *[Revisiting the tag relevance prediction problem](https://doi.org/10.1145/3404835.3463019)*. In *Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval*.  
- Vig, J., Sen, S., & Riedl, J. (2012). *[The tag genome: Encoding community knowledge to support novel interaction](https://dl.acm.org/doi/abs/10.1145/2362394.2362395)*. *ACM Transactions on Interactive Intelligent Systems, 2*(3), 13:1–13:44.  

