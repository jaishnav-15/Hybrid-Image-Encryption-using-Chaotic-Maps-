# Hybrid-Image-Encryption-using-Chaotic-Maps-for-Privacy-Protection

Image big data has become pervasive in today's world. Every day huge volumes of data are being transferred across systems. Significant advancements have been made in networking and file transfer technologies. Due to the remarkable expansion of network infrastructures, multimedia transmission has become inevitable. Image data is being produced at a faster rate and the variety of data types is expanding rapidly. A number of big data-related surveillance applications use wireless image sensor networks (WISN). Important and sensitive data must be hidden from different hackers trying to break into the system. So, encryption is used to hide sensitive information from various hackers. Lorenz attractor along with the chaotic maps are used to withstand statistical attacks. Dual confusion and dual diffusion are implemented so as to ensure maximum chaos and makes the encryption system strong against attacks. The pixels of the image are scrambled using logistic maps so that only authorized users can decipher it. Through the integration of tent map and logistic map, this study approaches an efficient image encryption algorithm.

## How It Works

The encryption process involves two main stages -- **CONFUSION and DIFFUSION**

### Confusion --
This stage scrambles the pixel positions of the original image to make it unpredictable. We use a Lorenz attractor, a chaotic system, to generate the sequences needed for this pixel shuffling. This makes it difficult for unauthorized users to decode the image.

### Diffusion -- 
This stage modifies the pixel values to further secure the image. The project uses a combination of Logistic map and Tent map for this purpose. By altering the pixel values based on these chaotic maps, the algorithm disperses the original statistical redundancy of the image.


### Key Features

- Dual-stage security: The use of both confusion and diffusion makes the encryption stronger and more resistant to various attacks.

- Hybrid Chaotic Maps: The algorithm leverages the strengths of multiple chaotic maps (Lorenz attractor, Logistic map, and Tent map) to achieve a higher level of encryption.

- Performance Metrics: The algorithm is evaluated using standard metrics like NPCR and UACI, which measure its effectiveness against differential attacks. The results show high NPCR and UACI values, indicating a robust and secure system.

- High Randomness: The encrypted images show a flat histogram profile and low auto-pixel correlation, confirming that the pixel values are highly random and difficult to analyze.

## IEEE Publication
[IEEE Xplore Paper - Published in 2024](https://www.researchgate.net/publication/382230572_Hybrid_Image_Encryption_for_WISN_in_Privacy_Protection_and_Security_of_Public_Big_Data_Using_Chaotic_Maps)
### Cite Us
N. Geddada, A. Sahu, S. G, J. S, and S. Arora, “Hybrid Image Encryption for WISN in Privacy Protection and Security of Public Big Data Using Chaotic Maps,” 2024 International Conference on Advances in Modern Age Technologies for Health and Engineering Science (AMATHE), pp. 1–5, May 2024, doi: https://doi.org/10.1109/amathe61652.2024.10582063.
