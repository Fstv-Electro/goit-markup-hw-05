# goit-markup-hw-05
 
Project
"A1" All styles are written in one styles.css file, which is located in the css folder.

"A2" Source code formatted with Prettier.

"A3" All images and textual content are taken from the layout.

"A4" The modern-normalize style normalizer is connected to all HTML pages.

"A5" The code is written in accordance with the instructions.

"A6" The script of the modal window is connected in HTML, by a separate file modal.js.

Marking
"B1" Completed HTML markup of all layout elements.

"B2" Tags are used according to their semantic content.

Design
"C1" Transitions are made for all hover and focus effects (color, background, shadow). Time - 250ms, time distribution function - cubic-bezier(0.4, 0, 0.2, 1).

"C2" Animated properties are explicitly marked in transitions and animations. Nothing matters anywhere.

"C3" In the What we use section, the text with the background is a positioned image of the surface.

"C4" In the main navigation, with the help of the ::after pseudo-element, the link of the current page (on which the user is currently located) is underlined.

"C5" Blue text overlay on Portfolio page cards appears when hovering anywhere on a card.

"C6" The blue overlay on the Portfolio page cards visits the bottom as shown in the video.

card preview
"C7" Pseudo-elements are missing text content in the content property. They are used exclusively for decorative purposes.

Modal window
"D1" Completed marking and design of the "backdrop" (dark translucent background) of the modal window.

"D2" "Backdrop" fills 100% of the height and width of the browser viewport and is fixed in it.

"D3" Finished marking and decoration of the fashionable window.

"D4" Modal window vertically and horizontally located in the center of the backdrop.

"D5" Finished marking and design of the modal window close button in the upper right corner.

"D6" Initial modal window and backdrop, hidden using is-hidden class on backdrop, whose selectors have visibility, opacity, and event pointer properties.

"D7" If you remove the is-hidden class from the backdrop, the backdrop and a modal window appear.

"D8" The appearance and hiding of the mod window is animated using a transition with a free effect, such as scale or translation, and opacity.

Opening/closing the fashion window
A modal window with an application form opens when you click on the "Order service" button. In order for the script to work, it is necessary to add special attributes to the markup, by which the script searches for elements:

data-modal-open - on the modal window opening button.
data-modal-close - on the button to close the modal window.
data-modal - on the backdrop of the modal window.
Then, before the closing body tag, add a script tag with a link to the script file for the modal window. You can watch the video instruction.