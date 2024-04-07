1) Open anaconda prompt.The environment is pl.

2) Copy the path and paste it like,"cd (the path of your source file).

3) Type: "conda create -n tf python=3.7 anaconda" #to activate environment python=3.7.

4) "python src/save_data.py --name (name of save_dir)" #to train a new face using webcam.

5) "python augment_data.py" #augmentation of that new face.

6) "python train_embs.py" #to embed the new face.it will take some time.

7) "python train_classify.py" #to classify the embeded face and calculate the loss, accuracy.

8) To run: "python stream_recognition.py" #to detect the person using webcam, if you already train that face it will detect the person.

Output:

---> If person is not register, it will show "Red color" Boundy Box and in prompt it will print"Error! Unknown Person".
---> In Additionly, we can add "Alarm" if unauthuorised person detected on webcam.
	Note:Once the Alarm is ON, the webcam getting slow to show.

Thanks for watching

By, 
1 crore projects...