# Large-scale coin die studies with artificial intelligence
The STUDIES project is an [ANR funded project](https://anr.fr/Project-ANR-23-CE38-0014).

In the domain of numismatics and ancient economy, there is a long expressed and large expectation to estimate the volumes of produced coinage. Study of coin-finds and hoards not being reliable, die studies are the best way to understand the mint outputs and therefore the relation of coinage to Politics and History. The die study consists in comparing each coin of a series to define the number of engraved tools that were used to strike coins. For large series, it is humanly impossible.
In the project STUDIES, we propose to rely on recent advances in data harvesting, computer vision and deep learning to automatically estimate the similarity between coins, in order to simplify the die studies. Based on a full matrix of similarity, one can then identify clusters, each being a plausible candidate for a unique die. It will thus be possible to conduct die studies at a much larger scale, one to two orders of magnitude more than the largest studies to date.

## Results
We proposed an initial tool to automatically estimate the similarity between coins and conduct automatic die studies from existing collections. We propose a fully automatic approach that introduces several innovations compared to previous methods. We rely on fast and robust local descriptors matching that is set automatically. Second, the core of our proposal is a clustering-based approach that uses an intrinsic metric (that does not need the ground truth labels) to determine its critical hyper-parameters. We validate the approach on two corpora of Greek coins, propose an automatic implementation and evaluation of previous baselines, and show that our approach significantly outperforms them. 

**References**: 
* Clément Cornet, Héloïse Aumaître, Romaric Besançon, Julien olivier, Thomas Faucher, Hervé Le Borgne, **Automatic Die Studies for Ancient Numismatics**, *3rd International Workshop on Artificial Intelligence for Digital Humanities* ([AI4DH@ECCV](https://sites.google.com/view/ai4dh2024)), Milan, Italy, 2024 <br/>[<img style="width:30px;" src="../../docs/logo_pdf.png"/>](https://arxiv.org/abs/2407.20876) [<img style="width:30px;" src="../../docs/logo_github.png"/>](https://github.com/ClementCornet/Auto-Die-Studies) 



