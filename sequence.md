[Return to home page](./README.md) 

# Table of Contents

The course is taught in a sequence of ten units.  Each unit takes between one
and two weeks so that the entire class can be fit into a single semester.
Most units currently have four components:
* **Lecture Notes**:  These are slides accompanying the class lecture.  They include code snippets
   from the demos.   Note that the lecture and unit numbering do not align.
* **Demo**: These are python-based [Jupyter notebooks](http://jupyter.org/)
   for demonstrations given during the lectures.  Some demos have a
   component that is done in class.  The demos do not generally cover
   all topics, since some concepts are left for the students to figure out 
   for themselves in the labs.
* **Lab**:  Following the lecture, the students do a python-based exercise at home
   that builds on the demo.
   The labs in the repository are given as skeletons with `TODO`
   markers that the students fill in.
* **Homework**:  These are more analytic problems, also done at home.

The homework and lab solutions are provided to students enrolled in the class.
If you are an instructor
and wish copies of the solutions for yourself,
please contact Sundeep Rangan at <srangan@nyu.edu>.

* [Setting up python, jupyter and github](./Basics/setup.md)
    * [Set up a local machine](./Basics/setup.md)
    * [Set up a virtual machine in Google Cloud Platform](./GCP/getting_started.md)
    * [Set up a virtual machine in Google Cloud Platform with Docker](./GCP/docker.md)
    * [Downloading the course material from github](./Basics/github.md)
      * For NYU students taking the course in Spring 2018 from Yao Wang, you should download the course material from this Forked Repo, to make sure that you have the updated material for the course. That is, you should replace "https://github.com/sdrangan/introml" by "https://github.com/yaowangatpoly/introml" in the above guide.
    * [Instruction for Fork the GitRepository and Make your own update and send pull request](https://github.com/ishjain/learnGithub/blob/master/updateMLrepo.md) 
    * [Basics of Python and Its Application for Image Processing through OpenCV](./Basics/PythonTutorial_ACK.pdf)
      * [Example codes and images used](./Basics/PythonSampleCodes.zip)
* Introduction
    * Course Admin [[pdf]](./lectures/CourseAdmin.pdf) [[Powerpoint]](./lectures/CourseAdmin.pptx)
    * S18 Course syllabus [[pdf]](./lectures/EL9123_IntroML_Syllabus_S18.pdf) [[Powerpoint]](./lectures/EL9123_IntroML_Syllabus_S18.pptx)
    * S18 Project Guideline [[pdf]](./lectures/ProjGuideline_S18.pdf) [[Powerpoint]](./lectures/ProjGuideline_S18.pptx)
    * Lecture 1:  Introduction to Machine Learning [[pdf]](./lectures/Lect01_IntroML.pdf)
     [[Powerpoint]](./lectures/Lect01_IntroML.pptx)    
* [Unit 1:  Simple linear regression](./unit01_simp_lin_reg/readme.md)
    * Lecture 2:  Simple linear regression [[pdf]](./lectures/Lect02_SimpRegression.pdf)
     [[Powerpoint]](./lectures/Lect02_SimpRegression.pptx)    
    * [Introduction to `numpy` vectors](./Basics/intro_vectors.ipynb)
    * [Demo 1:  Understanding automobile mpg](./unit01_simp_lin_reg/demo01_auto_mpg.ipynb)
    * [Lab 1: Boston housing data](./unit01_simp_lin_reg/lab01_housing_partial.ipynb) 
    * Homework 1 [[pdf]](./unit01_simp_lin_reg/hw/hw01_simp_lin_reg.pdf)
     [[Latex]](./unit01_simp_lin_reg/hw/hw01_simp_lin_reg.tex)
* [Unit 2:  Multiple linear regression](./unit02_mult_lin_reg/readme.md)
    * Lecture 3:  Multiple linear regression [[pdf]](./lectures/Lect03_MultLinRegression.pdf)
     [[Powerpoint]](./lectures/Lect03_MultLinRegression.pptx)    
    * [More `numpy`:  Python broadcasting](./Basics/numpy_axes_broadcasting.ipynb)      
    * [Demo 2:  Predicting glucose levels](./unit02_mult_lin_reg/demo02_glucose.ipynb)
    * [Lab 2: Calibrating robot dynamics](./unit02_mult_lin_reg/lab02_robot_calib_partial.ipynb)
    * Homework 2 [[pdf]](./unit02_mult_lin_reg/hw/hw02_mult_reg.pdf)
    [[Latex]](./unit02_mult_lin_reg/hw/hw02_mult_reg.tex)
* [Unit 3:  Model selection and regularization](./unit03_model_sel/readme.md)
    * Lecture 4:  Model selection [[pdf]](./lectures/Lect04_ModelSelection.pdf)
     [[Powerpoint]](./lectures/Lect04_ModelSelection.pptx)    
    * Lecture 5:  LASSO Regularization [[pdf]](./lectures/Lect05_Lasso.pdf)
     [[Powerpoint]](./lectures/Lect05_Lasso.pptx)         
    * [Demo 3.1:  Polynomial order selection with cross-validation](./unit03_model_sel/demo03_1_polyfit.ipynb)
    * [Demo 3.2:  LASSO regression for finding predictors of prostate cancer](./unit03_model_sel/demo03_2_prostate.ipynb) 
    * [Lab 3.1: Neural decoding motor cortex signals (feature selection based on correlation and cross validation)](./unit03_model_sel/lab03a_neural_partial.ipynb) 
    * [Lab 3.2: Student performance prediction (feature selection based on LASSO and other feature selection methods)](./unit03_model_sel/lab03b_student-performance_LASSO.ipynb) 
    * Homework 3.1 [[pdf]](./unit03_model_sel/hw/hw03_model_sel.pdf) [[Latex]](./unit03_model_sel/hw/hw03_model_sel.tex)
    * Homework 3.2 [[pdf]](./unit03_model_sel/hw/hw03b_LASSO.pdf) [[Latex]](./unit03_model_sel/hw/hw03b_LASSO.tex)
* [Unit 4:  Logistic regression](./unit04_logistic/readme.md)
    * Lecture 6:  Linear classification and logistic regression
    [[pdf]](./lectures/Lect06_LogisticReg.pdf)
    [[Powerpoint]](./lectures/Lect06_LogisticReg.pptx)         
    * [Demo 4:  Breast cancer diagnosis via logistic regression](./unit04_logistic/demo04_breast_cancer.ipynb)
    * [Lab 4: Genetic analysis of Down's syndrome in mice](./unit04_logistic/lab04_gene_partial.ipynb)
    * Homework 4 [[pdf]](./unit04_logistic/hw/hw04_logistic.pdf)
    [[Latex]](./unit04_logistic/hw/hw04_logistic.tex) 
* [Unit 5:  Nonlinear optimization](./unit05_optim/readme.md)
    * Lecture 7:  Nonlinear optimization and gradient descent
    [[pdf]](./lectures/Lect07_Optim.pdf)
    [[Powerpoint]](./lectures/Lect07_Optim.pptx)         
    * [Demo 5.1:  Computing gradients](./unit05_optim/demo05_1_computing_gradients.ipynb)
    * [Demo 5.2:  Simple gradient descent optimization](./unit05_optim/demo05_2_grad_descent.ipynb)    
    * [Lab 5: Audio pitch detection](./unit05_optim/lab05_audio_partial.ipynb)
    * Homework 5 [[pdf]](./unit05_optim/hw/hw05_optim.pdf)
    [[Latex]](./unit05_optim/hw/hw05_optim.tex)
* [Unit 6:  Support vector machines](./unit06_svm/readme.md)
    * Lecture 8:  SVM [[pdf]](./lectures/Lect08_SVM.pdf)
    [[Powerpoint]](./lectures/Lect08_SVM.pptx)         
    * [Demo 6:  MNIST digit classification](./unit06_svm/demo06_mnist_svm.ipynb)
    * [Lab 6: Extended MNIST with letters](./unit06_svm/lab06_emnist_partial.ipynb)
    * [Lab 6b: Extended MNIST digit and letter classification with image processing (optional)](./unit06_svm/lab06_emnist_2017_partial.ipynb)
    * Homework 6 [[pdf]](./unit06_svm/hw/hw06_svm.pdf) [[Latex]](./unit06_svm/hw/hw06_svm.tex) 
* [Unit 7: Neural networks with Keras and Tensorflow](./unit07_neural/readme.md)
    * Lecture 9:  Neural networks [[pdf]](./lectures/Lect09_NeuralNet.pdf)
    [[Powerpoint]](./lectures/Lect09_NeuralNet.pptx)         
    * [Demo 7.1: First neural network in Keras](./unit07_neural/demo07_1_synthetic.ipynb)
    * [Demo 7.2: MNIST neural network classification](./unit07_neural/demo07_2_mnist_neural.ipynb)
    * [Lab 7:  Music instrument classification](./unit07_neural/lab07_music_partial.ipynb)
    * [In-class Exercise](./unit07_neural/InclassExercise.ipynb)
    * Homework 7: [[pdf]](./unit07_neural/hw/hw07_neural.pdf) [[Latex]](./unit07_neural/hw/hw07_neural.tex)
    * Supplementary notes with solved problems [[pdf]](./unit07_neural/hw/supplementary_neural.pdf) [[Latex]](./unit07_neural/hw/supplementary_neural.tex)
      
* [Unit 8:  Convolutional and deep networks](./unit08_cnn/readme.md)
    * Lecture 10:  Convolutional and deep networks
    [[pdf]](./lectures/Lect10_ConvNet.pdf)
    [[Powerpoint]](./lectures/Lect10_ConvNet.pptx)         
    * [Setting up a GPU instance](./GCP/gpu_setup.md) (Recommended)
    * [Demo 8.1: 2D convolutions and convolutional layers in keras](./unit08_cnn/demo08_1_convolutions.ipynb)
    * [Demo 8.2: Creating an image set using the Flickr API](./unit08_cnn/demo08_2_flickr_images.ipynb)
    * [Demo 8.3: Exploring the deep VGG16 network](./unit08_cnn/demo08_3_vgg16.ipynb)
    * [Demo 8.4: Building an image classifier using CIFAR10 dataset](./unit08_cnn/demo08_4_classifier.ipynb)
    * [Demo 8.5: Building an autoencoder for image denoising using CIFAR10 dataset](./unit08_cnn/demo08_5_autoencoder.ipynb)
    * [Lab 8:  Transfer learning with a pre-trained network](./unit08_cnn/lab08_fine_tune_partial.ipynb)
    (GPU recommended)
    * Homework 8 [[pdf]](./unit08_cnn/hw/hw08_cnn.pdf) [[Latex]](./unit08_cnn/hw/hw08_cnn.tex)
* [Unit 9:  PCA](./pca/readme.md)
    * Lecture 11:  PCA [[pdf]](./lectures/Lect11_PCA.pdf), Modifed Note [[pdf]](./lectures/Lect11_PCA_modified.pdf)
    [[Powerpoint]](./lectures/Lect11_PCA_modified.pptx)         
    * [Demo 9:  PCA eigen-faces-SVM](./unit09_pca/demo09_eigen_face_SVM.ipynb)
    * [Lab 9a:  PCA with NN vs CNN](./unit09_pca/Lab09a_pca_NN_CNN_partial.ipynb)
    * [Lab 9: Movie recommendations](./unit09_pca/lab09_movies_partial.ipynb) (Not required) 
    * Homework 9 [[pdf]](./unit09_pca/hw/hw09_PCA.pdf) [[Latex]](./unit09_pca/hw/hw09_PCA.tex)
* [Unit 10:  Clustering and EM](./unit10_cluster/readme.md)
    * Lecture 12:  Clustering and EM [[pdf]](./lectures/Lect12_Clustering.pdf)
    [[Powerpoint]](./lectures/Lect12_Clustering.pptx)         
    * [Demo 10: Document clustering via k-means and latent semantic analysis](./unit10_cluster/demo10_doc_cluster.ipynb)
    * [Demo 10b: Color quantization via k-means and EM-GMM](./unit10_cluster/demo10b_kmeans_GMM_color_quantization.ipynb)    
    * Homework 10 [[pdf]](./unit10_cluster/hw/hw10_clustering.pdf) [[Latex]](./unit10_cluster/hw/hw10_clustering.tex)
* Unit 11:  Decision tree and random forest
    * Lecture 13:  Decision tree and random foreast [[pdf]](./lectures/Lect13_Trees.pdf)
    [[Powerpoint]](./lectures/Lect13_Trees.pptx)         
    * [Demo 11: Prediction of temperature using decision tree and random forest](./unit11_tree/decision_tree_and_random_forest.ipynb)
    * Homework 11 [[pdf]](./unit11_tree/hw/hw11_tree.pdf) [[Latex]](./unit11_tree/hw/hw11_tree.tex)
* Summary and Review 
    * Lecture 13: Review [[pdf]](./lectures/Lect13_Review.pdf)
[[Powerpoint]](./lectures/Lect12_Clustering.pptx)

