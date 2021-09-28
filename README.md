# Measure-Me

Measure-Me is an app concept developed to extract measurements such as height, waist, chest, and others via images without going through the hassle of measuring tapes.

<br>

Two methods were used. The first identifies a reference object in the image and calculates the number of pixels needed to make up 1 cm. Then the top and bottom point of a person is located to count the pixels and then calculate the final height. Similarly, the second method produces the same types of calculations however the identification of the object and person’s top and bottom points is done more manually by the user themselves.

<br>

Both methods were slightly off with the manual method doing a bit better. However, the room for improvement is much bigger for the first method especially if a pre-trained model that detects the outline of a human body existed/were to exist.
