# BLADE Dataset


The BLADE dataset is a obfuscation resilient system based on Opcode Segments for Android malware detection. The data set comprises of Opcode Segment Document (OSD) of malware and benign samples generated from static analysis approach defined in the paper "BLADE: Robust malware detection against obfuscation in android".

The dataset is based on samples collected from various sources and processed into OSD files. 

	+ AndroAutopsy
	   --Benign0
	   --MalwareFamilies
	+ AndroTracker
	   --Benign1
	   --MalwareFamilies
	+ Drebin
	   --MalwareFamilies
	+ PRAGuard
	   --Contagio (T, S, R, C, TS, TSR and TSRC)
	   --Malgenome (T, S, R, C, TS, TSR and TSRC)

[Obfuscation Techniques T: Trivial; S: String Encryption; R: Reflection; C: Class Encryption; TS: Trivial and String Encryption; TSR: Trivial, String encryption and Reflection; TSRC: Trival, String Encryption, Reflection and Class Encryption]


If you are using our dataset, you need to cite our research paper which outlines the details of the dataset and its underlying principles:

Sihag Vikas, Manu Vardhan, and Pradeep Singh. **"BLADE: Robust malware detection against obfuscation in android."** Forensic Science International: Digital Investigation 38 (2021): 301176.

The dataset is available on --> www.kaggle.com/vikassihag/blade-dataset
