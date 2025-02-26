# Cyber-Security-AICTE--Project-on-Hiding-Data-Using-Steganography--

Steganography is the practice of concealing information within other, seemingly innocuous data, such as images, audio files, or text. The goal is to hide the existence of the information itself, so that it remains undetectable to anyone who isn't specifically looking for it.
	
•     In images: Information could be hidden in the least significant bits (LSBs) of the image pixels, which are altered in a way that is invisible to the human eye but can be 			  extracted using a specific algorithm.

•    In audio: Messages can be embedded in sound files by slightly altering frequencies that are inaudible to the human ear.

•    In text: Certain letters or words might be used to spell out a hidden message, or specific patterns in the text can serve as a covert message.

•    In Video: Video files offer both spatial and temporal domains for hiding data. Steganographic techniques in video files could involve altering pixel values in specific frames 		 (spatial domain) or manipulating the frame rate or motion patterns (temporal domain).

•    In Network: Data can be hidden within network protocols or messages. For example, in the headers of packets in network traffic or within unused fields of a network protocol.		
		
A modern GUI application for hiding secret message within images using steganography techniques. Built with python and openCV2 Library. 

**Features**

•	Support for multiple image formats like PNG, BMP, JPEG, JPG)
•	Text input directly from files.
•	Password protection for message encrypts and decrypt.
•	Real time status update
•	Save encoded images in high quality PNG format.

**Steganalysis**

Steganalysis is the process of detecting hidden information in media. Common methods of steganalysis include:

•**Visual Inspection:** Sometimes, minor artifacts or distortions in an image, audio, or video file can signal that data has been hidden.
•**Statistical Analysis:** Analyzing the statistical properties of the file (such as pixel distribution in images) can reveal inconsistencies.
•**Machine Learning:** Advanced methods use machine learning algorithms to detect hidden data by recognizing patterns in files.


