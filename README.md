*Collecting and labeling training samples starting from
unlabeled data is a long and tedious task, as it requires
great manual human effort. Moreover, collecting training
samples that cover all possible target classes for training
a classifier is an arduous labour, potentially even impossible in case some of those classes are yet to discover. Fulfill
both tasks at the same time can be indeed more burdensome
or even unfeasible to do. We propose to ’aid’ humans to
solve this composite problem with a simple but yet efficacious method. To address the first problem we use a SemiSupervised Learning approach inspired by Domain Adaptation and Data Augmentation. To deal with the second (a.k.a.
Open Set Recognition) problem we use attribute-inference
to generate new labels for the out-of-set samples, starting
from the known in-set samples. We demonstrate how these
two approaches can be directly merged into a single one and
into a single Deep Neural Network as well. We also show
that, despite the simplicity and the plug-and-play nature of
the method, the performances are satisfactory and the results are credible and reasonable*

![Results](/results.jpg)

The code is also available at my colleague's repository https://github.com/danieleleto94/AID
