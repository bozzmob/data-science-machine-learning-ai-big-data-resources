# Data Science Goals, Components, Processes, and Deliverables - Data Science, Data Mining, Machine Learning, AI, Advanced Analytics, and Big Data

## Data Science, Artificial Intelligence, Statistics, Advanced Analytics, Big Data, and IoT Fields
- Data/text mining and data exploration
- Data/text analytics
- Descriptive, predictive, and descriptive analytics
- Machine learning
- Recommendations
- Real-time stream processing and computing (spot opportunities and risks)
- Pattern Matching
- Forecasting
- Visualization
- Semantic analysis
- Statistical analysis
- Network and cluster analysis
- Multivariate statistics
- Graph analysis
- Simulation
- Optimization
- Experimental design
- Complex event processing
- Autonomous systems
- Smart machines and devices
- Neural networks and deep learning
- Real-time scoring
- Entity analytics
- Business intelligence
- Streaming media analytics
- Cognitive IoT
- Cognitive chatbots
- Embedded deep learning
- Embodied robotic cognition
- Computer vision
- Virtual and augmented reality
- Knowledge management
- Fraud detection

## Typical data science goals
* Derive discoveries, insights, and value from data collections
* Turning data into actions, including real-time
* Build data products providing actionable information while abstracting away technical details, data, and analytics
* Question discovery
* Improving products for user benefit and experience
* Driving business decisions and solutions
* Improving the decisions your business makes
    - Decision science uses data to analyze business metrics — such as growth, engagement, profitability drivers, and user feedback — to inform strategy and key business decisions.
    - Decision science uses data analysis and visualization to inform business and product decisions.
* Automated decision making, predictions, recommendations, and deeper insights
* Inform strategic decisions
* Inform product changes and drive company KPIs
* Shift from HiPPO decision making to data-driven decision making
* Competitive advantage, differentiation, future-proofing, and opportunity costs
* Complement business intelligence functions
* Predict and advise
* Grow data economy wealth
* Increase ROI and ROA
* Shifting between deductive (hypothesis-based) and inductive (pattern- based) reasoning (ref. Booz, Allen, Hamilton)
    - Deductive
        + Formulate hypotheses about relationships and underlying models
        + Carry out experiments with the data to test hypotheses and models
    - Inductive
        + Exploratory data analysis to discover or refine hypotheses
        + Discover new relationships, insights and analytic paths from the data

## Data Science Components and Considerations
- Data types
    + Structured data
    + Unstructured data
    + Semi-structured data
    + Streaming data
    + Batch data
- Analytic classes
    + Transforming analytics
        * Aggregation
        * Enrichment
        * Processing
    + Learning analytics
        * Regression
        * Clustering
        * Classification
        * Recommend
    + Predictive analytics
        * Simulation
        * Optimization
    + Descriptive analytics
    + Prescriptive analytics
- Learning models
    + Learning style
        * Supervised
        * Unsupervised
        * Semi-supervised
    + Training style
        * Reinforcement learning
        * Online learning
        * Offline learning
- Execution models
    + Sequencing
        * Serial execution
        * Parallel execution
    + Scheduling
        * Streaming execution
        * Batch execution
- Key considerations
    + Curse of dimensionality

## Analytics Toolbox
- Mathematical
- Computational
- Visual
- Analytic
- Statistical
- Experimental
- Problem definition
- Model building
- Validation

## Data Science Process (non-linear, iterative, and cyclical)
- Domain discovery, goal identification, and question development
    + Understanding the goal of the project and define objectives
    + Drives mapping the problem space to the solution space
- Determine the type of problem and type of solution required
- Data instrumentation, acquisition, collection, extraction, merging/joining, ETL, storage, and pipeline architecture/development
    + Data sources: raw data, real time measurement, events, IoT, and so on
    + Data warehouse or data lake
        * Data lake eliminates need for ETL according to Booz, Allen, and Hamilton
    + Note that more data is almost always better
- Data munging/wrangling
    - Data parsing, cleaning, and tidying
    - Data processing, transformation, and aggregation
        + Includes feature scaling, normalization, and/or standardization
        + Categorical feature transformation and dummy variables
            * One-hot encoding
            * Note: For large number of categorical features, a good technique is to encode only the most important features (e.g., 95% of the importance) and then assign the rest to an 'others' class
        + Deduplication
        + Data conversions
            * Character dates to dates
            * Numerics to strings and vice versa
        + Format conversion
        + Frequency space
            * Fast fourier transform (FFT)
            * Discrete wavelet transform
        + Euclidian space
            * Coordinate transform
        + Transposition if needed
        + Sorting as needed
    - Data filtering
        + Outlier detection and removal
        + Exponential smoothing
        + Gaussian filter
        + Median filter
        + Noise handling and reduction
    - Find and handle missing values
        + Imputation
            * Generate values for other observations in dataset
                - Random sampling
                - Markov chain monte carlo
            * Without other observations
                - Mean
                - Statistical distributions
                - Regression models
        + Data deletion
- Data consumption, exploratory data analysis (EDA), statistical analysis, descriptive analytics, and visualization
    + General plots
        * Histogram
        * Scatter
        * Box
    + Generate frequency table
    + Target variable distribution
    + Distributiont and outlier detection via box and scatter plots for numeric features
    + Correlation analysis and pairwise distribution plots
    + Plots with point color as label for classification tasks
    + Aggregations and analysis
        * Group for counts, sums, and averages
- Feature extraction, feature selection, and feature engineering
    + Purpose
        * Simpler and faster training
        * Less computationally expensive
        * Find feature interactions to use as new features
    + Techniques
        * Wrapper methods
        * Sensitivity analysis
        * PCA
        * Random forests
            - Mean decrease impurity
            - Mean decrease accuracy
        * Text-based
            - Stemming
            - Tokenizing
            - Synonym substitutions
- Performance metric selection. Examples:
    + MSE and RMSE
    + R squared (aka explained variance)
    + Accuracy
    + Precision
    + Recall (aka sensitivity)
    + Receiver operator characteristic (ROC)
    + Area under the ROC curve (AUC)
    + F-score
    + Per Kaggle
        * LB: Score you get is calculated on a subset of testing set
        * CV: Score you get by local cross validation is commonly referred to as a CV score.
- Data splitting
- Model selection, training, evaluation, validation, complexity reduction, and tuning
    + Iterative process and involves revisiting previous stages, including model selection
    + Model complexity reduction via subset selection, shrinkage methods, regularization (e.g., ridge regression and lasso), and dimensionality reduction
        * Dimensionality reduction
            - PCA
            - Factor analysis
            - K-means clustering
            - Canopy clustering
            - Feature hashing
            - Wrapper methods
            - Sensitivity analysis
            - Self organizing maps
            - Text data
                + Term frequency (TF)
                + Inverse document frequency (IDF)
    + Ensemble methods exploration and implementation as needed for performance goals
        * Techniques
            - Bagging
            - Boosting
            - Model averaging
            - Weak learner theory
            - Random forests
            - Blending
            - Stacking
            - ...
        * Benefits
            - Bias and variance reduction, thus reduced overfitting risk
            - Increased performance
    + Model validation, resampling methods, and selection
        + Cross-validation
        + Hyperparameter optimization
        + Bootstrap
        + Mallow’s Cp
        + Akaike information criterion (AIC)
        + Bayesian information criterion (BIC)
    + Model tuning: bias variance tradeoff and model complexity
        * Validation curve
        * Learning curve
        * Residual sum of squares
        * Goodness-of-fit metrics
        * Grid search
    + Error analysis and tradeoffs
        * Type 1
        * Type 2
    + Kaggle notes
        * Tree-based (top for Kaggle)
            - Gradient Boosted Trees
            - Random Forest
            - Extra Randomized Trees
        * Lower performance
            - SVM
            - Linear Regression
            - Logistic Regression
            - Neural Networks
    + Model tuning goals
        * Performance
        * Accuracy
        * Robustness
        * Speed
- Deliverables, deployment, and results communication (see below)

## Tips
- Random forest usually reach optimum when max_features is set to the square root of the total number of features.
- [How to Rank 10% in Your First Kaggle Competition](https://dnc1994.com/2016/05/rank-10-percent-in-first-kaggle-competition-en/)
    + Ensemble methods
        * Base models should be as unrelated as possibly. This is why we tend to include non-tree-based models in the ensemble even though they don’t perform as well. The math says that the greater the diversity, and less bias in the final ensemble.
        * Performance of base models shouldn’t differ to much.
    + Cross-validation
        * Usually 5-fold CV is good enough
        * We shouldn’t use too many folds if our training data is limited. Otherwise we would have too few samples in each fold to guarantee statistical significance.
        * More folds, the CV score would become more reliable, but the training takes longer to finish as well.
    + Automated pipeline
        * - Modularized feature transformations. We only need to write a few lines of codes (or better, rules / DSLs) and the new feature is added to the training set.
        * Automated grid search. We only need to set up models and parameter grid, the search will be run and the best parameters will be recorded.
        * Automated ensemble selection. Use K best models for training the ensemble as soon as we put another base model into the pool.

## Data Science Deliverables
- Automated decision making, predictions, recommendations, and insights
- Deep and actionable insights
    + Story telling
    + Writing
    + Speaking
    + Reports
    + Dashboards
    + Visualizations
    + Presentation
- Statistical analysis
    + Sensitivity
    + Correlation
    + Variance and standard deviation
    + Mean, median, and mode
    + Skew and kurtosis
    + Quartiles
    + Distribution
    + Count
    + Range
    + Plots
- Asynchronous messaging, notifications, insights, and alerts
- Deployed batch and/or real-time solution (e.g., analytics models and algorithms), potentially including monitoring, performance measurement, analytics, dashboards, and reporting
- Analytics
    + Descriptive analytics - What happened and why?
        * Visualization
        * Exploratory data analysis
    + Predictive analytics - What is the probability of something happening?
        * Machine learning
        * Artificial intelligence
        * Forecasting
    + Prescriptive analytics - What specific recommendations will drive business decisions and help achieve business goals (i.e., what to do if 'X' happens)
- Machine learning and Artificial intelligence specific
    + Supervised learning and prediction
        * Classification
            - Binary (two class) and multi-class
        * Regression
            - Univariate and multivariate
        * Anomoly detection
    + Unsupervised learning
        * Clustering, grouping, and characterizations
        * Anomoly detection
    + Recommendation systems (aka recommendation engine)
    + Recognition
        * Image
        * Speech
        * Video
        * Text and optical character
        * Pattern
        * Audio
        * Facial    
        * Handwriting
    + Text analytics
        * Sentiment analysis
        * Word clouds
        * NLP, NLG, NLU
        * Text categorization
        * Text processing
        * N-grams
        * Entity extraction (e.g., phone numbers, addresses, ...)
        * Levenshtein distance
    + Reinforcement learning
    + Probability estimates and likelihoods
    + Graph analytics (e.g., social network analysis)
    + Health diagnosis
    + Process improvements
- Optimization
    + Minimum
    + Maximun
    + Optimal value or optimal combination
- Segmentation
    + Behavioral
    + Demographic
    + Geographic
- Targeted advertising
- Forecasts
- Risk analysis
- Optimization and response surface models (RSM) for design of experiments (DOE) projects

## Process Models
- [Ask, Get, Explore, Model, Communicate and visualize results](http://www.datascientists.net/what-is-data-science)
- [Sample, Explore, Modify, Model, and Assess - SEMMA](https://en.wikipedia.org/wiki/SEMMA)
- [Acquire, Prepare, Analyze, Act (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
    + Analyze stage (iterate evaluation)
        * Setup
        * Try
        * Do
- [The Data Science Maturity Model: Collect, Describe, Discover, Predict, Advise (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
- [Balancing the Five Analytic Dimensions (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
    + Speed
    + Analytic complexity
    + Accuracy and precision
    + Data size
    + Data complexity
- [Implementation Constraints (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
    + Computational frequency
    + Solution timeliness
    + Implementation speed
    + Computational resource limitations
    + Data storage limitations
- [Fractal Analytic Model (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
    + Goal
        * Describe
        * Discover
        * Predict
        * Advise
    + Data
    + Computation
        * Aggregation
        * Enrichment
        * Clustering
        * Classification
    + Action
        * Productization
        * Data monetization
        * Insights and relationships
- [Cross Industry Standard Process for Data Mining - CRISP-DM](https://en.wikipedia.org/wiki/Cross_Industry_Standard_Process_for_Data_Mining)
    + [CRISP Visual Guide](https://exde.files.wordpress.com/2009/03/crisp_visualguide.pdf)
- [Knowledge Discovery in Databases - KDD](https://en.wikipedia.org/wiki/Data_mining#Process)
    + [Overview of the KDD Process](http://www2.cs.uregina.ca/~dbd/cs831/notes/kdd/1_kdd.html)
    + [From Data Mining to Knowledge Discovery in Databases](http://www.kdnuggets.com/gpspubs/aimag-kdd-overview-1996-Fayyad.pdf)
- [Team Data Science Process (TDSP)](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-process-overview) and [Interactive graphic](https://azure.microsoft.com/en-us/documentation/learning-paths/data-science-process/)
- [Acquire, Prepare, Analyze, Report, Act](https://www.coursera.org/learn/big-data-introduction/lecture/Fonq2/steps-in-the-data-science-process)
- [The REASON Method: Relating, Explaining, Selecting, Outlining, and Navigating](http://www.datasciencecentral.com/m/blogpost?id=6448529%3ABlogPost%3A369943)

## Data Mining
Coming soon...

## References
- [The Field Guide to Data Science (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
