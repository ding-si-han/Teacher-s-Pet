# Teacher's Pet 
Teacher's Pet is employs 3 key Tensorflow.js models to predict engagement values of students in classrooms (enter _/computer-vision-models_ folder)
1. Emotion Detection
2. Head Gaze
3. Human Pose Estimation

## Setup
1. Navigate to the individual folder
2. Install VSC Live-server extension
3. Open html file and click **go live** button at the bottom right hand corner
4. Ensure that download location (See useful link: https://www.google.com/amp/s/windowsreport.com/download-overwrite-existing-files/%3famp) 
5. Download chrome extension to override download names (https://chrome.google.com/webstore/detail/downloads-overwrite-alrea/lddjgfpjnifpeondafidennlcfagekbp)
6. Each model should download a CSV file every 5 seconds.

We have attached here the flask server that predicts engagement values should you require it and can be executed with the following command in  _/neuralnet-flask-server_: 
<pre><code>$ python3 app.py </code></pre>



