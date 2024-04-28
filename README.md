# Face-attendance-using-FaceNet
1) We start by creating a virtual environment followed by installing all the packages and dependencies given in the requirements.txt file
2) Make a folder named "dataset" in the same directory as the project and add the faces which you want the model to recognize in that folder
3) Run the "Create_Signature_Haar.ipynb" file to generate the data.pkl file i.e. the signatures of all the faces
4) Run the "Recognize_Face_Haar.ipynb" file to open the webcam using OpenCV for capturing anf recognizing faces
5) The names of the recognized faces will get added to the excel sheet along with the time to track attendance 
