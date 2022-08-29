# Day 1 Notes

## HTML Elements & Attributes
- `<kbd>``</kbd>` 
  - Keyboard Input element is used to define keyboard input by a user in a document. 
  - The input can be from a keyboard, voice input, or other text input device
- `data-` attribute 
  - is used to store data custom to the page or application which can then be used in the page's JS.
  - Global attribute 
- `<audio>` 
  - element is used to play an audio file on a page or application. 
  - comes with its own JS methods like `audio.play()`
- `attribute selector` 
  - used to target elements with certain attributes using CSS

## Javascript

- Get the element you're listening for: `window`
- Event: `keydown`
- Use interpolation to name the `data-key` attribute selector dynamic
- If no audio element associated with a key pressed, `null` is displayed in the console.log. 
  - Stop the function from running in this scenario with `if (!audio) return;` all on one line
- use `audio.play()` method to start playing the current audio
- `transitionend` event
  - event fired when a CSS transition has completed and reverted to its original/default state
  - use within the `addEventListener()` method
- `transform` CSS property lets you rotate, scale, skew, or translate an element. 