# **Image-Based Steganography (Message Hiding in Images)**  

A secure and efficient Python-based steganography tool that hides secret messages inside images while keeping them visually unchanged. This project ensures automatic message length detection, efficient RGB encoding, and password protection, making it ideal for secure communication and cybersecurity applications.  

## **Features**  

- No manual message length input – The system automatically stores the message length.  
- Minimal image distortion – Uses RGB channels efficiently, keeping the image unchanged.  
- Built-in password protection – Ensures only authorized users can decrypt the message.  
- Lightweight and flexible – Uses OpenCV and supports multiple image formats (PNG, JPG, BMP).  
- Easy encoding and decoding – Simple command-line interface for secure messaging.  

## **Installation**  

1. Install the required library:  
   ```bash
   pip install opencv-python
   ```
2. Clone or download the project files.  

## **Usage**  

while providing the path we should add double slash to the path as slash is an escape character

For example path is ==>  K:\aicte\image\mypic.png

The input should be like this ==> K:\\aicte\\image\\mypic.png

### **Encrypt a Message into an Image**  
Run the encryption script:  
```bash
python encrypt.py
```  
- Enter the image path, secret message, and a password.  
- The encrypted image will be saved as `mypic.png`.  

### **Decrypt a Message from an Image**  
Run the decryption script:  
```bash
python decrypt.py
```  
- Enter the encrypted image path, original message length, and password.  
- If authenticated, the hidden message is revealed.  

## **Future Scope**  

- Implement stronger encryption (AES/RSA) for added security.  
- Support for hiding files, not just text.  
- Develop a graphical user interface (Tkinter or PyQt) for easier use.  
- Mobile and web integration for broader accessibility.  
- AI-resistant encoding to prevent detection by steganalysis tools.  

## **License**  

This project is open-source and available for modification and use.  


## **Contributors**

[Kalyani Mantramurthi] – Project Developer
