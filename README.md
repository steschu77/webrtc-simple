# WebRTC Simplest Example

This is a repository showing how to setup a very simple WebRTC call in just a few lines of code.

It demonstrates how a webcam can be shared between two browsers. It shows what a calling / media sending browser and a called / media receiving browser has to do respectively.

## How to Use

1. Open src/sender.html in a browser A. You should see a preview of the webcam.
2. Open src/receiver.html in a browser B
3. In browser A, copy the offer by pressing the "Offer" button.
4. In browser B, paste the offer into the text area and press the "Offer" button.
5. In Browser B, copy the answer by pressing the "Answer" button.
6. In browser A, paste the answer into the text area and press the "Answer" button.
7. In browser B, copy the ICE candidates by pressing the ICE button.
8. In browser A, paste the ICE candidates into the text area.

After that you should see the shared webcam in Browser B.

Make sure that both browsers can talk to each other directly.

## Try It Out

Try it out at [GitHub Pages](https://steschu77.github.io/webrtc-simple/)