# 🔐 Reversible Data Hiding in Encrypted Images (RDHEI) 🖼️

This project presents a **Reversible Data Hiding in Encrypted Images (RDHEI)** technique that integrates key-based encryption with block-based XOR operations for secure message embedding and extraction. The primary goal of this method is to hide data in digital images while ensuring the image quality is maintained and data can be recovered accurately. By employing XOR operations and key matrices, the method ensures that both the embedded message and the original image remain intact.

## Features 🌟
- **🔒 Key-Based Encryption**: Uses randomly generated key matrices to securely encrypt the image and hide messages.
- **🔑 XOR Operation for Data Hiding**: Employs XOR operations to embed message bits into the encrypted image blocks, maintaining security and data integrity.
- **📊 Lossless Image Recovery**: Ensures the image can be fully recovered without any loss in quality, preserving the original content.
- **🛠️ Hamming Distance Analysis**: Calculates the Hamming distance between the embedded and recovered messages to ensure accurate data extraction.
- **📈 High PSNR Value**: Achieves a Peak Signal-to-Noise Ratio (PSNR) of INF dB, demonstrating no loss in image quality during the data hiding and recovery process.

## How It Works 🔍

1. **Image Division**: The original image is divided into smaller blocks to simplify the message embedding process.
2. **Message Embedding**: The message is integrated into the encrypted image using XOR operations with randomly generated key matrices.
3. **Message Extraction**: The embedded message is extracted from the encrypted image during the decryption process, ensuring no loss of data or image quality.
4. **Image Recovery**: The original image is recovered without any degradation, ensuring the lossless nature of the technique.

## Key Metrics 🧮

- **Hamming Distance**: The Hamming distance between the embedded message and the recovered message is calculated to verify the accuracy of the data extraction process.
- **Peak Signal-to-Noise Ratio (PSNR)**: The method achieves a PSNR value of **INF dB**, indicating that the image quality is preserved throughout the encryption and message embedding process.

## Technologies Used 🛠️

- **Encryption**: Key-based encryption with XOR operations for message embedding.
- **Image Processing**: Dividing images into blocks for efficient message hiding.
- **Data Extraction**: Calculating Hamming distance and recovering the original image.
