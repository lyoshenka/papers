*These are papers that I wrote or participated in during my undergrad cognitive science research.*

### Vector Generation of an Explicitly-defined Multidimensional Semantic Space

[PDF](https://github.com/lyoshenka/papers/raw/master/grintsvayg07iccm.pdf)

Measures of Semantic Relatedness (MSRs) are a recent breed of computational models of text comprehension. MSRs have been successfully used to model human web browsing behavior, language acquisition, and text comprehension, among other things. MSRs have also been used in the applied domain for augmented search engine technology, ETS essay grading, and many other applications. 

In this paper we propose a new MSR called VGEM that combines the best features of probabilistic and vector-based approaches, while adding flexibility and broadening the range of tasks that MSRs are capable of carrying out. Specifically, this technique allows non-vector-based MSRs to represent words in vector form. Preliminary results show that this conversion produces a measure that surpasses the performance of the original.

*Grintsvayg, A., Veksler, V. D., Lindsey, R., & Gray, W. D. (2007). Vector Generation from an Explicitly-defined Multidimensional Space. Proceedings of the 8th International Conference on Cognitive Modeling, Ann Arbor, MI.*

### A Proxy For All Your Semantic Needs

[PDF](https://github.com/lyoshenka/papers/raw/master/a-proxy-for-all-your-semantic-needs.pdf)

Measures of Semantic Relatedness (MSRs) are computational means for assessing the relative meaning of terms. More specifically, MSRs take the form of computer programs that can extract relatedness between any two terms based on large text corpora. Among the many contributions of MSRs are cognitive modeling applications, augmented search engine technology, and essay grading algorithms used by ETS. Here we introduce an ongoing effort to centralize and unify MSR technology – a publicly available MSR Web Server

*Veksler, V. D., Grintsvayg, A., Lindsey, R., & Gray, W. D. (2007). A proxy for all your semantic needs. Proceedings of the 29th Annual Meeting of the Cognitive Science Society, Nashville, TN.*

### Be Wary of What Your Computer Reads: The Effects of Corpus Selection on Measuring Semantic Relatedness

[PDF](https://github.com/lyoshenka/papers/raw/master/LindVeksGrintGray07_ICCM-libre.pdf)

Measures of Semantic Relatedness (MSRs) provide models of human semantic associations and, as such, have been applied to predict human text comprehension. In addition, MSRs form key components in more integrated cognitive modeling such as models that perform information search on the World Wide Web (WWW). However, the effectiveness of an MSR depends on the algorithm it uses as well as the text corpus on which it is trained. In this paper, we examine the impact of corpus selection on the performance of two popular MSRs, Pointwise Mutual Information and Normalised Google Distance. We tested these measures with corpora derived from the WWW, books, news articles, emails, web-forums, and encyclopedia. Results indicate that for the tested MSRs, the traditionally employed books and WWW-based corpora are less than optimal, and that using a corpus based on the New York Times news articles best predicts human behavior.

*Lindsey, R., Veksler, V. D., Grintsvayg, A., & Gray, W. D. (2007). Effects of Corpus Selection on Measuring Semantic Relatedness. Proceedings of the 8th International Conference on Cognitive Modeling, Ann Arbor, MI.*

### Cognitive Modeling of Web Search

[PDF](https://github.com/lyoshenka/papers/raw/master/SGVGG06_ACTR.pdf)

A significant challenge for computational cognitive modeling is to develop high-fidelity models of web surfing. To successfully model the entire task both software and cognitive engineering problems must be solved. At ACT-R-2005, we addressed some of the software engineering challenges posed by the task of attaching an ACT-R model to a web browser (Gamard, Schoelles, Kofila, Veksler, & Gray, 2005). In this talk we focus on the cognitive engineering challenges posed by the need to navigate and search a near infinite number of heterogeneously designed web pages in pursuit of a weakly specified target.

*Schoelles, M. J., Gray, W. D., Veksler, V. D., Gamard, S., & Grintsvayg, A. (2006, July). Cognitive modeling of web search. Paper presented at the 13th Annual ACT-R Workshop, Carnegie Mellon University, Pittsburgh, PA.*


---

*Related, by Dan, Ryan and Wayne:*

### Defining the Dimensions of the Human Semantic Space

[PDF](https://github.com/lyoshenka/papers/raw/master/pp718-veksler.pdf)

We describe VGEM, a technique for converting probability-based measures of semantic relatedness (e.g. Normalized Google Distance, Pointwise Mutual Information) into a vector-based form to allow these measures to evaluate relatedness of multi-word terms (documents, paragraphs). We use a genetic algorithm to derive a set of 300 dimensions to represent the human semantic space. With the resulting dimension sets, VGEM matches or outperforms the probability-based measure, while adding the multi-word term functionality. We test VGEM's performance on multi-word terms against Latent Semantic Analysis and find no significant difference between the two measures. We conclude that VGEM is more useful than probability-based measures because it affords better performance, and provides relatedness between multi-word terms; and that VGEM is more useful than other vector-based measures because it is more computationally feasible for large, dynamic corpora (e.g. WWW), and thus affords a larger, dynamic lexicon.
