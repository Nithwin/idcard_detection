# ID CARD AND PEOPLE DETECTION

## Preparing the Dataset and Training It

To train the model, we first need a dataset. For this project, we created a dataset by capturing images of our students wearing ID cards. Additionally, we obtained a publicly available people dataset online. Both datasets were merged using Roboflow, where the images were annotated and augmented. This processed dataset was then used to train the model using the YOLOv8 algorithm.

## Running the Model

To run the model, use the following command:

```bash
python main.py
```

