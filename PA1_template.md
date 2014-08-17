---
title: "Activity Monitoring"
output: html_document
---



  
    
#What is mean total number of steps taken per day?   
![plot of chunk stepsPerDay](figure/stepsPerDay.png) 

**The median number of steps taken per day is 10765.**  
**The mean number of steps taken per day is 1.0766 &times; 10<sup>4</sup>.**  

#What is the average daily activity pattern?  
![plot of chunk dailyActivity](figure/dailyActivity.png) 
  
**The 5-min interval with the maximum number of steps is 206.1698**  

#Input missing values

**The total number of missing values is 2304 ** 



 
![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2.png) 
  
**With missing step values set as the average of the interval:**    
**the median number of steps taken per day is 1.0766 &times; 10<sup>4</sup>.**      
**the mean number of steps taken per day is 1.0766 &times; 10<sup>4</sup>.**      

**The difference in median steps per day is**      
**-1.1887 for the original and adjusted data.**    
**The difference in mean number of steps per day is**    
**0 for the original and adjusted data.**    

#Are there differences in activity patterns between weekdays and weekends? 




 
![plot of chunk unnamed-chunk-5](figure/unnamed-chunk-5.png) 
