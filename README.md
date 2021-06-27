# image_recognition project by Ferry Liekens and Frank Ladage
<p>This project consist of a set of notebooks helping through the installation of our own image recognition project. Not all notebooks are necessary to run the project, but are there to help create a set of images and label them. The code is made as generic as possible so it would be easier to set it up.

## Steps
<br />
<b>Step 1</b> Clone this repository: https://github.com/ferryliekens/image_recognition.git
<br/><br/>
<b>Step 2</b> Create a new virtual environment
<pre>
python -m venv imagerecognition
</pre>
<br/>
<b>Step 3</b> Activate your virtual environment
<pre>
.\imagerecognition\Scripts\activate # Windows
</pre>
<br/>
<b>Step 4.</b> Install pip and add virtual environment to the Python Kernel
<pre>
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=imagerecognition
</pre>
<pre>
pip install jupyter
jupyter notebook
</pre>
<br/>
<b>Step 5 (Optional)</b> Follow intructions in notebook 'Image capturing and labeling' to create and label images.
<br/>
<b>Step 6.</b> Manually divide collected images into two folders train and test. So all images and labels should be split between the following two folders:<br/>
\image_recognition\Tensorflow\workspace\images\train<br />
\image_recognition\Tensorflow\workspace\images\test
<br/><br/>
<b>Step 7.</b> Follow intructions in notebook 'Install dependencies' for installing all nessesary libraries.
<br /><br/>
<b>Step 8.</b> Follow intructions in notebook 'Install pretrained model and train model with new images' to get everything ready for the image recognition
<br /> <br/>
<b>Step 9.</b> Follow intructions in notebook 'Run Realtime-image-recognition' to see the image recognition AI in action!
<br />
