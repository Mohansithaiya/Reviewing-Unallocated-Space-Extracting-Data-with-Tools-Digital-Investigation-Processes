# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes

## NAME: MOHAN S
## REGISTER NUMBER: 212223240094

## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```
lsblk
```
```
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```
```
mmls ~/disk.img
```
```
sudo ls -lh disk.img
```
```
strings disk.img | less
```

## OUTPUT:
Unallocated Space Analysis and Extracted Data Report
![EXP6_IMG1](https://github.com/user-attachments/assets/6e524545-5736-4dd5-9c3a-9c3bced6189c)

![EXP6_IMG2](https://github.com/user-attachments/assets/0f06dad5-77f7-455a-ac6d-ab54ab17a8ce)

![EXP6_IMG3](https://github.com/user-attachments/assets/3364e20b-67d9-40bb-b3bd-339b6254888b)

![EXP6_IMG4](https://github.com/user-attachments/assets/2e8c869c-9271-4029-bb70-a18edd32cc5b)

![EXP6_IMG5](https://github.com/user-attachments/assets/1b15192a-e8eb-49da-b12a-c0cfde0630c5)


## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

