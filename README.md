# Breadboard Vending Machine Page
In this page you will have all the information you need to know to create a Breadboard Vending Machine. You will learn everything you need to create one, from the pieces you need to photos to see where the parts go.


In the next circuit you can see two inputs, a "coin"  button and a "vend" button. When you press on the coin button it represents inserting a coin, when you press the vend button, the machine will vend an item. ( the circuit will turn on a LED representing vending an item). Also, you will see two LED outputs, the coin LED and the vend LED. The coin LED will turn on when a coin has been inserted and the vend LED indicates that an item has been vended. For the machine to vend an item, first, we need the user to insert a coin and after this happen we would expect the circuit to reset itself and go back to the "no coin" state. 

![image](https://github.com/user-attachments/assets/17c213fd-ce4c-4c1c-8cd8-41627b6789c9)

When you press the coin button, the coin memory device will store the fact that a coin was inserted, the memory device output would be 1, indicating that a coin hass been inserted, and the coin LED will lights up. If a coin was previously inserted, when you prees the vend button , the AND gate ouput would be 1 and the vend LED turn on. But, if you press the vend button without previously inserting a coin, nothing will happen. And to clear the coin LED and reset the circuit, you must manually set the reset input to 1.

# How to add delay to the circuit?

To add a delay to the citcuit you will need something called capacitor that look like this:

![image](https://github.com/user-attachments/assets/69056ed1-fe68-4664-8be9-6ce946765368)

A capacitor is an electrical component that stores energy, it has 2 terminals. When the current flows to the capacitor, the capacitor will charge, this ability is called capacitance which is measure in farads. One farad is a very large value, so we tipically rate capacitors in microfarads (uF). When the capacitor is not charged it acts like a short circuit. Once the capacitor is charged, it acts like an open circuit. The time it takes to charge or discharge a capacitor is controlled by the capacitor's capacitance value and resistance in the circuit.

![image](https://github.com/user-attachments/assets/8b5547f4-a5f9-4cfc-8b57-6dd849b00688)

# Example:
In the image below you can see everything we need to create a Breadboard Vending Machine. Wires, LEDs, capacitor, resistors, gates and buttons.
![image](https://github.com/user-attachments/assets/fcea6603-677a-477f-9682-a34abd1e70d2)


# How it looks in a real circuit?

![B913B281-9F14-4D68-B2D2-F9A96272B8E6](https://github.com/user-attachments/assets/411af652-400f-452f-9281-85f6ce354279)

![3802066A-AFFE-4FBB-A6CB-BE674CB236AE](https://github.com/user-attachments/assets/6085468d-4769-4734-b650-41e734c3c97e)

![858B6658-266F-417D-A4A1-8873905C62B7](https://github.com/user-attachments/assets/493a8217-9e9f-4cd6-9249-8649a6676ebf)


