This is a repo for Project on 3-D Human Pose Estimation with VAEs.

The image below shows the diversification of Pose-Estimation from a given 3-D Human Pose.
![image](https://github.com/advit2611/3-D-Human-Pose-Estimation/assets/47061894/25dca340-cafe-41df-b357-5f9170d9de55)

The model can be represented in the following diagram.

The data-set used in this project was Human3.6M dataset. 
![image](https://github.com/advit2611/3-D-Human-Pose-Estimation/assets/47061894/e278fe6a-bbad-46b8-ad57-af9be42e629a)

The metrics used for evaluation are 
• Average Pairwise Distance (APD): Average L2 distance between all pairs of motion
samples aimed at measuring diversity within the generated samples
• Average Displacement Error (ADE): Average L2 distance over all time steps between the
ground truth motion ˆx and the closest generated sample.
• Final Displacement Error (FDE): L2 distance between the final ground truth pose xT and
the closest generate sample’s final pose
• Multi-Modal ADE (MMADE): the multi-modal version of the ADE that obtains multi-
modal ground truth future motions by grouping similar past motions
• Multi-Modal FDE (MMFDE): same as MMADE but for FDE

The metrics calculated can be seen in the table below.
![image](https://github.com/advit2611/3-D-Human-Pose-Estimation/assets/47061894/c9e09326-484f-469f-bfcb-d237a8845bf3)

