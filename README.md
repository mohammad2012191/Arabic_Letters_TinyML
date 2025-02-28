# Real-Time Arabic Letter Classification Using TinyML

This repository contains the source code and deployment files for real-time Arabic letter classification using TinyML, specifically optimized for **Nicla Vision**. The model was trained and deployed using **Edge Impulse**, achieving a test accuracy of **94.33%**. 

## To deploy the model onto **Arduino Nicla Vision** you can follow these steps:

### What You Need
- **Nicla Vision** board
- **Edge Impulse Exported ZIP File** (TinyML_Arabic.zip)
- **Arduino IDE or Edge Impulse CLI**
- **USB-C Cable** to connect Nicla Vision

### Flashing Using Arduino IDE 
1. **Install Dependencies**:
   - Install **Arduino IDE**
   - Install **Arduino Nicla Vision Board Package**
   - Install **Edge Impulse Arduino Library**
   
2. **Open Arduino IDE**
   - Go to **Sketch > Include Library > Add .ZIP Library**
   - Select **TinyML_Arabic.zip** to import it.
   
3. **Upload the Model**
   - Open **File > Examples > Edge Impulse > TinyML_Arabic**
   - Click **Upload** to flash the model onto Nicla Vision.

### Running the Model
Once flashed, Nicla Vision will **capture handwriting input and classify Arabic letters in real-time**. The predictions will appear in the **Serial Monitor**.

---
* ## Contributers:
[Abdulrahman Alfrahidi](https://www.linkedin.com/in/abdulrahman-alfrihidi-0243a528a)

[Nayef Aljhani](https://www.linkedin.com/in/nayefaljhani/)

[Mohamed Eltayeb](https://www.linkedin.com/in/mohammad2012191/)
