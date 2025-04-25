# Analysis-of-the-Disk-Structure-using-Sleuth-Kit
## NAME : KARTHICK KISHORE T
## REG NO : 212223220042
## AIM:
To analyze the disk structure of a given disk image using Sleuth Kit tools in Kali Linux.

## DESIGN STEPS:
### Step 1:
Obtain or create a disk image file (e.g., disk.dd) to analyze. Open the terminal in Kali Linux.

### Step 2:
Use Sleuth Kit tools like mmls, fsstat, and fls to examine the partition layout, file system details, and file listing.

### Step 3:
Interpret the output of the tools to understand the disk structure, including partitions, sectors, and files.

## PROGRAM:
Sleuth Kit Disk Analysis Commands

cd ~/Downloads

# Step 1: Create an empty disk image
dd if=/dev/zero of=disk.dd bs=1M count=10

# Step 2: Format it with a file system (like FAT32)
mkfs.vfat disk.dd

## OUTPUT:

![2 1](https://github.com/user-attachments/assets/f5a47770-ea88-4caf-8a23-82cc25ab073a)
![2 2](https://github.com/user-attachments/assets/9ebf2df4-a76f-4e96-8b70-9d0d053259e7)
![2 3](https://github.com/user-attachments/assets/7868a939-3c31-4e7b-aee5-1301d9a5d90d)
![2 4](https://github.com/user-attachments/assets/fdb7632a-a96c-494c-8401-26a0a14ae4ab)
![2 5](https://github.com/user-attachments/assets/b4149251-c9ab-4fb9-8650-db8c5ae613e6)
![2 6](https://github.com/user-attachments/assets/70a470ee-dd25-4066-8f1a-36f29da21321)



## RESULT:
The analysis was performed successfully using Sleuth Kit, and the disk structure was understood in detail.
