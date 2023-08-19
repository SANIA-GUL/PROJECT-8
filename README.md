# PROJECT-8
BENET

1) In the current directory create a folder to store RIRs. The folder 'RIRs of Room 890ms' has two sub-folders, the "Left mics" and the "Right mics". For the direct path create a folder 'Anechioc RIRs Room 890ms' again with 2 similar sub-folders.
2) Do settings in ISM-setup.m and run it. For anechoic conditions in line #106, set SetupStruc.T60 = 0;  and comment line 107 and uncomment line 108.
3) Save the RIRs by the program Saving_The_RIRs.m. In the case of anechoic RIRs, comment on all lines except 1,3,4, 20, and 21, also change the folder name to 'Anechoic RIRs Room 890ms' in lines 3,4, 20, and 21. Now run the following program files with .m extension.
4) Step 1: Create the direct waves at the First Mics of left and Right beamformers.
5) Step 2: Create the reverberations in .wav files by subtracting the beamformed signal from the reverberated speech
6) Step 3: Create ILD images by the Left and Right Direct waves and Beamformed waves respectively.
7) Step 4: Create ILD labels for the class direct wave and Reverberations.
8) Step 5: Train the Neural network (U-Net) with the two class data.
9) Step 6: Test the Neural network on noisy and clean datasets.
10) Step 7: Generate the IPD cues by maximum likelihood estimation (MLE).
11) Step 8: Combine the ILD and IPD masks and apply over the reverberant testing data.
12) Step 9: Evaluate the results.

 Cite As: 	Sania Gul, M. S. Khan, and S. W. Shah.: “Preserving the beamforming effect for spatial cue-based pseudo-binaural dereverberation of a single source”, Computer Speech & Language, Vol. 77, January 2023, 
