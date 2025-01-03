# nigerian-plate-number-recognizer
An automatic plate number recognition system for Nigerian plates

There are seven primary algorithms that the software requires for identifying a license plate:

- Plate localization(object detection) – responsible for finding and isolating the plate on the picture
- Plate orientation and sizing – compensates for the skew of the plate and adjusts the dimensions to the required size
- Normalization – adjusts the brightness and contrast of the image
- plate regions segmentation - segment the plate into different parts to remove the text only
- Character segmentation – finds the individual characters on the plates
- Optical character recognition
- Syntactical/Geometrical analysis – check characters and positions against country-specific rules
- The averaging of the recognised value over multiple fields/images to produce a more reliable or confident result, especially given that any single image may contain a reflected light flare, be partially obscured, or possess other obfuscating effects.