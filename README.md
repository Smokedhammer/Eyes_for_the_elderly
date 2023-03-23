<div align="center">
  
  <br>
  <p>
    With vision impairment being one of the most prominent health issues in the elderly, it has become imperative to tackle the complications an individual faces while navigating inside their living quarters. This paper aims to describe the working of an AI tool called Eyes for the Elderly that communicates with the target demographic to enable them to locate objects in their vicinity.
We first engineered a way to convert audio data into text, which could then be used in parallel with a custom-trained YOLOv5 (You Only Look Once) algorithm. Snapshots from the video feed are taken and fed into this model. The tool then calculates the IOU (Intersection Over Union) between the bounding boxes of the objects detected. This allows us to locate objects with respect to each other.(ex: The phone is on the bed). The location of the household item is then returned as an audio response. This allows the target demographic to make up for their loss of vision to a certain degree. This tool was then integrated into a web application built on flask. The interface enables the visually impaired to quickly and efficiently locate personal belongings in multiple areas inside their homes.

Download the repository, and then run python app.py while being in the current directory. (make sure to download the requirements and connect to the camera of choice!

The rest of the paper can be found at: 
    
  </p>

</div>


