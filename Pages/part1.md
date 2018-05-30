Part 1: Playing around with the ideas
======

Machine Learning is hidden from the user most of the time, even though it powers many modern applications.

So, before we get into the actual details, we look at some different implementations of ML.


## Your phone assistants

If you have a modern Android or iPhone (and activated the assistant features), you have access to Siri or the Google Assistant.

If possible:

- form pairs of people having access to Siri and Google Assistant (+x)
- explain to each other if and how you use those tools
- try to make a little comparison: what works well, what doesn't, are there notable differences in user guidance/addressing etc

## Birdseye view on Machine Learning

The basic flow of ML is as follows:

0. Define the application, environment, kind of things that you want the machine to learn. Define what you want to achieve with the trained machine, in what environment, how often...
1. From that, build the model (what kind of machine do you need?)
2. Get data. A lot.
3. Pre-process the data so that your model can work with them
4. Let the model train on the data, all the time evaluating on a test sample of data
5. When the model is good enough, test again on a fresh set of data
6. Maybe repeat 
7. Deploy

## Tensorflow.js

Visit [tensorflow.js](https://js.tensorflow.org/). We look at a couple of examples there.

### Play around with the [Emoji Scavenger Hunt](https://emojiscavengerhunt.withgoogle.com/)

If you know how to code, take a look at the "code" section. 
How well does the game work?

### Play around with the [Piano](https://magenta.tensorflow.org/demos/performance_rnn/index.html)

If you know how to code, take a look at the "code" section.
What do you notice about the music?


### Main parts

Form two groups.
Each group checks out one of the two examples below.
Afterwards, you present the example and your findings to the other group.

#### The [Teachable Machine](https://teachablemachine.withgoogle.com/)

Group 1 looks at the teachable machine. You can collect image data with your webcam and make the machine produce an output (that you can choose), whenever it detects the given image data.

Here are a couple of ideas what you can do with it

- Teach the machine to say the names of people/items (you can enter words that will then be spoken upon detection)
- Teach the machine to show funny gifs that match your pose
- Play an air instrument and let the machine produce the correct sounds for that instrument

Test the machine!

- How good is the face recognition? Can you fool it?
- Can you improve the recognition somehow?
- How similar can the different inputs be to still be discerned?
- What happens when the camera only sees the background?

#### [Posenet](https://storage.googleapis.com/tfjs-models/demos/posenet/camera.html)

Group 2 looks at posenet. The machine is already trained to detect body parts. 

Here are a couple of ideas what you can do with it:

- Have a look at one or different people (there are the settings "single" vs "multipose")
- What does the machine detect, what doesn't it detect?
- How quick is it? 
- Under what circumstances does the machine fail to detect poses? (Think lighting, angle, clothes, background etc)
- What does the machine do when you're not in the picture?


### Now play PACMAN with [PACCAM](https://storage.googleapis.com/tfjs-examples/webcam-transfer-learning/dist/index.html)

Make pairs of one member of each group.

Use what you learned about training a machine to train the controller of the Pacman example. Make sure it works well for both of you.

Play! If you want, we can have a little tournament before the...

## BREAK! Let's have coffee and a chat about your ideas what ML can do!

After that: [Part 2!](Pages/part2.md)