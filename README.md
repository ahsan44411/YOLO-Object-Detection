# Welcome to my repo

Custom Traffic Dataset was created for this project.
Classes:
1. Person
2. Cars
3. Bikes
4. Bicycles
5. Number Plates

Around 500-1000 images were collected for each class and number of instances per class exceeded 1000. All images were labeled using LabelImg(https://github.com/tzutalin/labelImg)

# Resources
Model Weights for traffic dataset (Person, Cars, Bikes, Bicycles, Number Plates) avalible here 
<strong>https://drive.google.com/file/d/1-4l16rpFfakvERIWHUnNC2Oe3z2RzaDG/view?usp=sharing</strong>

Get demo train data from here
<strong>https://drive.google.com/file/d/1SjCn76d9Hk-v0wpFUNvoKIhUfkNi5Ijm/view?usp=sharing</strong>

and test data from here 
<strong>https://drive.google.com/file/d/1ce3GAkEQqEVaGgmblQiZ9TdlziDDj8BO/view?usp=sharing</strong>


# Run Server
To run Flask server install required python packages

<strong>pip3 install -r requirements.txt</strong>

Run code blocks of Deploy.ipynb and send a request to the server using

This will return an image file

<strong>curl.exe -X POST -F image=@test.jpg 'http://localhost:5000/api/test' --output test.png</strong>

This will return a .json file

<strong>curl.exe -X POST -F image=@test.jpg 'http://localhost:5000/api/test' --output output.json</strong>


# Predictions

![Binary Image](https://github.com/ahsan44411/YOLO-Object-Detection/blob/main/yolo%20prediction.JPG)
