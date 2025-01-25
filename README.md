# Performance Testing
## Technology used:
  - Apache JMeter

    
## Summary Report
I’ve completed performance test on frequently used API for test App. 
Test executed for the below mentioned scenario in server 000.000.000.00. 

- 30 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 1.1 And Total Concurrent API requested: 150.
- 50 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 1.1 And Total Concurrent API requested: 250.
- 80 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 1.6 And Total Concurrent API requested: 400.
- 100 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 2.2 And Total Concurrent API requested: 500.


### While executed 50 concurrent request, found  25 request got connection timeout and error rate is 0.82%. 

### Summary: Server can handle almost concurrent 40 API call with almost zero (0) error rate.
