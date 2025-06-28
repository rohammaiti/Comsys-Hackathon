# Comsys-Hackathon
This is the repository of team Code Crusaders. This contains all the necessary files and folders of Task A and Task B with related documents

We are sharing the google drive link which contains weights of the models used in task A and task B along with their output. For task A
it is reccomended to use the "densenet169_gender_best.keras" file for evaluation and "siamese_best_model.keras" for task B. For task A
one can enter both the directory path along with the weights file or the image to get predicted output. For task B, one can enter the
test data path, for this purpose. Both the models were made on Google Colab and executed using T4-GPU.

Task A output and weights link- https://drive.google.com/drive/folders/1j4aJOwmrCxRmy0asjzZscM4LSmQgi-SF?usp=sharing
Task A Google Colab code link- https://colab.research.google.com/drive/19Dr9bl1hOxAFBTH3W932CMks9yNRgY7A?usp=sharing

Task B output and weights link- https://drive.google.com/drive/folders/1cNURexLmokQfGTiAA2pwRQ8R3XftHjlk?usp=sharing
Task B Google Colab code link- https://colab.research.google.com/drive/1rS20lb8LM3fagpVZ41BLVH4SxnpTqSaX?usp=sharing

To evaluate test data, enter test data in the last cells of the colab files after execution. The run time for Task A is approximately 40 minutes
and for Task B it is nearly 3 hours.


For Task A, we have achieved an accuracy ranging between 91-92 percent. 
Males: Precision- 93%, Recall- 96% and F1 score- 95%.
Females: Precision- 86%, Recall- 79% and F1 score- 83%.

For Task B-
Top-1 Accuracy: 94.65 %
Macro Precision: 100.00 %
Macro Recall: 94.65 %
Macro F1 Score: 97.25 %
