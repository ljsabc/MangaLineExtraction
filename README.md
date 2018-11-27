Manga Line Extraction
--------------

## erika_unstable.h5(weight)

To download the file please follow this link:
https://www.dropbox.com/s/m1f5n8xbrpkl37r/erika_unstable.h5?dl=0
Please use this file as the pre-trained weight for testing.


## Requirement

+  Python3
+  keras==1.2.0 (1.2.2 is okay too)
+  theano==0.9
+  python-opencv
+  h5py
+  cuda is optional but highly recommended

It's strongly recommended to use virtualenv to build the testing environment.


## Forward Compatibility

As this project is build against theano, you need to modify the dim orderding into "th"/"channels_first" in your keras.json.

For details of testing with latest version of tensorflow, please refer to #1 .

## Usage

        test_mse.py [source folder] [output folder]

Example:

        test_mse.py ./Arisa ./output

The outputs will be clipped to 0-255.




For more details please take a look at the source files. Thanks.
