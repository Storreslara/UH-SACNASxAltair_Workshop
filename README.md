# SACNASxAltair_Workshop


1. Visit the Anaconda download page: https://www.anaconda.com/products/individual
2. Download the appropriate Anaconda installer for your operating system.
3. Follow the installation instructions for your operating system to install Anaconda.
   - Around the halfway point you will be prompted to enter yes or no, enter `y `(for yes and nothing bad will happen, I promise) 
4. Open the Anaconda prompt by searching for "Anaconda Prompt" in your computer's search bar. 
5. In the Anaconda prompt, create a new environment named "my_env" that runs Python 3.10 by running the following command:
   - Feel free to call your env whatever you want.
   - At some point the prompt will ask to enter ‘y’ to proceed, make sure you do that!
   
    
    `conda create --name my_env python=3.10`
    
6. Activate the new environment by running the following command:
   
   `conda activate my_env`
   
7. Install the following packages numpy, pandas, jupyter, scikit-learn, and Plotly in the environment by running the following command:

   `conda install -y numpy pandas jupyter scikit-learn plotly`
   
8. Wait for the packages to finish installing.
9. Go to the Git download page: https://git-scm.com/downloads, download and install your appropriate installer 
10. In your Anaconda prompt use the following command: 

    `git clone https://github.com/Storreslara/UH-SACNASxAltair_Workshop.git`
    
11. Go into the directory where you installed the repository. 

    `cd .\UH-SACNASxAltair_Workshop\`
    
12. In your Anaconda prompt run this command to start up Jupyter 

    `jupyter notebook`
