# Chatbot

Execution instructions - 

Download the data from the link - https://drive.google.com/open?id=1_aln9rsWg_uKilEwssDHgEUzmjBj4FDh
and extract the archive into ./data in the project folder.

Run the notebook till the training cell.

In order to execute the last predictions cell, replace the directory name in the ./runs folder to the relevant number generated after running.
Make the relevant change in the line - 
estimator = tf.contrib.learn.Estimator(model_fn=model_fn, model_dir='./runs/1525381531') of the last cell.

This will give the required results.
