1. The repository contains the architechtures for SFNet and Segformer model. The choice of the models can be done with the config.yaml files inside the "configs" folder. 

2. The segmentation_handler.py file contains the inference handler for the the models. The output recieved from the get_seg_map function is a segmentation map which contains all of the classes.

3. To change the architechture just change the config file path in the inference handler and you are good to go.

4. Command for training the model is:
python train.py --cfg <path to cfg file>