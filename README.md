# TAGE-Branch-Predictor
Implementing TAGE and TAGE-L for simulation with ChampSim

**CS-305 IITB Group project by C.A.O.S team**
- Gyana Prakash Beria -> Implementing TAGE, TAGE-L, testing
- Hiren Bavaskar -> Implementing TAGE, testing
- Nabarun Champramnari -> Presentation, video making
- Sayantan Dhar -> Testing, video editing

## Objective of this project
Compare the performance of the state of art TAGE, TAGE-L branch predictors with other predictors like hashed_perceptron in ChampSim

## How to run these in ChampSim?
- Paste the tage.bpred and ltage.bpred files in /champsim/ChampSim/branch
- Put the trace file in the /champsim/traces
- Run the command ```./build_champsim.sh tage no no no no lru 1```
- Run the command ```./run_champsim.sh tage-no-no-no-no-lru-1core 10 10 {tracefilename}``` 
- The results can be seen in the results_10M folder

## Code and Presentation References
1. [Main reference paper](https://jilp.org/vol9/v9paper6.pdf)
2. https://github.com/2Bor2C/tage
3. https://github.com/rajarshibiswas/Branch-Prediction
