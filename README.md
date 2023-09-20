<a name="readme-top"></a>
# TFM-Drowsiness_detector
## About The Project

The "Drowsiness Detector" project originated as an idea for a Master's Thesis in Big Data & Business Analytics by a group of students from the Complutense University of Madrid: Beatriz Cuesta, Antonio Fernández, Federico Golffeld, Alejandro Lema, Álvaro López, and Ginés Meca. Together, we have developed a fatigue detector with the intention of implementing it in smart cars to prevent accidents caused by driver drowsiness. 

The product is a real-time predictor of user's drowsiness that works through the computer webcam, and tries to replicate the way how it would work in a real driving situation.

The model used is a Convolutional LSTM that uses the frames extracted from the camera and some face features obtained through the [Google's Mediapipe library](https://developers.google.com/mediapipe)


### Built With

The code has been developed using Python and the libraries that are specified in the `requirements.txt` file.


## Getting Started

To use the product, only is needed to install python along with the requirements.

### Installation

To set up this project, you'll need to create a Conda environment and install the required dependencies from the `requirements.txt` file.

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/GinesMeca/TFM-Drowsiness_detector.git
   ```
   
2. Navigate to the project directory:
   
   ```
   cd your-project
   ```
3. Create a Conda environment (if not already created) and activate it:
   ```
   conda create --name myenv python=3.8
   conda activate myenv
   ```

4. Install the required dependencies from the requirements.txt file:
   ```
   conda install --file requirements.txt
   ```

Now, your Conda environment should be set up with all the necessary dependencies.

To deactivate the Conda environment when you're done with your project, you can use:

   ```
   conda deactivate
   ```

For more details on managing Conda environments, refer to the [Conda documentation](https://docs.conda.io/en/latest/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Usage

Once the environment is succesfully configured, to run the latest version of the model you need to set as an environment variable the path of: `drowsiness_config_CNN.config`.

In the same folder, there are two more configs by default that you can try, although they should work worse than the previous one. Also, you can play a bit with these configs, changing values like fps number, number of frames by prediction... Nevertheless, note that most of the params given through the config (for example: frame size, rgb or gray scale, model init frames...) are set according to the trained models included. Changing them can become an error.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## License

This project is licensed under the [Creative Commons Attribution-NonCommercial License](LICENSE). See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Beatriz Cuesta - [LinkedIn profile](https://www.linkedin.com/in/beatriz-cuesta-munizaga-786b08145/) - bcuestam@gmail.com

Antonio Fernández - antoniofm99@gmail.com

Federico Golffeld - [LinkedIn profile](https://www.linkedin.com/in/fgolffeld/) - f.golffeld@gmail.com

Alejandro Lema - [LinkedIn profile](https://www.linkedin.com/in/alex-lema-0850b99b/) - lema.madrid@gmail.com

Álvaro López - [LinkedIn profile](https://www.linkedin.com/in/alvaro-lopez-benito/) - alvarolopezb94@gmail.com

Ginés Meca - [LinkedIn profile](https://www.linkedin.com/in/gin%C3%A9smeca/) - ginesmeca11@hotmail.com

Project Link: [https://github.com/GinesMeca/TFM-Drowsiness_detector](https://github.com/GinesMeca/TFM-Drowsiness_detector)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Main resources:

* [ConvLSTM](https://paperswithcode.com/method/convlstm)
* [Mediapipe](https://developers.google.com/mediapipe)
* [Face landmarks with Mediapipe](https://developers.google.com/mediapipe/solutions/vision/face_landmarker)
* [pygame](https://www.pygame.org/news)
* [PyCharm](https://www.jetbrains.com/es-es/pycharm/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



