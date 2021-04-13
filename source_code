[System]
Name='Tugas_Prak_Fuzzy'
Type='mamdani'
Version=2.0
NumInputs=3
NumOutputs=1
NumRules=7
AndMethod='min'
OrMethod='max'
ImpMethod='min'
AggMethod='max'
DefuzzMethod='centroid'

[Input1]
Name='makan'
Range=[0 10]
NumMFs=2
MF1='sedikit':'trimf',[-4.168 -1.11e-16 7]
MF2='banyak':'trimf',[3 10 14.17]

[Input2]
Name='belajar'
Range=[0 10]
NumMFs=2
MF1='malas':'trimf',[-4.166 -1.665e-16 7]
MF2='rajin':'trimf',[3 10 14.17]

[Input3]
Name='tidur'
Range=[0 10]
NumMFs=2
MF1='kurang':'trimf',[-4.168 -1.11e-16 7]
MF2='cukup':'trimf',[3 10 14.17]

[Output1]
Name='prestasi'
Range=[0 30]
NumMFs=3
MF1='kurang':'trimf',[-12.5 0 12.5]
MF2='rata-rata':'trimf',[2.5 15 27.5]
MF3='baik':'trimf',[17.5 30 42.5]

[Rules]
1 1 1, 1 (1) : 1
2 1 1, 1 (1) : 1
1 2 1, 2 (1) : 1
1 2 2, 3 (1) : 1
2 1 2, 2 (1) : 1
2 2 2, 3 (1) : 1
1 2 1, 2 (1) : 1
