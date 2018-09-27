# NEAT TERMINOLOGY

## Active Inertia / Cognitive Inertia
    * When you set a belief and it fuck you over later

## _A Priori_
    * 'from the earlier'

## _A Posteriori_
    * 'from the later'

## _Non Sequitur_
    * 'it does not follow'

## _Likelyhood =/= Probablity_
    * 'in stats, likelyhood and probablity are not synonymous'

## Type I Error
    * H<sub>0</sub> is true but regected.

## Type II Error
    * H<sub>0</sub> is false but accepted.

## Null Hypothesis (H<sub>0</sub>)
    * The equality bound always goes into the null hypothesis. i.e. the >= & =< are always in H<sub>0</sub>
    * The "not interesting" result

## Pedantic
    * ostentatious in one's learning.

## Meta-Conversation
    * Talking about your conversation about something else

## Heteroskedasticity
    * hetero “different” and skedasis “dispersion”

## Data Deluge or Information Explosion
    * the side effects of bringing lots of information into scope

## Dagwood Sandwich Problem
    * Multi layered multi parameter functions, like callback hell.

## Gaussian or Normal Curve
    * You know the one.

## Preattentive Processing
    * Spidey Sense (<250ms)

## Visualization: 'Pop'
    * The speed at which you can decode a vis

## C.R.A.P. of Good Design
    * Contrast, Alignment, Repetition, Proximity

## Hicks Law    
    * More Choice, More Time. Rate of gain of Information

## Chart Junk
    * Anyhting included in a chart that's junk obviously

## Data / Ink Ration
    * Amount of text vs data

## UX "Affordances"
    * Switches, buttons, things a user must do

## UX "Signifier"
    * Showing users what the controls are

## UX "Mapping"
    * Working with how the user expects controls to work

## The 7 Types Of Lean Manufacturing Waste (TIMWOOD)
    * Transport
    * Inventory
    * Motion
    * Waiting
    * Over Processing
    * Over Production
    * Defects

## EDA: Exploratory Data Analysis
    * 

## Brownian Motion
    * Simulation of random motion of particles in a fluid or gas.

## EMV: Expected Monetary Value
    * The number used to compare different decisions.

## Anscombe's Quartet
    * Four scatterplots that look very different but have the same outputs

## Least Squares Regression Line
    * The line where the sum of the distrance from each point squared is the minimum

## Generic Statistical Model
    * response = f(explanatory) + noise
    * Y => X + e

## Utility Function
    * The imaginary function of a customer's perspective on the usefullness of a product to them.

## Nash Equilibrium
    * Is a solution concept of a non-cooperative game involving two or more players in which each player is assumed to know the equilibrium strategies of the other players, and no player has anything to gain by changing only their own strategy.

## Confusion Matrix
    * this is the rate at which type I & type II errors are made.

## Receiver Opererating Curve (ROC CURVE)
    * Developed during WWII for Radar.

## Area Under Curve (AUC)
    * Pretty fucking self fucking explanatory no
    * Perfect model is 1, average for a random model is 0.5
    * Think of it as a letter grade, happy with 0.8, 0,7 isn't bad.

## GLMNET Models: Generalized Linear Models
    * Attempts to find a parsimonious model. Helps with colieearity, also better with small sample sizes. Pairs well with random forest models. Uses balance of Lasso and Ridge regressions.
    * Turing Parameters:
        * Alpha: Mix of Lasso : Ridge Regressions
        * Lamda: Strength of the penalty on the coefficients
    * Lasso Regression
        * Peanlizes the number of non-zero coefficients
    * Ridge Regression
        * Penalizes the absolute magnitude of the coefficients

## Parsimonious
    * Frugal, unwilling to spen money or use resources

## KNN Inputation
    * K Nearest Neighbours Imputation, tryies to make it up based on existing data points like it

## Principle Compoent Analysis
    * Combines the low variance and correlated variables into a single set of hifh-variance, perpendicular predictors.
    * 

## The 5 Vs of Big Data (only 3 are legit)
    * Volume - The size of it all
    * Variety - The range of sources
    * Velocity - The speed at which it's growing
    * Veracity (bullshit)
    * Value (bullshit)

## Edge Computing
    * Keeps only a rolling state rather than storing it all

## What Counts As Big Data?
    * You can't hold it or analyze it on an average consumer-level computer.

## What makes Data Smart?
    * Data that provides values to the bottom line somehow

## RMSE: Root Mean Squared Error
    * The measurement of the closeness of the model to new values.

## Aritificial Intelligence 
    * AI : Artifical Intelligence
        * ML : Machine Learning --> Algorithms that improve over time through exposure to more data
            * DL : Deep Learning --> Subset of Machine Learning that uses advanced Neural Networks
                - Convolution NN : 
                - Recursive NN : 

## Supervised Learning
    * Uses training data and feedback from humans to learn relationships.
    * Regression, Classification
    * When you want to make predictions on labelled data

## Unsupervised Learning
    * an algorithm explores input data without being diven an explicit output variable.
    * Clustering, Anomalies
    * Finding structure in unlabeled data
    * Dimensionality Reduction (reducing the number of dimensions effectively) (makes it simpler)
        * Principal Cmponent Analysis
            * Finds a linear combination of variables to create principle components
            * principle components should be uncorrelated
    * Used for PreProcessing before Supervised Learning
    * Requires creativity

## K-means Clustering Algorithm
    * Base install in R, Basically Breaks overservations into pre-defined number of clusters
    * 

## Hierarchical Clustering
    * Top Down
        * 
    * Bottom Up
        * 

# Linking Cluster Methods:
    * Complete *good
        * pairwise similarity between all obsercations in cluster 1 and cluster 2, and uses largest of similarities
    * Single *not great
        * same as above but uses smalles of similarities
    * Average *good
        * same as above but uses average
    * Centroid *dangerous
        * finds centroid of cluster 1 and centrind of cluster 2, and uses similaritiy between two centroids.

## Dentrogram
    * Tree shaped structure to interperet hierarchical clustering models

## Reinforcement Learning
    * An algorithm learns to perform a task simply by trying to maximize rewards it receiveds for its actions.
    * Games (Chess, Go, Poker, Starcraft)
    * Works when clear "rules" are present and machines can play with themselves (create its own data to train itself)
    * Learns from operating in a real environment

## Moore's Law
    * Computing power doubles every two years.

## Back Propogation
    * Helps calculate the weight of results from a Neural Network

## ARIMA Models
    * 

## Text Corpus
    * Collection of documents or tesxt

## Little's Law
    * 

## Gantt Chart
    * Timeline of stacked process steps or walk-ins or whatever

## Antithetic
    * Against the thesis, 'antithesis'

## Specification Limits
    * USL : upper specification limit
    * LSL : lower specification limit

## Process Capability Index
    * CP = (USL - LSL) / 6-sigma

## Six Sigma Process
    * A process that yields 3.4 defective parts per million.
        * Muda (無駄, also ムダ) (English: Waste)
        * Mura (斑 or ムラ) (English: Unevenness)
        * Muri (無理) (English: Overburden)

## Poka-Yoke (ポカヨケ)
    * Japanese word for 'error proofing'
    * Originally 'baka-yoke' for 'idiot proofing'
 
## Obeya (大部屋) 
    * Manager's meeting. Literally: Large room, war room, council room

## Jidoka (自働化)
    * Japanese word meaning "Automation with a human touch"
    * Build a culture of stopping to fix problems, to get quality right from the start.

## Heijunka (平準化) 
    * Level out the workload (work like the tortoise, not the hare)

## Kaizen (改善)
    * Japanese word for 'continuous improvement'

## Gemba (現場) 
    * The actual place, the place where the real work is done; On site

## Andon (行灯) 
    * A large lighted board used to alert floor supervisors to a problem at a specific station. Literally: Signboard)

## Kanban (看板, also かんばん) 
    * Sign, Index Card

## Toyota Production System
    * Waste of overproduction (largest waste)
    * Waste of time on hand (waiting)
    * Waste of transportation
    * Waste of processing itself
    * Waste of stock at hand
    * Waste of movement
    * Waste of making defective products
    * Waste of underutilized workers

## ANOVA Gauge R & R
    * ANOVA gauge repeatability and reproducibility is a measurement systems analysis technique that uses an analysis of variance (ANOVA) random effects model to assess a measurement system.

## The 5 Whys
    * 5 Whys is an iterative interrogative technique used to explore the cause-and-effect relationships underlying a particular problem.[1] The primary goal of the technique is to determine the root cause of a defect or problem by repeating the question "Why?" Each answer forms the basis of the next question. The "5" in the name derives from an anecdotal observation on the number of iterations needed to resolve the problem.

## S.I.P.O.C Tooling
    * In process improvement, a SIPOC (sometimes COPIS) is a tool that summarizes the inputs and outputs of one or more processes in table form. The acronym SIPOC stands for suppliers, inputs, process, outputs, and customers which form the columns of the table. It was in use at least as early as the total quality management programs of the late 1980s[a] and continues to be used today in Six Sigma, lean manufacturing, and business process management.

## Chi-Square Goodness-of-fit
    * Chi-Square Distribution is 

## Simpson's Paradox
    * Simpson's paradox, or the Yule–Simpson effect, is a phenomenon in probability and statistics, in which a trend appears in several different groups of data but disappears or reverses when these groups are combined. It is sometimes given the descriptive title reversal paradox or amalgamation paradox.

## Cycles
    * Something that is not nessessarily trending

## Trends
    * 

## Exponential Smoothing
    * New forecast = alpha * actual + (a - alpha) * old forecast
    * Basically the further we go into the past when calculating moving averages & forecasts the less it impacts the prediction.

## Holt's Model
    * Smoothing with addititive trent
    * includes a alpha * beta level

## Winter's Model
    * Smoothing with additiveve trend and seasonality.
    * Includes 

## Multiplicative smoothing methods

## Decompositions

## Multiple Seasonalities


## Autoregressive Methods
    * ARMA, ARIMA, ARCH, GARCH
    * Dynamic Regressions
    * Multiple correlated time-resires
        * Vectoried auto-regressions

## 'Classical' ARMA & ARIMA
    * Auto-regression
        * P
    * Moving Average (this is different from the normal moving average)
        * regressing on the error from the prev
    * Differencing
        * regressing on the difference between previous values and this value
    * ARIMA(p,d,q)
        * p = number of auto-regressive terms
        * d = 'order of the first difference'
        * q = num of moving average terms
    ARIMA(0,0,0) white noise
    ARIMA(0,1,0) random walk
    ARIMA(0,1,0) rand walk with dirft
    ARIMA(p,0,0) autoregression
    ARIMA(0,0,q) moving average
 
## Forecasting 'Cones'
    * 

## Rolling Horizon Holdout Datasets
    * Predicting timeseries using a test set of previous time periods togeterh

## Dynamic Regressions
    * Blend a number of data-types

## Trigonometric Seasonality (Fournier Transforms)
    * Uses a combo of Sin & Cos to determine seasonality then creates intercepts for each wave so that when they're added together they come close to the actual variance in the data.


## FUN FACTS:
    * AI Translation French-English is most robust because of Canada's public parliamentary notes