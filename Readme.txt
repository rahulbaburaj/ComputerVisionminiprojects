OpenCV is required for all the projects. 

Yawn Detector Live and  Face Swapper
You need to install dlib (http://dlib.net) including its Python bindings. You'll also need to obtain the trained model from http://sourceforge.net/projects/dclib/files/dlib/v18.10/shape_predictor_68_face_landmarks.dat.bz2
Unzip with `bunzip2` and change `PREDICTOR_PATH` to refer to this file. The script is run like so:
	 ./faceswap.py <head image> <face image>
'output.jpg' will be produced with the facial features from `<head image>` replaced with the facial features from `<face image>`.

