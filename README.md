# Image-Encryption
In this project I have used methods to hide text and images in an image which include, encryption of the image, embedding of data and extraction of data. This consists of two phases, the encryption phase and the decryption phase. Different techniques have been used for encrypting text and image respectively. 

The objective of this project is to provide an efficient data hiding technique with minimal distortion of the encrypting image using Image Encryption in which data and image can be retrieved independently.

Encrypting Text 
The first part of the project is hiding text using Image Encryption .Here, the text to be hidden is written in a text file. The maximum number of characters that can be hidden in the image is equal to the product of width and height of the image, in pixels. The image in first converted into binary values and stored into a matrix .Then the text in the file is also converted to binary values and stored in a matrix. After that the corresponding binary values of the two matrices are added, and this is how data encryption has been performed. 

Decrypting Text 
The second part of the project is decrypting the text hidden in an image. For decryption, the encrypted image and the original image are compared, and the corresponding binary values are stored in a matrix, and then converted to text and written in a another file.

Encrypting an image
The third part is encrypting an image into another image. This can be done by increasing the size of image 1(image used to hide image 2) then encoding pixel details of image 2 into image 1. By doing this the quality of image 2 will not be affected. Also only 2 bits in every pixel of image 1 is used for encoding this is because the encoded image does not show any patches of image 2. The bits in every pixel of the image2 is split into four and placed in four different locations in image1. So it provides some sort of encryption. So it will be hard for others to decode the hidden image.

Decrypting the image 
For decrypting the image, the encrypted image’s resolution is decreased and made the same as the original image’s resolution. Then the matrix that had been formed while encrypting is used as a key to decrypt the image.
