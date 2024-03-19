Labs at the time were completed in Jupyter hub.

This is incomplete

ailab

Networkx


Table of Contents for AI: A Modern Approach
Part I: Artificial Intelligence
Chapter 1: Introduction ... 1

1.1. What Is AI? ... 1
      1.1.1. Acting humanly: The Turing Test approach ... 2
      1.1.2. Thinking humanly: The cognitive modeling approach ... 3
      1.1.3. Thinking rationally: The ``laws of thought'' approach ... 4
      1.1.4. Acting rationally: The rational agent approach ... 4
1.2. The Foundations of Artificial Intelligence ... 5
      1.2.1. Philosophy ... 5
      1.2.2. Mathematics ... 7
      1.2.3. Economics ... 9
      1.2.4. Neuroscience ... 10
      1.2.5. Psychology ... 12
      1.2.6. Computer engineering ... 13
      1.2.7. Control theory and cybernetics ... 15
      1.2.8. Linguistics ... 15
1.3. The History of Artificial Intelligence ... 16
      1.3.1. The gestation of artificial intelligence (1943--1955) ... 16
      1.3.2. The birth of artificial intelligence (1956) ... 17
      1.3.3. Early enthusiasm, great expectations (1952--1969) ... 18
      1.3.4. A dose of reality (1966--1973) ... 20
      1.3.5. Knowledge-based systems: The key to power? (1969--1979) ... 22
      1.3.6. AI becomes an industry (1980--present) ... 24
      1.3.7. The return of neural networks (1986--present) ... 24
      1.3.8. AI adopts the scientific method (1987--present) ... 25
      1.3.9. The emergence of intelligent agents (1995--present) ... 26
      1.3.10. The availability of very large data sets (2001--present) ... 27
1.4. The State of the Art ... 28
1.5. Summary ... 29
Bibliographical and Historical Notes ... 30
Exercises ... 31
Chapter 2: Intelligent Agents ... 34

2.1. Agents and Environments ... 34
2.2. Good Behavior: The Concept of Rationality ... 36
      2.2.1. Rationality ... 37
      2.2.2. Omniscience, learning, and autonomy ... 38
2.3. The Nature of Environments ... 40
      2.3.1. Specifying the task environment ... 40
      2.3.2. Properties of task environments ... 41
2.4. The Structure of Agents ... 46
      2.4.1. Agent programs ... 46
      2.4.2. Simple reflex agents ... 48
      2.4.3. Model-based reflex agents ... 50
      2.4.4. Goal-based agents ... 52
      2.4.5. Utility-based agents ... 53
      2.4.6. Learning agents ... 54
      2.4.7. How the components of agent programs work ... 57
2.5. Summary ... 59
Bibliographical and Historical Notes ... 59
Exercises ... 61
Part II: Problem-solving
Chapter 3: Solving Problems by Searching ... 64

3.1. Problem-Solving Agents ... 64
      3.1.1. Well-defined problems and solutions ... 66
      3.1.2. Formulating problems ... 68
3.2. Example Problems ... 69
      3.2.1. Toy problems ... 70
      3.2.2. Real-world problems ... 73
3.3. Searching for Solutions ... 75
      3.3.1. Infrastructure for search algorithms ... 78
      3.3.2. Measuring problem-solving performance ... 80
3.4. Uninformed Search Strategies ... 81
      3.4.1. Breadth-first search ... 81
      3.4.2. Uniform-cost search ... 83
      3.4.3. Depth-first search ... 85
      3.4.4. Depth-limited search ... 87
      3.4.5. Iterative deepening depth-first search ... 88
      3.4.6. Bidirectional search ... 90
      3.4.7. Comparing uninformed search strategies ... 91
3.5. Informed (Heuristic) Search Strategies ... 92
      3.5.1. Greedy best-first search ... 92
      3.5.2. A* search: Minimizing the total estimated solution cost ... 93
             Conditions for optimality: Admissibility and consistency ... 94
             Optimality of A* ... 95
      3.5.3. Memory-bounded heuristic search ... 99
      3.5.4. Learning to search better ... 102
3.6. Heuristic Functions ... 102
      3.6.1. The effect of heuristic accuracy on performance ... 103
      3.6.2. Generating admissible heuristics from relaxed problems ... 104
      3.6.3. Generating admissible heuristics from subproblems: Pattern databases ... 106
      3.6.4. Learning heuristics from experience ... 107
3.7. Summary ... 108
Bibliographical and Historical Notes ... 109
Exercises ... 112
Chapter 4: Beyond Classical Search ... 120

4.1. Local Search Algorithms and Optimization Problems ... 120
      4.1.1. Hill-climbing search ... 122
      4.1.2. Simulated annealing ... 125
      4.1.3. Local beam search ... 125
      4.1.4. Genetic algorithms ... 126
4.2. Local Search in Continuous Spaces ... 129
4.3. Searching with Nondeterministic Actions ... 133
      4.3.1. The erratic vacuum world ... 133
      4.3.2 AND-OR search trees ... 135
      4.3.3. Try, try again ... 137
4.4. Searching with Partial Observations ... 138
      4.4.1. Searching with no observation ... 138
      4.4.2. Searching with observations ... 142
      4.4.3. Solving partially observable problems ... 143
      4.4.4. An agent for partially observable environments ... 144
4.5. Online Search Agents and Unknown Environments ... 147
      4.5.1. Online search problems ... 147
      4.5.2. Online search agents ... 149
      4.5.3. Online local search ... 150
      4.5.4. Learning in online search ... 153
4.6. Summary ... 153
Bibliographical and Historical Notes ... 154
Exercises ... 157
Chapter 5: Adversarial Search ... 161

5.1. Games ... 161
5.2. Optimal Decisions in Games ... 163
      5.2.1. The minimax algorithm ... 165
      5.2.2. Optimal decisions in multiplayer games ... 165
5.3. Alpha--Beta Pruning ... 167
      5.3.1. Move ordering ... 169
5.4. Imperfect Real-Time Decisions ... 171
      5.4.1. Evaluation functions ... 171
      5.4.2. Cutting off search ... 173
      5.4.3. Forward pruning ... 174
      5.4.4. Search versus lookup ... 176
5.5. Stochastic Games ... 177
      5.5.1. Evaluation functions for games of chance ... 178
5.6. Partially Observable Games ... 180
      5.6.1. Kriegspiel: Partially observable chess ... 180
      5.6.2. Card games ... 183
5.7. State-of-the-Art Game Programs ... 185
5.8. Alternative Approaches ... 187
5.9. Summary ... 189
Bibliographical and Historical Notes ... 190
Exercises ... 195
Chapter 6: Constraint Satisfaction Problems ... 202

6.1. Defining Constraint Satisfaction Problems ... 202
      6.1.1. Example problem: Map coloring ... 203
      6.1.2. Example problem: Job-shop scheduling ... 204
      6.1.3. Variations on the CSP formalism ... 205
6.2. Constraint Propagation: Inference in CSPs ... 208
      6.2.1. Node consistency ... 208
      6.2.2. Arc consistency ... 208
      6.2.3. Path consistency ... 210
      6.2.4. K-consistency. ... 211
      6.2.5. Global constraints ... 211
      6.2.6. Sudoku example ... 212
6.3. Backtracking Search for CSPs ... 214
      6.3.1. Variable and value ordering ... 216
      6.3.2. Interleaving search and inference ... 217
      6.3.3. Intelligent backtracking: Looking backward ... 218
6.4. Local Search for CSPs ... 220
6.5. The Structure of Problems ... 222
6.6. Summary ... 227
Bibliographical and Historical Notes ... 227
Exercises ... 230
Part III: Knowledge, reasoning, and planning
Chapter 7: Logical Agents ... 234

7.1. Knowledge-Based Agents ... 235
7.2. The Wumpus World ... 236
7.3. Logic ... 240
7.4. Propositional Logic: A Very Simple Logic ... 243
      7.4.1. Syntax ... 244
      7.4.2. Semantics ... 245
      7.4.3. A simple knowledge base ... 246
      7.4.4. A simple inference procedure ... 247
7.5. Propositional Theorem Proving ... 249
      7.5.1. Inference and proofs ... 250
      7.5.2. Proof by resolution ... 252
             Conjunctive normal form ... 253
             A resolution algorithm ... 254
             Completeness of resolution ... 255
      7.5.3. Horn clauses and definite clauses ... 256
      7.5.4. Forward and backward chaining ... 257
7.6. Effective Propositional Model Checking ... 259
      7.6.1. A complete backtracking algorithm ... 260
      7.6.2. Local search algorithms ... 262
      7.6.3. The landscape of random SAT problems ... 263
7.7. Agents Based on Propositional Logic ... 265
      7.7.1. The current state of the world ... 265
      7.7.2. A hybrid agent ... 268
      7.7.3. Logical state estimation ... 269
      7.7.4. Making plans by propositional inference ... 271
7.8. Summary ... 274
Bibliographical and Historical Notes ... 275
Exercises ... 279
Chapter 8: First-Order Logic ... 285

8.1. Representation Revisited ... 285
      8.1.1. The language of thought ... 286
      8.1.2. Combining the best of formal and natural languages ... 288
8.2. Syntax and Semantics of First-Order Logic ... 290
      8.2.1. Models for first-order logic ... 290
      8.2.2. Symbols and interpretations ... 292
      8.2.3. Terms ... 294
      8.2.4. Atomic sentences ... 294
      8.2.5. Complex sentences ... 295
      8.2.6. Quantifiers ... 295
             Universal quantification (∀) ... 295
             Existential quantification (∃) ... 297
             Nested quantifiers ... 297
             Connections between ∀ and ∃ ... 298
      8.2.7. Equality ... 299
      8.2.8. An alternative semantics? ... 299
8.3. Using First-Order Logic ... 300
      8.3.1. Assertions and queries in first-order logic ... 301
      8.3.2. The kinship domain ... 301
      8.3.3. Numbers, sets, and lists ... 303
      8.3.4. The wumpus world ... 305
8.4. Knowledge Engineering in First-Order Logic ... 307
      8.4.1. The knowledge-engineering process ... 307
      8.4.2. The electronic circuits domain ... 309
             Identify the task ... 309
             Assemble the relevant knowledge ... 309
             Decide on a vocabulary ... 310
             Encode general knowledge of the domain ... 310
             Encode the specific problem instance ... 311
             Pose queries to the inference procedure ... 312
             Debug the knowledge base ... 312
8.5. Summary ... 313
Bibliographical and Historical Notes ... 313
Exercises ... 315
Chapter 9: Inference in First-Order Logic ... 322

9.1. Propositional vs. First-Order Inference ... 322
      9.1.1. Inference rules for quantifiers ... 322
      9.1.2. Reduction to propositional inference ... 324
9.2. Unification and Lifting ... 325
      9.2.1. A first-order inference rule ... 325
      9.2.2. Unification ... 326
      9.2.3. Storage and retrieval ... 327
9.3. Forward Chaining ... 330
      9.3.1. First-order definite clauses ... 330
      9.3.2. A simple forward-chaining algorithm ... 331
      9.3.3. Efficient forward chaining ... 333
             Matching rules against known facts ... 333
             Incremental forward chaining ... 335
             Irrelevant facts ... 336
9.4. Backward Chaining ... 337
      9.4.1. A backward-chaining algorithm ... 337
      9.4.2. Logic programming ... 339
      9.4.3. Efficient implementation of logic programs ... 340
      9.4.4. Redundant inference and infinite loops ... 342
      9.4.5. Database semantics of Prolog ... 343
      9.4.6. Constraint logic programming ... 344
9.5. Resolution ... 345
      9.5.1. Conjunctive normal form for first-order logic ... 345
      9.5.2. The resolution inference rule ... 347
      9.5.3. Example proofs ... 347
      9.5.4. Completeness of resolution ... 350
      9.5.5. Equality ... 353
      9.5.6. Resolution strategies ... 355
             Practical uses of resolution theorem provers ... 356
9.6. Summary ... 357
Bibliographical and Historical Notes ... 357
Exercises ... 360
Chapter 10: Classical Planning ... 366

10.1. Definition of Classical Planning ... 366
      10.1.1. Example: Air cargo transport ... 369
      10.1.2. Example: The spare tire problem ... 370
      10.1.3. Example: The blocks world ... 370
      10.1.4. The complexity of classical planning ... 372
10.2. Algorithms for Planning as State-Space Search ... 373
      10.2.1. Forward (progression) state-space search ... 373
      10.2.2. Backward (regression) relevant-states search ... 374
      10.2.3. Heuristics for planning ... 376
10.3. Planning Graphs ... 379
      10.3.1. Planning graphs for heuristic estimation ... 381
      10.3.2. The Graphplan algorithm ... 383
      10.3.3. Termination of Graphplan ... 385
10.4. Other Classical Planning Approaches ... 387
      10.4.1. Classical planning as Boolean satisfiability ... 387
      10.4.2. Planning as first-order logical deduction: Situation calculus ... 388
      10.4.3. Planning as constraint satisfaction ... 390
      10.4.4. Planning as refinement of partially ordered plans ... 390
10.5. Analysis of Planning Approaches ... 392
10.6. Summary ... 393
Bibliographical and Historical Notes ... 393
Exercises ... 396
Chapter 11: Planning and Acting in the Real World ... 401

11.1. Time, Schedules, and Resources ... 401
      11.1.1. Representing temporal and resource constraints ... 402
      11.1.2. Solving scheduling problems ... 403
11.2. Hierarchical Planning ... 406
      11.2.1. High-level actions ... 406
      11.2.2. Searching for primitive solutions ... 408
      11.2.3. Searching for abstract solutions ... 410
11.3. Planning and Acting in Nondeterministic Domains ... 415
      11.3.1. Sensorless planning ... 417
      11.3.2. Contingent planning ... 421
      11.3.3. Online replanning ... 422
11.4. Multiagent Planning ... 425
      11.4.1. Planning with multiple simultaneous actions ... 426
      11.4.2. Planning with multiple agents: Cooperation and coordination ... 428
11.5. Summary ... 430
Bibliographical and Historical Notes ... 431
Exercises ... 435
Chapter 12: Knowledge Representation ... 437

12.1. Ontological Engineering ... 437
12.2. Categories and Objects ... 440
      12.2.1. Physical composition ... 441
      12.2.2. Measurements ... 444
      12.2.3. Objects: Things and stuff ... 445
12.3. Events ... 446
      12.3.1. Processes ... 447
      12.3.2. Time intervals ... 448
      12.3.3. Fluents and objects ... 449
12.4. Mental Events and Mental Objects ... 450
12.5. Reasoning Systems for Categories ... 453
      12.5.1. Semantic networks ... 454
      12.5.2. Description logics ... 456
12.6. Reasoning with Default Information ... 458
      12.6.1. Circumscription and default logic ... 458
      12.6.2. Truth maintenance systems ... 460
12.7. The Internet Shopping World ... 462
      12.7.1. Following links ... 464
      12.7.2. Comparing offers ... 466
12.8. Summary ... 467
Bibliographical and Historical Notes ... 468
Exercises ... 473
Part IV: Uncertain knowledge and reasoning
Chapter 13: Quantifying Uncertainty ... 480

13.1. Acting under Uncertainty ... 480
      13.1.1. Summarizing uncertainty ... 481
      13.1.2. Uncertainty and rational decisions ... 482
13.2. Basic Probability Notation ... 483
      13.2.1. What probabilities are about ... 484
      13.2.2. The language of propositions in probability assertions ... 486
      13.2.3. Probability axioms and their reasonableness ... 488
13.3. Inference Using Full Joint Distributions ... 490
13.4. Independence ... 494
13.5. Bayes' Rule and Its Use ... 495
      13.5.1. Applying Bayes' rule: The simple case ... 496
      13.5.2. Using Bayes' rule: Combining evidence ... 497
13.6. The Wumpus World Revisited ... 499
13.7. Summary ... 503
Bibliographical and Historical Notes ... 503
Exercises ... 506
Chapter 14: Probabilistic Reasoning ... 510

14.1. Representing Knowledge in an Uncertain Domain ... 510
14.2. The Semantics of Bayesian Networks ... 513
      14.2.1. Representing the full joint distribution ... 513
             A method for constructing Bayesian networks ... 514
             Compactness and node ordering ... 515
      14.2.2. Conditional independence relations in Bayesian networks ... 517
14.3. Efficient Representation of Conditional Distributions ... 518
             Bayesian nets with continuous variables ... 519
14.4. Exact Inference in Bayesian Networks ... 522
      14.4.1. Inference by enumeration ... 523
      14.4.2. The variable elimination algorithm ... 524
             Operations on factors ... 526
             Variable ordering and variable relevance ... 527
      14.4.3. The complexity of exact inference ... 528
      14.4.4. Clustering algorithms ... 529
14.5. Approximate Inference in Bayesian Networks ... 530
      14.5.1. Direct sampling methods ... 530
             Rejection sampling in Bayesian networks ... 532
             Likelihood weighting ... 532
      14.5.2. Inference by Markov chain simulation ... 535
             Gibbs sampling in Bayesian networks ... 536
             Why Gibbs sampling works ... 536
14.6. Relational and First-Order Probability Models ... 539
      14.6.1. Possible worlds ... 540
      14.6.2. Relational probability models ... 542
      14.6.3. Open-universe probability models ... 544
14.7. Other Approaches to Uncertain Reasoning ... 546
      14.7.1. Rule-based methods for uncertain reasoning ... 547
      14.7.2. Representing ignorance: Dempster--Shafer theory ... 549
      14.7.3. Representing vagueness: Fuzzy sets and fuzzy logic ... 550
14.8. Summary ... 551
Bibliographical and Historical Notes ... 552
Exercises ... 558
Chapter 15: Probabilistic Reasoning over Time ... 566

15.1. Time and Uncertainty ... 566
      15.1.1. States and observations ... 567
      15.1.2. Transition and sensor models ... 568
15.2. Inference in Temporal Models ... 570
      15.2.1. Filtering and prediction ... 571
      15.2.2. Smoothing ... 574
      15.2.3. Finding the most likely sequence ... 576
15.3. Hidden Markov Models ... 578
      15.3.1. Simplified matrix algorithms ... 579
      15.3.2. Hidden Markov model example: Localization ... 581
15.4. Kalman Filters ... 584
      15.4.1. Updating Gaussian distributions ... 584
      15.4.2. A simple one-dimensional example ... 585
      15.4.3. The general case ... 587
      15.4.4. Applicability of Kalman filtering ... 588
15.5. Dynamic Bayesian Networks ... 590
      15.5.1. Constructing DBNs ... 591
      15.5.2. Exact inference in DBNs ... 595
      15.5.3. Approximate inference in DBNs ... 596
15.6. Keeping Track of Many Objects ... 599
15.7. Summary ... 603
Bibliographical and Historical Notes ... 603
Exercises ... 606
Chapter 16: Making Simple Decisions ... 610

16.1. Combining Beliefs and Desires under Uncertainty ... 610
16.2. The Basis of Utility Theory ... 611
      16.2.1. Constraints on rational preferences ... 612
      16.2.2. Preferences lead to utility ... 613
16.3. Utility Functions ... 615
      16.3.1. Utility assessment and utility scales ... 615
      16.3.2. The utility of money ... 616
      16.3.3. Expected utility and post-decision disappointment ... 618
      16.3.4. Human judgment and irrationality ... 619
16.4. Multiattribute Utility Functions ... 622
      16.4.1. Dominance ... 622
      16.4.2. Preference structure and multiattribute utility ... 624
             Preferences without uncertainty ... 624
             Preferences with uncertainty ... 625
16.5. Decision Networks ... 626
      16.5.1. Representing a decision problem with a decision network ... 626
      16.5.2. Evaluating decision networks ... 628
16.6. The Value of Information ... 628
      16.6.1. A simple example ... 629
      16.6.2. A general formula for perfect information ... 630
      16.6.3. Properties of the value of information ... 631
      16.6.4. Implementation of an information-gathering agent ... 632
16.7. Decision-Theoretic Expert Systems ... 633
16.8. Summary ... 636
Bibliographical and Historical Notes ... 636
Exercises ... 640
Chapter 17: Making Complex Decisions ... 645

17.1. Sequential Decision Problems ... 645
      17.1.1. Utilities over time ... 648
      17.1.2. Optimal policies and the utilities of states ... 650
17.2. Value Iteration ... 652
      17.2.1. The Bellman equation for utilities ... 652
      17.2.2. The value iteration algorithm ... 652
      17.2.3. Convergence of value iteration ... 654
17.3. Policy Iteration ... 656
17.4. Partially Observable MDPs ... 658
      17.4.1. Definition of POMDPs ... 658
      17.4.2. Value iteration for POMDPs ... 660
      17.4.3. Online agents for POMDPs ... 664
17.5. Decisions with Multiple Agents: Game Theory ... 666
      17.5.1. Single-move games ... 667
      17.5.2. Repeated games ... 673
      17.5.3. Sequential games ... 674
17.6. Mechanism Design ... 679
      17.6.1. Auctions ... 679
      17.6.2. Common goods ... 683
17.7. Summary ... 684
Bibliographical and Historical Notes ... 685
Exercises ... 688
Part V: Learning
Chapter 18: Learning from Examples ... 693

18.1. Forms of Learning ... 693
             Components to be learned ... 694
             Representation and prior knowledge ... 694
             Feedback to learn from ... 694
18.2. Supervised Learning ... 695
18.3. Learning Decision Trees ... 697
      18.3.1. The decision tree representation ... 698
      18.3.2. Expressiveness of decision trees ... 698
      18.3.3. Inducing decision trees from examples ... 699
      18.3.4. Choosing attribute tests ... 703
      18.3.5. Generalization and overfitting ... 705
      18.3.6. Broadening the applicability of decision trees ... 706
18.4. Evaluating and Choosing the Best Hypothesis ... 708
      18.4.1. Model selection: Complexity versus goodness of fit ... 709
      18.4.2. From error rates to loss ... 710
      18.4.3. Regularization ... 712
18.5. The Theory of Learning ... 713
      18.5.1. PAC learning example: Learning decision lists ... 715
18.6. Regression and Classification with Linear Models ... 717
      18.6.1. Univariate linear regression ... 718
      18.6.2. Multivariate linear regression ... 720
      18.6.3. Linear classifiers with a hard threshold ... 723
      18.6.4. Linear classification with logistic regression ... 725
18.7. Artificial Neural Networks ... 727
      18.7.1. Neural network structures ... 728
      18.7.2. Single-layer feed-forward neural networks (perceptrons) ... 729
      18.7.3. Multilayer feed-forward neural networks ... 731
      18.7.4. Learning in multilayer networks ... 733
      18.7.5. Learning neural network structures ... 736
18.8. Nonparametric Models ... 737
      18.8.1. Nearest neighbor models ... 738
      18.8.2. Finding nearest neighbors with k-d trees ... 739
      18.8.3. Locality-sensitive hashing ... 740
      18.8.4. Nonparametric regression ... 741
18.9. Support Vector Machines ... 744
18.10. Ensemble Learning ... 748
      18.10.1. Online Learning ... 752
18.11. Practical Machine Learning ... 753
      18.11.1. Case study: Handwritten digit recognition ... 753
      18.11.2. Case study: Word senses and house prices ... 755
18.12. Summary ... 757
Bibliographical and Historical Notes ... 758
Exercises ... 763
Chapter 19: Knowledge in Learning ... 768

19.1. A Logical Formulation of Learning ... 768
      19.1.1. Examples and hypotheses ... 768
      19.1.2. Current-best-hypothesis search ... 770
      19.1.3. Least-commitment search ... 773
19.2. Knowledge in Learning ... 777
      19.2.1. Some simple examples ... 778
      19.2.2. Some general schemes ... 778
19.3. Explanation-Based Learning ... 780
      19.3.1. Extracting general rules from examples ... 781
      19.3.2. Improving efficiency ... 783
19.4. Learning Using Relevance Information ... 784
      19.4.1. Determining the hypothesis space ... 785
      19.4.2. Learning and using relevance information ... 785
19.5. Inductive Logic Programming ... 788
      19.5.1. An example ... 788
      19.5.2. Top-down inductive learning methods ... 791
      19.5.3. Inductive learning with inverse deduction ... 794
      19.5.4. Making discoveries with inductive logic programming ... 796
19.6. Summary ... 797
Bibliographical and Historical Notes ... 798
Exercises ... 801
Chapter 20: Learning Probabilistic Models ... 802

20.1. Statistical Learning ... 802
20.2. Learning with Complete Data ... 806
      20.2.1. Maximum-likelihood parameter learning: Discrete models ... 806
      20.2.2. Naive Bayes models ... 808
      20.2.3. Maximum-likelihood parameter learning: Continuous models ... 809
      20.2.4. Bayesian parameter learning ... 810
      20.2.5. Learning Bayes net structures ... 813
      20.2.6. Density estimation with nonparametric models ... 814
20.3. Learning with Hidden Variables: The EM Algorithm ... 816
      20.3.1. Unsupervised clustering: Learning mixtures of Gaussians ... 817
      20.3.2. Learning Bayesian networks with hidden variables ... 820
      20.3.3. Learning hidden Markov models ... 822
      20.3.4. The general form of the EM algorithm ... 823
      20.3.5. Learning Bayes net structures with hidden variables ... 824
20.4. Summary ... 825
Bibliographical and Historical Notes ... 825
Exercises ... 827
Chapter 21: Reinforcement Learning ... 830

21.1. Introduction ... 830
21.2. Passive Reinforcement Learning ... 832
      21.2.1. Direct utility estimation ... 833
      21.2.2. Adaptive dynamic programming ... 834
      21.2.3. Temporal-difference learning ... 836
21.3. Active Reinforcement Learning ... 839
      21.3.1. Exploration ... 839
      21.3.2. Learning an action-utility function ... 842
21.4. Generalization in Reinforcement Learning ... 845
21.5. Policy Search ... 848
21.6. Applications of Reinforcement Learning ... 850
      21.6.1. Applications to game playing ... 850
      21.6.2. Application to robot control ... 851
21.7. Summary ... 853
Bibliographical and Historical Notes ... 854
Exercises ... 858
Part VI: Communicating, perceiving, and acting
Chapter 22: Natural Language Processing ... 860

22.1. Language Models ... 860
      22.1.1 N-gram character models ... 861
      22.1.2. Smoothing n-gram models ... 862
      22.1.3. Model evaluation ... 863
      22.1.4 N-gram word models ... 864
22.2. Text Classification ... 865
      22.2.1. Classification by data compression ... 866
22.3. Information Retrieval ... 867
      22.3.1. IR scoring functions ... 868
      22.3.2. IR system evaluation ... 869
      22.3.3. IR refinements ... 869
      22.3.4. The PageRank algorithm ... 870
      22.3.5. The HITS algorithm ... 872
      22.3.6. Question answering ... 872
22.4. Information Extraction ... 873
      22.4.1. Finite-state automata for information extraction ... 874
      22.4.2. Probabilistic models for information extraction ... 876
      22.4.3. Conditional random fields for information extraction ... 878
      22.4.4. Ontology extraction from large corpora ... 879
      22.4.5. Automated template construction ... 880
      22.4.6. Machine reading ... 881
22.5. Summary ... 882
Bibliographical and Historical Notes ... 883
Exercises ... 885
Chapter 23: Natural Language for Communication ... 888

23.1. Phrase Structure Grammars ... 888
      23.1.1. The lexicon of E0 ... 890
      23.1.2. The Grammar of E0 ... 890
23.2. Syntactic Analysis (Parsing) ... 892
      23.2.1. Learning probabilities for PCFGs ... 895
      23.2.2. Comparing context-free and Markov models ... 896
23.3. Augmented Grammars and Semantic Interpretation ... 897
      23.3.1. Lexicalized PCFGs ... 897
      23.3.2. Formal definition of augmented grammar rules ... 898
      23.3.3. Case agreement and subject--verb agreement ... 899
      23.3.4. Semantic interpretation ... 900
      23.3.5. Complications ... 902
23.4. Machine Translation ... 907
      23.4.1. Machine translation systems ... 908
      23.4.2. Statistical machine translation ... 909
23.5. Speech Recognition ... 912
      23.5.1. Acoustic model ... 914
      23.5.2. Language model ... 917
      23.5.3. Building a speech recognizer ... 917
23.6. Summary ... 918
Bibliographical and Historical Notes ... 919
Exercises ... 923
Chapter 24: Perception ... 928

24.1. Image Formation ... 929
      24.1.1. Images without lenses: The pinhole camera ... 929
      24.1.2. Lens systems ... 931
      24.1.3. Scaled orthographic projection ... 932
      24.1.4. Light and shading ... 932
      24.1.5. Color ... 935
24.2. Early Image-Processing Operations ... 935
      24.2.1. Edge detection ... 936
      24.2.2. Texture ... 939
      24.2.3. Optical flow ... 939
      24.2.4. Segmentation of images ... 941
24.3. Object Recognition by Appearance ... 942
      24.3.1. Complex appearance and pattern elements ... 944
      24.3.2. Pedestrian detection with HOG features ... 945
24.4. Reconstructing the 3D World ... 947
      24.4.1. Motion parallax ... 948
      24.4.2. Binocular stereopsis ... 949
      24.4.3. Multiple views ... 951
      24.4.4. Texture ... 951
      24.4.5. Shading ... 952
      24.4.6. Contour ... 953
      24.4.7. Objects and the geometric structure of scenes ... 954
24.5. Object Recognition from Structural Information ... 957
      24.5.1. The geometry of bodies: Finding arms and legs ... 958
      24.5.2. Coherent appearance: Tracking people in video ... 959
24.6. Using Vision ... 961
      24.6.1. Words and pictures ... 962
      24.6.2. Reconstruction from many views ... 962
      24.6.3. Using vision for controlling movement ... 963
24.7. Summary ... 965
Bibliographical and Historical Notes ... 966
Exercises ... 969
Chapter 25: Robotics ... 971

25.1. Introduction ... 971
25.2. Robot Hardware ... 973
      25.2.1. Sensors ... 973
      25.2.2. Effectors ... 975
25.3. Robotic Perception ... 978
      25.3.1. Localization and mapping ... 979
      25.3.2. Other types of perception ... 984
      25.3.3. Machine learning in robot perception ... 985
25.4. Planning to Move ... 986
      25.4.1. Configuration space ... 986
      25.4.2. Cell decomposition methods ... 989
      25.4.3. Modified cost functions ... 991
      25.4.4. Skeletonization methods ... 991
25.5. Planning Uncertain Movements ... 993
      25.5.1. Robust methods ... 994
25.6. Moving ... 997
      25.6.1. Dynamics and control ... 997
      25.6.2. Potential-field control ... 999
      25.6.3. Reactive control ... 1001
      25.6.4. Reinforcement learning control ... 1002
25.7. Robotic Software Architectures ... 1003
      25.7.1. Subsumption architecture ... 1003
      25.7.2. Three-layer architecture ... 1004
      25.7.3. Pipeline architecture ... 1005
25.8. Application Domains ... 1006
25.9. Summary ... 1010
Bibliographical and Historical Notes ... 1011
Exercises ... 1014
Part VII: Conclusions
Chapter 26: Philosophical Foundations ... 1020

26.1. Weak AI: Can Machines Act Intelligently? ... 1020
      26.1.1. The argument from disability ... 1021
      26.1.2. The mathematical objection ... 1022
      26.1.3. The argument from informality ... 1024
26.2. Strong AI: Can Machines Really Think? ... 1026
      26.2.1. Mental states and the brain in a vat ... 1028
      26.2.2. Functionalism and the brain replacement experiment ... 1029
      26.2.3. Biological naturalism and the Chinese Room ... 1031
      26.2.4. Consciousness, qualia, and the explanatory gap ... 1033
26.3. The Ethics and Risks of Developing Artificial Intelligence ... 1034
26.4. Summary ... 1040
Bibliographical and Historical Notes ... 1040
Exercises ... 1043
Chapter 27: AI: The Present and Future ... 1044

27.1. Agent Components ... 1044
27.2. Agent Architectures ... 1047
27.3. Are We Going in the Right Direction? ... 1049
27.4. What If AI Does Succeed? ... 1051
Chapter A: Mathematical background ... 1053

A.1. Complexity Analysis and O() Notation ... 1053
      A.1.1. Asymptotic analysis ... 1053
      A.1.2. NP and inherently hard problems ... 1054
A.2. Vectors, Matrices, and Linear Algebra ... 1055
A.3. Probability Distributions ... 1057
Bibliographical and Historical Notes ... 1059
Chapter B: Notes on Languages and Algorithms ... 1060
