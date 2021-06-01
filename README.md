## Audio Visual Patches

Patches for TouchDesigner

### Main Control UI

![image](https://user-images.githubusercontent.com/48803449/120361005-a7118f80-c309-11eb-8910-963167d4a667.png)

* **Main interface** for controlling then AV content btph for teh stage screens and projector. Using Lunochod UI

### Screen TOX's

**AI Data Viz w/ Head Scans**

Uses Head scans for each performer and visulizes the date thrugh teh layout for both the emotion being acted and teh data coming from the AI

![image](https://user-images.githubusercontent.com/48803449/120362077-f6a48b00-c30a-11eb-99f3-5051fab6f470.png)

**AI Data Viz Circle**

![image](https://user-images.githubusercontent.com/48803449/120364480-95ca8200-c30d-11eb-8da5-30d9d57c0de5.png)

**AI Data Viz Graph**

Graph uses instancing to create a general graph of all the emotion AI is detecting on the given performer, left hand side emotion shows the current emotion being acted by the performer.

![image](https://user-images.githubusercontent.com/48803449/120365620-f908e400-c30e-11eb-8156-75865c4c8023.png)


**AI Screen Smiley**

Repsresents the current emotion of tehe performer is acting through a distorted smiley.

![image](https://user-images.githubusercontent.com/48803449/120366643-2e620180-c310-11eb-995f-9ffc64d96d31.png)

![image](https://user-images.githubusercontent.com/48803449/120366942-8ac52100-c310-11eb-8942-d82d85ab4bf1.png)

**AI Main Screen Circle Visualization Circle v_2**

![image](https://user-images.githubusercontent.com/48803449/120367631-661d7900-c311-11eb-82c4-9f7bdfb55f3e.png)


<!-- <IMAGE OF STAGE SETUP (vector)> -->


### Internal TOX's

**Session Manager**

Conrols the sessions and send data to the stage PDAC over PDAC Router Patch using Websockets

Send CUE's to both light and sound through the list selection in CUE Patch 

**Cue Patch**

Cross matches the list of Cues for sound and light 

**PDAC Router**

Acts as the main UI for managing the PDAC data flow for between theAV machine and stage PDAC's.

**Communication Ports For Internal Data Packages**

AI OSC OUT : 300 
AI SIM OSC OUT: 301


<!-- **Patches**


* *smiley.tox* - smiley-face scene
* *melt.tox* - pixel-sorting scene
* *emotion.tox* - performer ratings scenes
* *overhead.tox* - overhead projection -->
