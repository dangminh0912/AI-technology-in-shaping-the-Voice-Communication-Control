# Regression Model in shaping the Voice Communication Control
-------------------------------------------------------------
## Description
Talking while driving: is not a good idea. Texting while driving: is downright dangerous and talking while flying: is essential (Volpe National Transportation Systems Center, 2022). A Voice Communication System (VCS) is an essential element in the aviation communication framework, allowing pilots, air traffic managers, and ground staff to converse. VCS ensures clear and efficient voice dialogues, promoting the secure and smooth functioning of air traffic management. Additionally, it is specifically developed for civil and military air traffic control such as ACC and APP control centers, ATC towers, simulators, and backup/emergency. VCS includes microphones, headsets, radios, and other integrated equipment. These components are designed to enable clear in-flight communication despite cockpit noise, vibrations, and other challenges. The system primarily faces challenges with sound disruption and the communication between air traffic controllers and pilots. Therefore, this study aims to integrate AI tools with sound disruption and text-driven communication systems to identify voice disturbances and guarantee consistent international messaging. I specifically focused on how the integration of AI technology can enhance the efficiency and reliability of the Voice Communication System (VCS).
## Author
- Name: Minh Nguyen
- Major: Data Analytics (Economics concentration), Minoring: Computer Science and Mathematics
## Contact
- Email: nguyen_m6@denison.edu
- Phone number: (740)-405-6495
## Programming Language
- Python and Jupiter Notebook
- Version: 3.8.13
- Libraries: Matplotlib/Seaborn, BeautifulSoup, PyTorch/LibROSA, Textstat.
  

## Data
- For the dataset, I plan to utilize data from sources such as Common Voice, Urban Sound, TIMIT, and DEMAND. These sources will aid in building and assessing AI models focused on identifying sound disruptions, minimizing noise, and enhancing voice recognition in communication systems. They provide a range of scenarios, environments, and sound profiles that will assist in thorough analysis and the development of improved AI-backed Voice Communication Systems. This process includes generating a varied collection of audio recordings that simulate conversations between air traffic controllers and pilots. The variables are noise levels, accents, and terminologies. This approach will allow the advancement and evaluation of the AI-integrated VCS without violating any privacy or security standards associated with real aviation communication data.
- The text-based analysis is performed to compare AI-generated text and human text and determine which one is easier to understand. I will use Python with the library “textstat”. This library uses the Flesch Reading Ease score: Source: https://pypi.org/project/textstat/
This means text should be fairly easy for the average adult to read. This is the source where I will
collect the text for the dataset, which includes 2 variables: Speaker and Conversation Text. The “Speaker” determines who is speaking in the conversation (Controller or Pilot) and the “Conversation Text” indicates the conversation between controller and pilot in the text format.


