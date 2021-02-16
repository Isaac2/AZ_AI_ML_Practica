Install libraries:
    pip install sklearn
    pip install mahotas
    pip install --upgrade scikit-learn==0.22

    pip install numpy
    pip install cv2
    pip install h5py


Run instructions:

1.- To download for the very first time the data you need to run:
python download_flowers.py

2.- Remember a folder named "output" must exist! before running main.py

3.- To train the data set you need to run (trained models will appear in output/ folder)
python main.py

4.- To test and compare different algorithms you can run
python train_test.py

5.- If you want to test with your own images, put .jpg format images in dataset/test/ folder.
    Then run:
python final_test.py