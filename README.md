# nfw-log-monitoring

## architecture design

<img width="791" alt="image" src="https://github.com/user-attachments/assets/30497882-1e43-44c8-835b-4a19140f351d" />

## options comparison

|          | Managed | Latency  | Throughput | Pricing |
| -------- | ------- | -------- | ---------- | ------- |
| Option1  | Medium  | Medium   | on-demand  | Low     |
| Option2  | Medium  | Medium   | on-demand  | High    |
| Option3  | High    | High     | on-demand  | Medium  |

## implementation guidance
- [Option1 Lambda Sample](https://docs.aws.amazon.com/opensearch-service/latest/developerguide/integrations-s3-lambda.html)
