# toit-melody
Library play notes in an easy way with your piezo buzzer. Just enter the notes as a string and play them. 

## How To
You can use all common notes C-D-E-F-G-A-B and the corresponding octaves 1,2,3,4,5,6 and 7.
`c4` is the note c in octave 4

Write `-=` if you want to "play" a pause. 

## Example
```
  melody_channel := Melody 26
  melody_channel.play "e4e4-=e4-=c4e4-=g4-=-=g3"
```

`Melody 26` will create a Melody object using the GPIO Pin 26. Make sure the Pin you are using has PWM capabilities. 
