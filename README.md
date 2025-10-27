## DBSCAN+KNN WAVEFORM CLEANER 
This code was developed by Izabela Lima Paiva, for use with spikesorted data, or waveforms in general with the aim of noise isolation. 
To use this algorith you need: 

- To have sorted your units with .phy2 or have the .spike_times and clusters classification in a format you can load. This algorithm was developed by using outputs from KILOSORT4 and PHY2; 
- Create a .csv table with the same structure of the .csv attached in the base folder of this Git. 
 
The output of this will be an .npz file with the clean waveforms; timestemps of the clean cluester and the noise cluster as well. 
Also it will be printed a figure with the waveforms within the noise cluster and the real spikes cluster, see on the Github page some examples of it. 

Last update: 26.10.2025 - Using VisualStudio Code (Jupyter notebook format)

Examples of cleaned clusters: 

Example 1:  

PCA  of the separeted clusters: 
<img width="589" height="590" alt="image" src="https://github.com/user-attachments/assets/95ab1f2e-cc16-45db-96e0-99067f88b220" />

Plot of the Waveforms, ACG (first line for the cluster before cleaning and second line cluster after cleaning), Amplitudes across time: 

<img width="1779" height="963" alt="image" src="https://github.com/user-attachments/assets/5a27bafa-b09f-4cb1-81b6-35ebf208656a" />

Example 2: 

PCA  of the separeted clusters: 
<img width="590" height="590" alt="image" src="https://github.com/user-attachments/assets/8e59886a-3f0e-408e-8652-5a1853bd61fa" />

Plot of the Waveforms, ACG (first line for the cluster before cleaning and second line cluster after cleaning), Amplitudes across time: 

<img width="1779" height="963" alt="image" src="https://github.com/user-attachments/assets/5a419fb6-2f2f-4705-86ed-e7973ae0ffe8" />

Example 3: 

PCA  of the separeted clusters: 
<img width="590" height="590" alt="image" src="https://github.com/user-attachments/assets/40d27c75-589d-4cac-9c2a-a4035d2949b3" />

Plot of the Waveforms, ACG (first line for the cluster before cleaning and second line cluster after cleaning), Amplitudes across time: 

<img width="1779" height="963" alt="image" src="https://github.com/user-attachments/assets/ae1b6e58-5367-4444-92ff-8c49b0e38420" />

Example 4: 

PCA  of the separeted clusters: 
<img width="589" height="590" alt="image" src="https://github.com/user-attachments/assets/8ae5ba79-6994-4c56-abc0-2eafaf80abc9" />

Plot of the Waveforms, ACG (first line for the cluster before cleaning and second line cluster after cleaning), Amplitudes across time: 

<img width="1779" height="963" alt="image" src="https://github.com/user-attachments/assets/4ca91e7c-c3d6-4a55-adef-273068997222" />

