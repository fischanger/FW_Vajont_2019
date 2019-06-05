# FW_Vajont_2019
## Shared files of the Vajont ERT Fullwaver survey - 2019_05_06-07

This repository collects all the files for the ERT Fullwaver geophysical survey held on May 6th and 7th 2019 at the site of the 1963 landslide of the Vajont dam.
The research project is directed by **Professor Roberto Francese (University of Parma and OGS)**.

Files in this repository are organized as follows:

- the **field_data** folder contains the ERT resistivity and chargeability datasets acquired by using the IRIS Instruments Fullwaver system 
  (25 VFullwaver boxes, 25 meters MN dipoles) and a VIP5000 transmitter used to inject current at 30 TX electrodes. The **raw** directory hosts the raw files acquired by the Fullwaver boxes, divided by the two acquisition days. The bin file contains the pre-processed measurements ready for processing. The conversion table txt file is used to translate the dummy coordinates of the raw datasets into the real positions.
- The **DTM** folder contains the xyz digital terrain file (2x2m mesh) of the survey area.
- The **processing** folder contains the ERTLab data file with configuration before processing and the data file with resistivity/IP models 
after inversion. PNG files with inversion progress are included.
- The **topography** folder hosts the kml file with the sensor positions after the field topographic survey and a xlsx spreadsheet with the definitive coordinates of the receiving and transmitting electrodes in the Gauss Boaga coordinate system.
