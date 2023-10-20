# Admin-It-L2

Admin-It is a parallel corpus of **sentences in Italian administrative language** aimed at Italian L2 speakers for Automatic Readability Assessment (ARA) and Automatic Text Simplification (ATS). The corpus comprises **134 original-simplified sentence pairs**.

We manually simplified 134 sentences by focusing on the linguistic traits that emerged from a comprehension test conducted over 86 participants (Miliani et al., 2022a), involving also Italian L2 speakers (30,2\%).

Admin-It-L2 counts **134 pairs of sentences** extracted from the texts used in this study (34 sentences) and from Admin-It RS} (100 sentences), a subsection of [Admin-It](https://github.com/Unipisa/admin-It), a parallel corpus of Italian administrative texts (Miliani et al., 2022b). All these sentences were manually simplified based on the linguistic traits of the administrative language. Then, they were further manipulated to produce a simplification close to the needs of Italian L2 speakers.

In the ```.txt```  file, each row contains three sentences divided by a ```\tab``` separator: the original sentence, the one obtained by the first simplification and the sentence were the simplification is tailored for Italian L2 speakers.

### References

* Miliani, M., Senaldi, M. S., Lebani, G. E., & Lenci, A. (2022). [Understanding Italian Administrative Texts: A Reader-Oriented Study for Readability Assessment and Text Simplification](https://ceur-ws.org/Vol-3285/paper5.pdf). In Proceedings of the 1st Workshop on AI for Public Administration (AIxPA), November 28-December 2, 2022, Udine, Italy.
* Miliani, M., Auriemma, S., Alva-Manchego, F., & Lenci, A. (2022, November). [Neural readability pairwise ranking for sentences in Italian administrative language](https://aclanthology.org/2022.aacl-main.63/). In Proceedings of the 2nd Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics and the 12th International Joint Conference on Natural Language Processing (pp. 849-866).

### Limitations

The validation of the simplification through an evaluation that involves human annotators, i.e., domain experts and Italian L2 speakers, is planned for future work.


### Citation

If you use Admin-It-L2 in your research, please cite our paper:

> Martina Miliani, Fernando Alva-Manchego and Alessandro Lenci. 2023. Simplifying Administrative Texts for Italian L2 Readers with Controllable Transformers Models: A Data-driven Approach. In *Proceedings of CLiC-it 2023: 9th Italian Conference on Computational Linguistics, Nov 30 — Dec 02, 2023, Venice, Italy* (Accepted)
