# Dreem-challenge-kaggle---sleep-stage-classification

We use Dreem 2 headband data to perform sleep stage scoring on 30 seconds epochs of biophysiological signals.

Dreem headband allows doing polysomnography at home signal thanks to three kinds of sensors: electroencephalogram (EEG), pulse oximeter and accelerometer signals.

Since the Dreem headband records a lot of nights every day, we spent time developing the most accurate automatic sleep staging algorithms. Data was labeled directly on our data by trained sleep expert.

In this challenge we have labelled sleep stage data. The idea is to develop an algorithm of sleep staging able to differentiate between Wake, N1, N2, N3 and REM on windows of 30 seconds of raw data. The raw data includes 7 eegs channels in frontal and occipital position, 1 pulse oximeter infrared channel, and 3 accelerometers channels (x, y and z).

Final Score : F1 mean score = 0.73796
Final rank : 14/70
