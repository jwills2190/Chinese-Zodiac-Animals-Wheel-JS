### Chinese Zodiac Animals with Spinning Wheel and Slider

This Chinese Zodiac Animals project is an educational interface where divs for each of the 12 animals of the Chinese Zodiac are made in the DOM dynamically, using JavaScript
The code loops an array of 12 animal objects, and makes a div for each one. Inside each div go several elements, including images and text.
There is a sound icon which when clicked plays the pronunciation of the animal in both English and Chinese.
There is also an input box to enter either the English or Chinese Pinyin (Romanization) version of the name.
There is also a spinning wheel depicting the 12 animals of the Chinese Zodiac. The wheel spinning is handled by ##setInterval()** which runs 40x per sec, and rotates the weheel by a set increment each time.
There is a **slider control** (input element of type **range**), which calls a function every time the slider is changed. The function sets the wheel speed.
