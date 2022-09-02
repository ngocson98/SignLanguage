# Sign Language
##1. Setup
- Install Mediapipe examples
- Modify Mediapipe
After Download, you must look for 3 files in that with the same name in "modified_mediapipe" and replace them.
##2. Create training data
- Make folder trainvideo and folder traintxt (empty directory) for each sign language word in 1 folder. Run build.py to get txt and file .mp4 output with hand tracking. You must 100 video per 1 word to train.
- NOTE: (DO NOT use space, '_' to your folder name)
##3. Trainning LSTM model
- Open model.ipynb.
- The model is saved as model.h5, download your computer.
##4 Result.
- Run main.py
- GUI appear.
- Step1: Choose Input video directory (folder)
- Step2: Input video file (mp4)
- Step3: Output Video file (folder)  --> Open input video (watching)
- Step4: click "Hand Mediapipe Process" ... waiting.... "success!"
- Step5: Output video file --> (choose file video output .mp4)  --> test by click (Open output video)  (hand tracking)
- Step6: Click Output directory --> choose 'Relative'
- Step7: Click "Predict sequece",


