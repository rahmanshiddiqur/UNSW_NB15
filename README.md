Here I have done the preprocessing with the intrusion detection dataset named "UNSW-NB15". UNSW-NB 15 data set is created by the IXIA PerfectStorm tool in the Cyber Range Lab of the Australian Centre for Cyber Security (ACCS) for generating a hybrid of real modern normal activities and synthetic contemporary attack 
activities. The UNSW-NB15 source files are provided in different formats, Pcap files, BRO files, Argus Files and CSV files. The source files of the data set were divided based in the date of the simulation 22-1-2015 and 17-2-2015, respectively. The descriptions of these simulations are 
provided in the report files to show the network configurations and the actions of the attack types during the simulation.

I have clean the dataset, remove the duplicates, clear the null/NA values . Then I have done the Normalization. After this I did the encoding. For this I had used the label encoding. 
After preprocessing I had split the dataset into 80:20 ratio. 
And then I had train my four Hybrid Model (CNN-LSTM, CNN-BiLSTM, CNN-GRU, CNN-BiGRU) with the training dataste and then test. 
I had got overall good performances from all of my hybrid model. But compared to each other it is seen that (CNN-BiLSTM) and (CNN-BiGRU) had the more better performance and higher accuray
