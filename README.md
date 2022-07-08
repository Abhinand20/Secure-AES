# Secure-AES
A novel approach to protect AES processors from Side Channel Attacks (SCAs) - 

Designing a tamper-resistant microchip for small embedded systems is one of the urgent demands of the computing community nowadays due to the immense security challenges arising particularly in massively connected networks. One of the major threats to secure smart card chips is the ability of Side Channel Attacks (SCA), such as Correlation Power Analysis (CPA) and Correlation Instantaneous Frequency Analysis (CIFA) to increase the vulnerability of the secured cipher text to attacks even when the state of the art Advanced Encryption Standard (AES) is used. In this paper we explore the possibility of using chaotic clocking to protect AES chips against CPA and CIFA attacks. Our findings reveal that chaotic clocks, although not random, can effectively provide this protection with a low power envelope. Chaotic clocks derived from two different chaotic systems were used for testing in order to confirm the findings. Two FPGA boards running AES were driven using these chaotic clocks in order to prove the applicability of the proposed security enhancement technique.

Paper - https://ieeexplore.ieee.org/document/9301437

# Approach
![Overall Approach](https://github.com/Abhinand20/Secure-AES/blob/main/imgs/Algorithm.PNG)

# Cite
``` @ARTICLE{9301437,  author={El-Moursy, Ali A. and Darya, Abdollah M. and Elwakil, Ahmed S. and Jha, Abhinand and Majzoub, Sohaib},  journal={IEEE Transactions on Emerging Topics in Computing},   title={Chaotic Clock Driven Cryptographic Chip: Towards a DPA Resistant AES Processor},   year={2022},  volume={10},  number={2},  pages={792-805},  doi={10.1109/TETC.2020.3045802}} ```
