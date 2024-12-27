# nfw log collection & analysis

## architecture design

<img width="791" alt="image" src="https://github.com/user-attachments/assets/a795c0cf-2670-43f0-92dd-123dd6c358bc" />

## options comparison

|          | Managed | Resiliency  | Latency         | Throughput | Pricing |
| -------- | ------- | ----------- | --------------- | ---------- | ------- |
| Option1  | Medium  | High        | Medium (30s-60s)| on-demand  | Low     |
| Option2  | Medium  | High        | Low (real-time) | on-demand  | High    |
| Option3  | High    | High        | Medium (30s-60s)| on-demand  | High    |

## implementation guidance
- [Option1 Lambda Sample](https://docs.aws.amazon.com/opensearch-service/latest/developerguide/integrations-s3-lambda.html)
