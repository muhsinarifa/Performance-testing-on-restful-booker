# Performance-testing-on-restful-booker
Dear,

I’ve completed the performance testing on  **restful-booker API**.

Test executed for the below-mentioned scenario in server [Restful-booker](https://restful-booker.herokuapp.com/).

**1. 100 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 10 And Total Concurrent API requested: 600.**

**2. 200 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 14 And Total Concurrent API requested: 1200.**

**3. 300 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 30 And Total Concurrent API requested: 1800.**

**4. 400 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 40 And Total Concurrent API requested: 2400.**

While executing 400 concurrent requests, I found 10 requests got connection timeout, and the error rate is 0.42%.

Summary: The server can handle almost a concurrent 2100 API calls with almost zero (0) error rate.

### Please find the details report in the attachment and let me know if you have any further queries.

1.[Herokuapp_Test_Plan_t100](https://64742b27983777374941cbe2--eclectic-donut-d86ac6.netlify.app/)

2.[Herokuapp_Test_Plan_t200](https://64742bdfcc50352fbe6b209f--poetic-praline-70c599.netlify.app/)

3.[Herokuapp_Test_Plan_t300](https://64742c39161908360df380f7--stately-pony-5540b5.netlify.app/)

4.[Herokuapp_Test_Plan_t400](https://64742d04565044325dbef6ea--stirring-sorbet-08def4.netlify.app/)

Thank You For Reading,

From

Muhsina Rifa
