# An-Odd-Music-Generator
Music generater with Denoising Auto encoder

## Description
**Project name: An Odd Music Generator**

  the project has 4 main parts which should be done in a loop to generate the output song:
  
  <div align="center"><img src="https://github.com/amirkasaei/RNN-An-Odd-Music-Generator/blob/main/steps.png?raw=true" width="70%" /></div>
  
  1) Denoising:
    During the performance, the musician must pay full attention to the sound of the music and must not allow noise and
    the sound of crowd cheering (!) destroys his concentration.
    
  2) Note Recognition:
    During the performance, the musician must remember in his mind the series of notes he performed
    To know what notes he has hit in the performance of a piece up to every moment.
    
  3) Note Prediction:
    During the performance, the musician must keep in mind the series of notes that are being performed up to the moment
    predict the next note to sound it.
  
  4) Noise maker:
    Naturally, since the crowd in the hall is not covered in pleasure, during the performance
    classical music with hands and whistles encourage your music production.
  
## Dataset
the dataset contains three parts:
1) notes
2) noises
3) songs (sequence of note names)

    
Neural Network models implemented by Keras in Tensorflow library.

## Team members

- Amir Kasaei     
- Amir Ezzati   
  
**This project was a pair work that we wrote as final project of Deep Learning course at University of Guilan in May 2022.**
