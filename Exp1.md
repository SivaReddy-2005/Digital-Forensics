
# Experment - 1:- Forensic Imaging of a Storage Device Using FTK Imager

## Aim
To create a forensic image of a storage device using FTK Imager to preserve the original data in a forensically sound manner for further analysis.

## Description
Forensic imaging is the process of creating an exact, bit-by-bit copy of the data from a storage device, ensuring that the original evidence remains unaltered. FTK Imager is a widely-used forensic tool that allows for capturing forensic images of hard drives, USB drives, and other digital storage media. The forensic image can be analyzed without affecting the original media, maintaining the integrity and admissibility of the evidence.

## Tools and Equipment Used
- **FTK Imager**: Forensic imaging software to create bit-by-bit copies.
- **Storage Device**: The device to be imaged (e.g., hard disk, USB flash drive).
- **Write Blocker**: A hardware or software device to prevent any write operations on the 
original storage device during imaging.

- **Forensic Workstation**: A computer with FTK Imager installed and sufficient storage for the forensic image.
 **External Storage Media**: Destination device for saving the forensic image (e.g., external hard drive).









## Procedure
1. **Prepare the Workstation**: Ensure FTK Imager is installed on the forensic workstation, and necessary permissions are granted.
![alt text](<Screen Shorts/Screenshot 2025-09-01 222934.png>)

2. **Connect Write Blocker and Storage Device**: Attach the write blocker between the storage device and the workstation to prevent writing to the original media.
![alt text](<Screen Shorts/Screenshot 2025-09-01 222958-1.png>)

3. **Launch FTK Imager**: Open the FTK Imager software on the forensic workstation.
![alt text](<Screen Shorts/Screenshot 2025-09-01 222958.png>)
4. **Select 'Create Disk Image'**: From the FTK Imager menu, choose "Create Disk Image" to start the imaging process.
![alt text](<Screen Shorts/Screenshot 2025-09-01 223014.png>)
-
5. **Choose Image Source**: Select the physical storage device to be imaged from the list of connected devices.
[alt text](<Screen Shorts/Screenshot 2025-09-01 223014-1.png>)
6. **Select Image Type and Destination**:
   - Choose the image format (e.g., E01, RAW, AFF).
   - Specify the destination path on the external storage where the image will be saved.
   ![alt text](<Screen Shorts/Screenshot 2025-09-01 223133.png>)
7. **Add Image Details and Hashes**:
   - Enter case information or notes if necessary.
   - Select options to calculate hash values (MD5, SHA1) for integrity verification.'
   ![alt text](<Screen Shorts/Screenshot 2025-09-01 223148.png>)
8. **Start Imaging**: Begin the imaging process and monitor its progress.
![alt text](<Screen Shorts/Screenshot 2025-09-01 223211-1.png>)
9. **Verify Image Integrity**: Once the imaging is complete, verify the hash values to ensure the forensic image is an exact copy.
![alt text](<Screen Shorts/Screenshot 2025-09-01 223226-1.png>)
10. **Document the Process**: Record details such as date, time, operator, device specifics, and any observations.
![alt text](<Screen Shorts/Screenshot 2025-09-01 223242.png>)
![alt text](<Screen Shorts/Screenshot 2025-09-01 223359.png>)
![alt text](<Screen Shorts/Screenshot 2025-09-01 223501.png>)
![alt text](<Screen Shorts/Screenshot 2025-09-01 224145-1.png>)

## Result
A forensic image file of the storage device is successfully created and saved to the specified destination. The image includes verified hash values to ensure data integrity. This forensic image can now be used for detailed analysis without compromising the original evidence.

