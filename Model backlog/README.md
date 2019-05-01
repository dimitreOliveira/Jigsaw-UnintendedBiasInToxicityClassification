## Model backlog (list of developed model and it's score)
- **Train** and **validation** are the splits using the train data from the competition.
- The competition metric is **Jigsaw Bias AUC**.
- **Runtime** is the time in seconds that the kernel took to finish.
- **Pb Leaderboard** is the Public Leaderboard score.
- **Pv Leaderboard** is the Private Leaderboard score.

---

## Deep Learning

|Model|Train|Validation|Pb Leaderboard|Pv Leaderboard|Runtime(s)|
|-----|-----|----------|--------------|--------------|----------|
|[1st] Bi GRU - Baseline|0.91|0.89|0.89316|???|1145|
|[2nd] Bi LSTM - Baseline|0.9005|0.8857|0.88531|???|1255.1|
|[3rd] GRU - Baseline|0.9031|0.8895|0.88608|???|804.3|
|[5th] Bi GRU - maxlen 200|0.9005|0.8853|0.88247|???|1589.9|
|[6th] Bi GRU - maxlen 250|0.9076|0.8959|0.89349|000|1601.9|
|[7th] Bi GRU - max_features 35000|0.9065|0.8942|0.88997|???|1084.4|
|[8th] Bi GRU - max_features 40000|0.9044|0.8918|0.89229|???|1084.7|
|[9th] Bi GRU - max_features 45000|0.9059|0.8938|0.89096|???|1088.5|
|[10th] Bi GRU - max_features 50000|0.9032|0.8911|0.89108|???|1161.6|
