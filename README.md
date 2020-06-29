# Machine-Learning---Twitter-User-Gender-Classification

#To run, open "ProcessedData.ipynb" and run all the cells (comments in code)
#	We are predicting how well do words in tweets and profiles predict user gender?

## This data is downloaded from the site https://www.kaggle.com/crowdflower/twitter-user-gender-classification















Anaconda3 Version 2018.12 was used to install the packages for our experiments.
To get the Anaconda3 installer run 'wget https://repo.continuum.io/archive/Anaconda3-2018.12-Linux-x86_64.sh'
To install all necessary Python packages download and run the Anaconda3 install file:
 './Anaconda3-2018.12-Linux-x86_64.sh' followed by: 
'conda install -c conda-forge --file requirements.txt' from inside of the 'icml_paper2626_code' folder. 
NOTE: installing the packages from the requirements file will only install a CPU-only version of Jax. 
Unfortunately, installing the GPU compatible version is dependent on the system architecure of the machine being used, 
as well as the CUDA and Python versions used by the system. 
Instructions on installing the GPU version of Jax can be found at: https://github.com/google/jax#installation.
In our case we used CUDA 10.1 with the install command:
'pip install --upgrade $BASE_URL/$CUDA_VERSION/jaxlib-0.1.31-$PYTHON_VERSION-none-$PLATFORM.whl'
Note that we force version 0.1.31 in the pip install above.
In addition it may be necessary to enforce jax version 0.1.50. These versions of Jax and Jaxlib are compatible

