# Pi_Pico_Scrambler
This project is based on the Raspberry Pi Pico W and utilises buttons for inputting Morse code. The Red Button represents a dot (.) while the Blue Button represents a dash (-). The Green Button is used to submit the input so that the Pico can decode the signals into text. The decoded text is then encrypted using a Caesar cypher with the formula "chr((ord(s) - 65 + 2) % 26 + 65)", and the result is displayed on an OLED screen.

## Image
![image](./attachments/Morse.png)

## Demo Gif
![gif](./attachments/Demo.gif)

## Demo Link: -
[Wokwi Demo Link](https://wokwi.com/projects/462636743026749441)
