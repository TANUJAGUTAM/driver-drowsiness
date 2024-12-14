Driver Drowsiness Monitoring using Convolutional Neural Networks

The advancement in computer vision has assisted drivers in the form of automatic self-driving cars etc. The misadventure are caused by driver's fatigue and drowsiness about 20%. It poses a serious problem for which several approaches were proposed. However, they are not suitable for real-time processing. The major challenges faced by these methods are robustness to handle variation in human face and lightning conditions. We aim to implement an intelligent processing system that can reduce road accidents drastically. This approach enables us to identify driver's face characteristics like eye closure percentage, eye-mouth aspect ratios, blink rate, yawning, head movement, etc. In this system, the driver is continuously monitored by using a webcam. The driver's face and the eye are detected using haar cascade classifiers. Eye images are extracted and fed to Custom designed Convolutional Neural Network for classifying whether both left and right eye are closed. Based on the classification, the eye closure score is calculated. If the driver is found to be drowsy, an alarm will be triggered.
EXISTING SYSTEM:
driving supporter schemes decreased the danger of four-wheeler accidents, and investigations depicted weariness to be a major reason of four wheeler accidents. A car organization announced an idea that whole deadly accidents (17%) would be attributed to weary drivers. Many revisions showed by Volkswagen AG specify that 5-25% of all accidents are produced by the sleeping of driver. The lack of concentration damage steering actions and decrease response period, and revisions illustrated that sleepiness raises threat of crashes demand for a dependable intelligent driver sleepiness sensing system. The aim is to create an intelligent processing scheme to avoid road accidents. This can be done by period of time monitoring the drowsiness and warning driver of inattention to prevent accidents.
DISADVANTAGES OF EXISTING SYSTEM:
	It is not suitable for real-time processing. 
	The existing system uses the orientation of facial characteristics for drowsy detection. 
	based on three factors such as physiological, behavioral, and vehicle-based measurements. But these approaches pose some disadvantages in certain real time scenarios.
Algorithm: Learning Vector Quantization (LVQ),Support Vector Machines (SVM)
PROPOSED SYSTEM:
Our proposed system will provide a solution for monitoring driver's drowsiness. The cons of the existing system in extracting only selected hand-crafted features is overcome by using custom-designed CNN by giving an input driver image. Now the driver will be continuously monitored by a webcam. The video captured is converted into a sequence of frames. For each frame, the face and eye are detected using predefined classifiers available in opencv called haar cascade classifiers. Eye images are extracted and sent to a series of 2D CNN layers (5x5, 3x3 kernel valid padding), max-pooling layers(2x2) and finally, the fully connected dense layer classifies whether eyes are closed or not. A score is calculated based on eye closure. If both eyes are closed consecutively in 15 frames then the system predicts as drowsy and an alarm sound is triggered to alert the car operator. The categorization of driver drowsiness is done correctly and the normalization issues in the existing model are eliminated by using customdesigned CNN. 
ADVANTAGES OF PROPOSED SYSTEM:
	If the eyes are both closed, we increase the score and when eyes are open, we decrease the score. We are drafting the outcome to display the actual time condition of the driver.
	approach enables us to identify driver's face characteristics like eye closure percentage, eye-mouth aspect ratios, blink rate, yawning, head movement.
Algorithm: Convolutional Neural Network; Data Augmentation Deep Learning.
SYSTEM REQUIREMENTS:
HARDWARE REQUIREMENTS:

	System			: 	Intel i5 6 core.
	Hard Disk 		          : 	500 GB SSD.
	Monitor			: 	15’’ LED
	Input Devices		: 	Keyboard, Mouse
	Ram				: 	32 GB.

SOFTWARE REQUIREMENTS:

	Operating system 		: 	Windows 10.
	Coding Language		:	Python
	Tool				:	PyCharm, Visual Studio Code
	Database			:	SQLite


REFERENCE:
D. Rosy Salomi Victoria; D. Glory Ratna Mary “Driver Drowsiness Monitoring using Convolutional Neural Networks  " 2021 International Conference on Computing, Communication, and Intelligent Systems (ICCCIS) Accession Number: 20552967 DOI: 10.1109/ICCCIS51004.2021.9397070.
