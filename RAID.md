# RAID (Redundant Array of Inexpensive)

## Benefits

- Provides real-time data recovery with uninterrupted access when a hard drive fails
- Increases system uptime and network availability
- Protects against data loss
- Multiple drives working in parallel increases system performance

## Software RAID

- Cheaper but uses server CPU. If the server fails the RAID system is lost

## Hardware RAID

- Faster but more expensive, provides resilence

## RAID Levels

### RAID 0

- Offer no fault tolerance or redundancy
- Data it striped across drives resulting in a higher data throughput
- Uses full disk capacity
- No parity generation
- Easy to implement
- Applications: Video editing, image manipulation

### RAID 1

- Writes data to two or more disks
- Faster reads, slower writes than a sigle disk
- Also called mirroring
- Hight cost per GB

### RAID 3

- Provides redundancy by writing the data to three or more disk
- One dedicate disk for parity
- Miminum of 4 disk needed
- High rates of reading and writing operations
- Good at working with big files, bad at small ones

### RAID 5

- Writes data and parity information across three or more disks.
- Good Performance, offers the best combination of disk array technologies
- The most popular RAID level
- High read data rate
- Medium write data rate
- Good for Data Bases, WWW servers, file sharing, printing server
- Disk failure great impact in performance
- Bad with large file tranfers

### RAID 10

- Data is simultaniusly stripped and mirrored
- May support multiple disk failures
- Very good read and write performance
- Very expensive

### RAID 0+1

- Higher performance than RAID 1
- Four drives minumum
