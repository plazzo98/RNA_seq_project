# RNA_seq_project
RNA - Seq Data Analysis of the Gene Expression Profiles of IFN - β and IFN - γ - Conditioned Human Macrophages


The project examines the effect of Interferon gamma (IFN - γ) and Interferon beta (IFN - β) on the expression profiles of non - activated (naive) human
macrophages, with the goal of highlighting the cellular processes impacted by each of these chemical mediators. After data normalization and filtering, 
the presence of latent structures or patterns in the data was investigated with a set of unsupervised learning methods, which failed to discriminate between
some of the groups considered. After a feature selection step, performed using a t - test and employed to select the genes displaying a singificative difference
in the expression levels across the three groups considered, the ability of a set of supervised classification methods to correctly distinguish between naive
and conditioned samples was tested: all the techniques considered showed 100% accuracy. Finally, functional and network - based analyses were performed: a 
significant overlap was detected between the cellular processes impacted by each interferon. The R Markdown code is provided, and the results of the analysis are
discussed in a PDF report file.
