## Multi-Scale Coarse-to-Fine Optical Flow for Accurate Motion Detection
The goal of the project is to get familiarize about the optical flow which is the most general and challenging version of motion estimation. It involves computing an independent estimate of motion at each pixel.

Using Lukas-Kanade algorithm, optical flow is calculated for the Middlebery Optical Flow Dataset. The method to calculate optical flow are written from scratch to get an in-depth knowledge of the Lukas-Kanade algorithm.

This method is further extended to calculate Multi-Scale Coarse-to-Fine optical flow which helps to capture large displacements among the frames. It solves the aperture problem to some extent encountered by Lukas-Kanade method. 

Program to calculate optical flow and observations derived from the results are present in optical_flow.ipynb

### Instructions
- Follow the directory structure as shown below: 
  ```
  ├── src           
        ├── optical_flow.ipynb
  ├── results  //storing outputs
  ├── docs 
        ├── report.pdf  //analysis of results
        ├── solutions.pdf //handwritten solutions 
  ├── data  //provided data
  ├── Problem Statement.pdf
  └── README.md
  ```
- `src` contains the Jupyter notebook(s) used for the project.
- `docs` contains final report and  docs on some though expiriments to analyze the optical flow
- `data` contains images as frames of continous video to calculate optical flow 


## Middlebery Optical Flow Dataset
- `all-frames-colour` : All frames in colour
- `ground-truth` : Groundtruth flow
- `ground-truth-interp` : Groundtruth flow interpolation
-  `usseq.mat` : Ultrasound sequence

