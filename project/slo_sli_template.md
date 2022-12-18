# API Service

| Category     | SLI | SLO                                                                                                         |
|--------------|-----|-------------------------------------------------------------------------------------------------------------|
| Availability | The number of successful requests     | 99%                                                                       |
| Latency      | Latency of frontend response          | 90% of requests below 100ms                                               |
| Error Budget | Unsuccessful HTTP requests per minute | Error budget is defined at 20%. This means that 20% of the requests can fail and still be within the budget |
| Throughput   | Query return time | 5 RPS indicates the application is functioning                                                |
