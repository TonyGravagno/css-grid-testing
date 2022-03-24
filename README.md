# css-grid-testing
Experimenting with CSS Grid

This is for personal education and is not a part of a larger project.
If you are learning about CSS Grid this will almost certainly provide **some** sort of enlightenment.

File index.html shows (essentially) the same form, rendered width CSS Grid in various ways.  
The goal is to understand flow, nested grids, and how to reset the UI based on media/device viewport changes.  
This will help with later initial design of forms that adapt responsively.

Comments and optimizations are welcome. Please create a ticket to discuss. Thanks!

Forms 1,2, and 4 demonstrate obvious issues that need to be addressed.

Forms 1 and 2 combine a vertical layout with a nested group of horizontal controls, which is common in many applications.

Form 1 is not responsive. Form 2 is highly responsive, adapting to many changes in form factor.

Form 3 shows an initial adaptation that stops when the input control is up against the label - an indication that more adaptation is required.

Forms 4 and 5 have a pure vertical format.

Form 4 is not responsive. Form 5 is to show a before/after contrast.

At the smallest viewports, form 2 shifts from the vertical+horizontal format to the same vertical-only configuration as form 5. The forms are identical in structure until the very smallest viewport where form 2 further adapts control sizes to the viewport, where form 5 overflows.

The red border around controls is only there to show the width of grid cells versus the width of the controls within. Of course this should be removed.

# Testing

To actually see how this works, I'll provide info about my specific environment and you can adapt as required...

- Clone the repo to a local folder.
- Get the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) VSCode extension.
- Open the folder in VSCode and save as a workspace.
- Open index.html and then Go Live. This opens a browser.
- Expand and shrink the container width to see some responsiveness.
- User Ctrl+Shift+M to open Responsive testing.
  - The viewport becomes a container within the browser window.
  - This viewport has a resize handle in the bottom right for manual adjustment.
  - You do Not need to manually select specific devices, though you can if that helps with your current efforts.
- Note the viewport breakpoints in styles.css and manually resize the width to see how each form behaves. See above for expected behaviors.

# To Do

At this point, nothing. Random changes might be made at any time. I'll note in commits if something is enhanced or broken.

Comments and suggestions are certainly welcome but since this is purely for personal testing I won't process requests for enhancements or questions about how it works. Please post questions to Stack Overflow, ref this repo if you wish, and let me know in an issue or Twitter that something is up so that I can at least keep up with the topic. Or you can [@ mention me in SO](https://stackoverflow.com/users/190955/tonyg) so I get a notification there : 
# License

This project has no license and is released to the public domain.  
A tweet to @tonygravagno would be appreciated if this is helpful.  
No support or warranty of any kind is implied or provided.


