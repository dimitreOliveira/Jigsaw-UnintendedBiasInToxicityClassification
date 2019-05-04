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
|[11th] Bi GRU - SGD|0.8805|0.8797|0.88098|???|6186.2|
|[12th] Bi GRU - LROnPlateau|0.9114|0.9084|0.90747|???|4420.3|
|[13th] Bi GRU - LRStepDecay|0.9103|0.9078|0.90679|???|4745.9|
|[14th] Bi GRU - Adam|0.8797|0.8765|0.87566|???|1413.8|
|[15th] Bi GRU - RMSprop|0.8506|0.8485|0.84158|???|1445.1|
|[16th] Bi GRU - Adadelta|0.8620|0.8611|0.86429|???|6532|
|[17th] Bi GRU - Adagrad|0.9031|0.8921|0.88897|???|1549.2|
|[18th] Bi GRU - LROnPlateau 0.5|0.9119|0.9085|0.90791|???|4400.7|
|[19th] Bi GRU - LROnPlateau 0.5 Longer|0.9120|0.9085|0.90738|???|4978.2|
|[20th] Bi GRU - Punctuation|0.9112|0.9077|0.90677|???|5006.4|
|[21th] Bi GRU - Contraction|0.9107|0.9067|0.90710|???|5038|
|[22th] Bi GRU - Misspelling|0.9114|0.9079|0.90743|???|5011.7|
|[23th] Bi GRU - Lower|0.9118|0.9084|0.90741|???|4918.4|
