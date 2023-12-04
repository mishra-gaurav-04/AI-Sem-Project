# Yoga pose detector

```
pip3 install -r requirements.txt
```

## Dataset link
http://download.tensorflow.org/data/pose_classification/yoga_poses.zip

## To run
1. Extract and download the dataset to data
2. ``` python3 train.py -i data/train -o data.csv ```

3. ``` python3 neuralnetwork.py -i data.csv -o model.h5 ```
4. ``` python3 inference.py --model model.h5 --conf 0.75 --source 0 ```


# Members
1. Gaurav Mishra
2. Prateek Parmar
3. Saarthak Verma
4. Sameep Aher