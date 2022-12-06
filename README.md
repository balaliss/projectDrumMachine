# projectDrumMachine
 drumMachineProject
# Project: Drum Machine

![drum machine example](./drumMachineExample.png)

## Description:
You will be building a drum machine with React and Redux. Your drum machine will have clickable buttons that each play a unique audio clip. Audio clips can also be played with certain keys from your keyboard. Whenever an audio clip is played, its name will appear in your drum machine's display. Each element of this project will be rendered from React components, and all data will be stored in state with Redux. Your project should have a minimum of 9 buttons/sounds, but having more is fine.

## Key Concepts:
- Creating reusable components with React
- Rendering components to the DOM
- Rendering multiple elements from one component
- State management with Redux
- Using React with Redux

## User Stories:

- [ ] User Story:  I should be able to see an outer container with a corresponding id="drum-machine" that contains all other elements.

- [ ] User Story:  All of the elements in my drum machine should be rendered from React Components.

- [ ] User Story:  Within #drum-machine I can see an element with a corresponding id="display".

- [ ] User Story:  Within #drum-machine I can see 9 clickable drum pad elements, each with a class name of drum-pad, a unique id that describes the audio clip the drum pad will be set up to trigger, and an inner text that corresponds to one of the following keys on the keyboard: Q, W, E, A, S, D, Z, X, C. The drum pads MUST be in this order.

- [ ] User Story:  Within each .drum-pad, there should be an HTML5 audio element which has a src attribute pointing to an audio clip, a class name of clip, and an id corresponding to the inner text of its parent .drum-pad (e.g. id="Q", id="W", id="E" etc.).

- [ ] User Story:  When I click on a .drum-pad element, the audio clip contained in its child audio element should be triggered.

- [ ] User Story:  When I press the trigger key associated with each .drum-pad, the audio clip contained in its child audio element should be triggered (e.g. pressing the Q key should trigger the drum pad which contains the string "Q", pressing the W key should trigger the drum pad which contains the string "W", etc.).

- [ ] User Story:  When a .drum-pad is triggered, a string describing the associated audio clip is displayed as the inner text of the #display element (each string must be unique).

- [ ] User Story:  Each .drum-pad element's id, name, audio info and key info should be stored in state using Redux

- [ ] User Story: Include a markdown file in your project folder that includes
  * Your name
  * Name of the project
  * Why you are creating the project (because it was assigned is not a good answer)
  * Two enhancements you would like to make on your project in the future 

- [ ] User Story:  When your project is completed, delete the node modules folder, and submit your project folder to the shared drive here:
- 
```
SharedDrive > build > am|pm > DrumMachine
```

### Resources

- A folder of sounds for you to use is provided in the sounds folder

- Reference the example image if you are looking for design inspiration