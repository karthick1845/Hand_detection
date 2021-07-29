# Hand detection
  This is an object detection model,where i worked with help of my organization mates.
# Problem description
   The shutter machine in an Tea production factory seeking a problem by "whenever you pass garbage by hand to a sutter machine".
    
   It rarely sometimes workers hand accidently will go more than limit,at that time some damage will occur for our worker".

# Use case
   *  Creating a hand model using transfer learning and will identify hands,then create a bounding box of it.

   *  Then create two certain line named as safety border line and machine border line,if hand will crossing safety border line,
set an alert tune and suppose accidently crossing an machine border line the machine will automatically stopped.

   *  Save an each time that you will run an model and put it into xl sheet.
     
   *  I worked on ssd with moblienet model here pretrained weights :https://drive.google.com/file/d/1txQZBQCZpf-ziBhTCIv5qlugTMHfAdcO/view?usp=sharing

# Steps
   *   To download pretrained weights here : https://drive.google.com/drive/folders/1CeghfTiyh9U7kfSQcBdZMGHjepRzLYoh?usp=sharing
     
   *   Just command > pip install -r requirements.txt.
     
   *   Then execute hand_detection.py.
   
