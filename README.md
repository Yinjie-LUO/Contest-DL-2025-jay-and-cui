# Contest-DL-2025-jay-and-cui

These codes are submitted for the DL-Fall-25 Kaggle Contest. Our team name is "jay and cui", consisting of two members, Xiangyu Cui and Yinjie (Jay) Luo.


### Methods
We provide two training methods to improve the model performance, namely conventional refining training and masked training.

In the conventional refining training, we trained on the 0-500k samples during Round 1 and the 500k-800k samples during Round 2. The accuracy of "submission.csv" on Kaggle is 0.83886.

In the masked training, we trained on the 0-200k samples during Round 1 and the 200k-400k samples during Round 2. The accuracy of "submission.csv" on Kaggle is 0.85737.


### Files

- Refined_Training_Round1_0_500k.ipynb : conventional refining training for the 0-500k samples.

- Refined_Training_Round2_500k_800k.ipynb : conventional refining training for the 500k-800k samples, which should be run after "Refined_Training_Round1_0_500k.ipynb".
  
- Refined_Training_Masked_Round1_0_200k.ipynb : masked training for the 0-200k samples.

- Refined_Training_Masked_Round2_200k_400k.ipynb : masked training for the 200k-400k samples, which should be run after "Refined_Training_Masked_Round1_0_200k.ipynb".

- Accuracy_Test.ipynb : used to test the prediction performance of a trained model and generate the "submission.csv" file.

- unmasked_train_loss.txt : training losses of the unmasked model over epochs.

- masked_train_loss.txt : training losses of the masked model over epochs.

- unmasked_val_acc.txt : validation accuracies of the unmasked model over epochs.

- masked_val_acc.txt : validation accuracies of the masked model over epochs.


### Trained Models

- The trained unmasked model can be downloaded from [here](https://drive.google.com/drive/folders/1vOwyg9pJbJYFNL8_h47lgLs__eP4n1Kk?usp=sharing).

- The trained masked model can be downloaded from [here](https://drive.google.com/drive/folders/1u4A1Uq5IK7nDpQirZTc3sbTTniqqC48L?usp=sharing).


### Results

<img width="865" height="649" alt="image" src="https://github.com/user-attachments/assets/c4ecdafa-82fb-4faf-9cab-e78833c40b24" />

<img width="865" height="649" alt="image" src="https://github.com/user-attachments/assets/d7bf6eaa-f951-4b47-8fb3-e5d0b5d7bd82" />

