# nfw-log-monitoring

## architecture design

<img width="791" alt="image" src="https://github.com/user-attachments/assets/a795c0cf-2670-43f0-92dd-123dd6c358bc" />

## options comparison

|          | Managed | Latency  | Throughput | Pricing |
| -------- | ------- | -------- | ---------- | ------- |
| Option1  | Medium  | Medium   | on-demand  | Low     |
| Option2  | Medium  | Medium   | on-demand  | High    |
| Option3  | High    | High     | on-demand  | Medium  |

## implementation guidance
- [Option1 Lambda Sample](https://docs.aws.amazon.com/opensearch-service/latest/developerguide/integrations-s3-lambda.html)
