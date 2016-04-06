#Dynamic Retrainig of Azure ML Environments

#Overview:
55 minutes, 45 presentation, 15 minutes Q&A


##What does the audience want to know?
* What is going on behind the scenes for Azure ML? iLearner and storage?
* Why do retraining?
* What is possible to fully automate the retraining process?

##Artifacts:
* The github repo for dynamic retraining
* Documentation for how to retrain

##Outline
1. Overview of Azure ML workflow behind the scenes
    1. The Azure Blob Storage - what's in it and how it's used
    2. Endpoints and model retraining experiments
2. The retraining components and process
    1. Creating and purpose of retraining experiment (BES call)
    2. Endpoints for redeploy and scale out
    3. Matching iLearners with experiments
    3. Input and Output nodes
3. How to take full advantage of the retraining process
    1. Storing retraining results (in CSV)
    2. Keeping and sharing iLearners
    
