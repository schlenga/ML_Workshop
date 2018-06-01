Part 4: Google Inception, Transfer Learning and Data Acquisition
=====

Google Inception v3 looks like this:

![Inception](inception.png)

We use transfer learning to retrain the last layer.

**Data Acquisition Session**

We use a little Python script to control the retraining:

```
python3 retrain.py --image_dir Folder/To/Images
```

That takes about half an hour again.

(With -h you can check for all the options that script has.)

Afterwards, you can make predictions with another script:
 
```
python3 label_image.py --graph=/tmp/output_graph.pb --labels=/tmp/output_labels.txt --input_layer=Placeholder --output_layer=final_result --image=Path/to/image/file.jpg
```