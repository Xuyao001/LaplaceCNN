This dataset is a class imbalanced CAN bus fault diagnosis dataset. CANFD-2.91 indicates a low degree of imbalance, CANFD-5.03 indicates a moderate degree of imbalance, and CANFD-10.42 indicates a high degree of imbalance. Here, 2.91 and so on represent the reciprocal of the imbalance rate. 

The calculation of the imbalance rate is The ratio of samples in the data set's smallest category to samples in its largest category is known as the imbalance rate.
Each line in the file represents a sample, columns 1 to 1024 represent 1024 features, and the last column represents a label.
![image](https://github.com/user-attachments/assets/5e83465e-64da-4399-a992-2c4b478fbe05)
![image](https://github.com/user-attachments/assets/52d3e77f-5296-4d5e-ae48-bc17b7de96b5)
![image](https://github.com/user-attachments/assets/16b0b994-939f-4460-b112-caeae0fb7791)
(1). Fault A: Terminating resistor missing fault. 

(2). Fault B: Terminating resistor poor contact fault.

(3). Fault C: Poor contact failure of the CAN bus transmission line.

(4). Fault D: CAN bus transmission line short-circuit fault.

(5). Fault E: Electrical Fast Transient (EFT) interference.

(6). Fault F: Harmonic interference.
