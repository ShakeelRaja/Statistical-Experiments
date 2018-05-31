# Statistical-Experiments-
Experimental Design, bias in experiments, randomly controlled trials; beginning with the null hypothesis, and then going to alternative

In this lesson, we will introduce the basic ideas of experimental design. Let's start by introducing a few terms which will be explained in detail during the course of this module. 

### Experimental Design or Design of Experiments (DoE)

An **Experiment** is defined as a structured and efficient approach which employs statistical techniques  under controlled conditions, in order to discover or illustrate an unknown **Effect**, in order to test or establish a **Hypothesis**. 
When analyzing processes, experiments are often used to evaluate which process inputs have a **significant impact** on the process output, and what **Target Levels** of those inputs should be to achieve a desired output. Experiments can be designed in many different ways to collect this information. The terms *“Experimental Design”* or *“Design of Experiments”* are used interchangeably and mean the same thing. However, the medical and social sciences tend to use the term “Experimental Design” while engineering, industrial and computer sciences favor the term “Design of experiments”.

Today experimenral design ideas are used extensively towards **Industrial Process Optimization** , **Medicine**, **Social Sciences** . Experimental design is the corner stone of **A/B testing**, which is one of the main tasks of many data scientists today.

The elements of an experimental design are the **Experimental Units**, **Treatments** and **Factors** that are assigned to these units. The key objective of an experimental design is always to compaere different treatments e.g. for clinical trials around testing the effect of different drugs on patients, "patients" are the experimental units and "drugs" is the treatment. Similarly, in agricultural experiments, the plots in fields are experimental units, and different pesticides, fertilizers could be seen as treatments. The goal in all such experiments is to investigate potentially significant treatments/factors and determine their cause-and-effect relationship on the outcome of an experiment. 

## Treatment
In experiments, a treatment is something that researchers administer to experimental units. For example, a corn field is divided into four, each part is 'treated' with a different fertiliser to see which produces the most corn; a teacher practices different teaching methods on different groups to see which yields the best results; a doctor treats a patient with a skin condition with different creams to see which is most effective. Treatments are administered to experimental units by 'level', where level implies amount or magnitude. For example, if the experimental units were given 5mg, 10mg, 15mg of a medication, those amounts would be three levels of the treatment. 

## Factor
A factor of an experiment is a controlled independent variable; a variable whose levels are set by the experimenter.
A factor is a general type or category of treatments. Different treatments constitute different levels of a factor. For example, three different groups of runners are subjected to different training methods. The runners are the experimental units, the training methods, the treatments, where the three types of training methods constitute three levels of the factor 'type of training'. 





Any experimental design uses three basic principles i.e. **Replication, Local Control** and **Randomization**

### Randomization 
The first principle of an experimental design is randomization, which is a process of randomly assigning treatments to the experimental units. Randomization is an essential essential requirements in almost all statistical analyses. A random process implies that all possible applications of treatments have the same probability. An experimental unit can be thought of as the smallest division of the experimental material, and a treatment as an experimental condition whose effect is to be measured and analyzed. The purpose of randomization is to remove bias and other sources of extraneous variation which are not controllable. Another advantage of randomization (accompanied by replication, gven below) is that it provides basis of any valid statistical test. Hence, the treatments must be assigned at random to the experimental units. 

### Replication 
The next principle of an experimental design is replication, which deals with repetition of the basic experiment. In other words, it provides a wider set of all the treatments to be tested in the given experiment. During design of experiments, some kind of variation is always introduced to cater for the fact that the experimental units such as individuals or plots of land in agricultural experiments can never be physically identical. This type of variation can be removed by using a number of experimental units. The experiment is therefore performed a number of times i.e. repeating/replicating the basic experiment. An individual repetition is called a **Replicate**. Attributes of replicates depend upon the nature of the experimental material and knowledge of the experiment domain. A replication is used to:

(i) Calculate an accurate estimate of the **Experimental Error**, which represents *the differences that would be observed if the same treatments were applied several times to the same experimental units*.

(ii) Decrease the experimental error to increase **Precision** of the results, which is a measure of the variability of the experimental error.

(iii) Obtain a more precise estimate of the mean effect of a treatment. 

If same treatments are assigned to different experimental units *without replication*, it would be impossible to get an idea about natural variability in the units and measurement error.  It allows the experimenter to make causal inferences about the relationship between independent variables and a dependent variable.

### Local Control
It must be noted that all extraneous sources of variation are not removed by randomization and replication, requiring further refinement of the experimental technique. A design must be chosen in such a manner that all extraneous sources of variation are brought under control. Local control is a term which refers to the amount of **Balancing, Blocking** and **Grouping** of the experimental units. 

**Balancing** allows treatments to be assigned to the experimental units in such a way that the result is a balanced arrangement of the treatments. 

**Blocking** allows collection of similar experimental units to form a relatively **Homogeneous** group.
> A data set is homogeneous if it is made up of things (i.e. people, cells or traits) that are similar to each other.
A block is also a replicate. The main idea behind local control is to increase the efficiency of an experimental design by decreasing the Experimental Error. 

It allows the experimenter to rule out alternative explanations due to the confounding effects of extraneous variables (i.e., variables other than the independent variables).

