# API Service

| Category     | SLI | SLO                                                                                                         |
|--------------|-----|-------------------------------------------------------------------------------------------------------------|
| Availability | Total number of successful requests / total number of requests  | 99%                                             |
| Latency      | 90th percentile latency over a 100 ms period                    | 90% of requests below 100ms                     |
| Error Budget | The number of error requests/total number of requests in budget | Error budget is defined at 20%. This means that 20% of the requests can fail and still be within the budget |
| Throughput   | Total number of requests over a period of time                  | 5 RPS indicates the application is functioning  |
