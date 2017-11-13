# Eurosys Current Graphs

# Storage
## Buffer size vs Chunk Size for file retrieval 
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1507143039030_image.png)

![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1508430341779_image.png)


Buffersize Graph^^^


## HDD vs SSD for 100mb chunks


![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1507143050779_image.png)

# Key-Value Store(YCSB)
## 1KB Object Size Average Read Time
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506369961092_image.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506369974283_image.png)

## 100KB Object Size Average Read Time
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506369895840_image.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506369907275_image.png)

## 100KB Object Size [Proper Buffers]
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1507126462496_image.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1507126467999_image.png)

## 200KB Object Size Average Read Time
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506369988146_image.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506369994107_image.png)

## Interface Usage for 1kb, 100kb, 200kb
![1 kb object sizes](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506370035212_image.png)
![100 kb object sizes](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506370055690_image.png)

# 
![200 kb object sizes](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506370080600_image.png)

# Spark
## Terasort total time to completion
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506369797653_image.png)



## Terasort **SORT** phase total time:
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506369823804_image.png)

## Terasort **SORT** phase box plot:
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506369842642_image.png)

# Memory Congestion(YCSB)


## 10g Congestion [200kb]
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506609539839_image.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506609547314_image.png)

## 9.5g Congestion [100kb] [Proper Buffers] 
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1507046639811_image.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1507046648595_image.png)



## 5g Congestion [200kb]
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506609567570_image.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506609573262_image.png)

## 5g Congestion [100kb] [Proper Buffers]
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1507046702589_image.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1507046710434_image.png)



## 2.5g Congestion [200kb]


![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506609589299_image.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1506609596592_image.png)



## 2.5g Congestion [100kb] [Proper Buffers]
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1507126303234_image.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_0D5DEC6B2D871F7E2B7146647C1CCD94F9B495A9C911A2B3220473DF65AB8F4A_1507126310765_image.png)

