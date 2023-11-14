# Regression Model in shaping the Voice Communication Control
-------------------------------------------------------------
## Description
Talking while driving: is not a good idea. Texting while driving: is downright dangerous and talking while flying: is essential (Volpe National Transportation Systems Center, 2022). A Voice Communication System (VCS) is an essential element in the aviation communication framework, allowing pilots, air traffic managers, and ground staff to converse. VCS ensures clear and efficient voice dialogues, promoting the secure and smooth functioning of air traffic management. Additionally, it is specifically developed for civil and military air traffic control such as ACC and APP control centers, ATC towers, simulators, and backup/emergency. VCS includes microphones, headsets, radios, and other integrated equipment. These components are designed to enable clear in-flight communication despite cockpit noise, vibrations, and other challenges. The system primarily faces challenges with sound disruption and the communication between air traffic controllers and pilots. Therefore, this study aims to integrate machine learning with sound disruption and text-driven communication systems to identify voice disturbances and guarantee consistent international messaging. I specifically focused on how the integration of machine learning can enhance the efficiency and reliability of the Voice Communication System (VCS).

## Author
- Name: Minh Nguyen
- Major: Data Analytics (Economics concentration), Minoring: Computer Science and Mathematics

## Contact
- Email: nguyen_m6@denison.edu
- Phone number: (740)-405-6495

## Programming Language
- Python and Jupiter Notebook
- Version: 3.8.13
- Libraries: librosa - audio processing, pandas - data analysis, sklearn - machine learning, matplotlib - visualization, numpy - numerical computing, soundfile/scipy - audio I/O, warnings - ignore warnings
  

## Data
For the dataset, I collected the datasets from the Dicom Corporation to get the voice recording from the VCS system in the Air Traffic Controller (ATC) of Noibai International Airport. These data provide the wav files of the sound with background noise (HF_ANALOG, VHF_ANALOG) and without background sound (VHF_VOIP, VOIP Telephone). HF_ANALOG and VHF_ANALOG are the High Frequency (HF) and Very High Frequency signals that contain the background noise. HF radios cover far greater distances due to ionospheric refraction, but HF radio signals are prone to distortion by atmospheric conditions such as geomagnetic storms or solar flares that radio users cannot control. HF communications are best suited for long-distance communication between ground operators and base stations. VHF_VOIP uses VHF radio frequencies to transmit voice communications encoded as VOIP; VOIP Telephone is a technology that allows users to make voice calls using a broadband Internet connection instead of a regular (or analog) phone line.



