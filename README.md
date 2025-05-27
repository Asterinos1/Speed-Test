# SpeedTest
**Technical University of Crete**  
**Networks II Project**  
**Authors:**  
- @Asterinos1
- @fneamonitaki 
- @eNiaro

##  SpeedTest instructions

To run the SpeedTest:

1. **Open two terminal windows.**

2. In the **first terminal**, run the following commands:
   ```bash
   make
   ./server
   ```

3. In the **second terminal**, run:
   ```bash
   ./client
   ```

4. When you are done with the SpeedTest, you can clean up the executables by running:

```bash
make clean
```

## WiFi-Doctor instructions

To run the WiFi-Doctor:

1. Place your **.pcap/pcapng** files in the /pcap_files folder inside the main folder.

2. In the terminal, run:
```
   python wifi_doctor.py
   ```
3. After that, select the desired file when prompted to perform analysis.

4. When the analysis is complete, all the **.csv** files and **plots** will be saved in the main folder.
