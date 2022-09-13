
# Performance Test

Dear, 

I’ve completed performance test on frequently used API for test App. 
Test executed for the below mentioned scenario in Remote Address: 172.217.163.211:443 & Request URL: https://www.demoblaze.com/


## Test for 20 threads
20 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 8.33 And Total Concurrent API requested: 480.



## Test for 40 threads
40 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 16.4 And Total Concurrent API requested: 960.
## Test for 55 threads
55 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 21 And Total Concurrent API requested: 1320.
## Testing environment
RAM: 16GB

OS: Windows 10
## Conclusion
While executed 55 concurrent request, found  72 request got connection timeout and error rate is 0.53%. 

Summary: Server can handle almost concurrent 1320 API call with almost 0.5% error rate.

Please find the details report from the attachment and  let me know if you have any further queries. 
