# Various-types-of-sampling

 1.Experimental Verification Of Signal Sampling Using Various Types Such as i)
 Natural Sampling ii) Flat Top Sampling
 
 AIM:
 
 To perform experimental verification of various types of sampling such as natural
 sampling and flat top sampling.
 
 APPARATUS REQUIRED:
 
 Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)
 
 PROCEDURE:
 
 1.Natural Sampling
 
 1. Switch on the DCL-10 kit with correct power supply polarity.
 2. Connect 1kHz, 5Vpp sine wave output to BUF IN of buffer.
 3. Connect BUF OUT of buffer to IN of Flat Top Sampling block.
 4. Set clock to Internal mode (INT clk) using switch Sw4.
 5. Set sampling frequency to 8kHz using switch S1.
 6. Set 50% duty cycle using switch Sw2.
 7. Connect OUT of Flat Top Sampling block to IN1 of 2nd order Butterworth Low
 Pass Filter.
 8. Observe output and repeat steps for 2kHz sine wave input.
    
 2. Sample and Hold
 1. Switch on the DCL-01 kit with correct power supply polarity.
 2. Connect 1kHz, 5Vpp sine wave output to BUF IN of buffer.
3. Connect BUF OUT to IN of Sample and Hold block.
 4. Set clock to Internal mode (INT clk) using switch Sw4.
 5. Set sampling frequency to 8kHz using switch S1.
 6. Set 50% duty cycle using switch Sw2.
 7. Connect OUT of Sample and Hold block to IN1 of 2nd order Butterworth Low
 Pass Filter.
 8. Observe output and repeat steps for 2kHz sine wave input.
    
 3. Flat Top Sampling
 1. Switch on the DCL-01 kit with correct power supply polarity.
 2. Connect 1kHz, 5Vpp sine wave output to BUF IN of buffer.
 3. Connect BUF OUT to IN of Flat Top Sampling block.
 4. Set clock to Internal mode (INT clk) using switch Sw4.
 5. Set sampling frequency to 8kHz using switch S1.
 6. Set 50% duty cycle using switch Sw2.
 7. Connect OUT of Flat Top Sampling block to IN1 of 2nd order Butterworth Low
 Pass Filter.
 8. Observe output and repeat steps for 2kHz sine wave input

     CIRCUIT DIAGRAM:
    
 NATURAL SAMPLING
 
 ![image](https://github.com/user-attachments/assets/99734cae-2623-48d1-916b-ec7af48c243a)

 SAMPLE AND HOLD
 
 ![image](https://github.com/user-attachments/assets/ca0d2c9c-82c7-4913-af33-0eaa879d99f5)
 
 
 MODEL GRAPH
 
 NATURAL SAMPLING
 
 ![image](https://github.com/user-attachments/assets/8d313c0d-01e1-4d9a-b245-66e29a4c053e)

 SAMPLE AND HOLD
 
 ![image](https://github.com/user-attachments/assets/6e6b3960-dc3e-4c05-90ed-8237818f3fa2)

 TABLE

 
 ![image](https://github.com/user-attachments/assets/cb855894-87a4-422c-a32e-1ea0ca381ef6)
 

 OUTPUT GRAPHS

 
 ![image](https://github.com/user-attachments/assets/8abe5d1c-057d-4e8f-9aef-b7dfd064e4df)
 ![image](https://github.com/user-attachments/assets/27974ced-c065-40e5-bded-d0439ae16354)

 

 RESULT

 
 Thus the sapmpling and reconstruction of the given input signal is done using
 different types of sampling techniques





 


