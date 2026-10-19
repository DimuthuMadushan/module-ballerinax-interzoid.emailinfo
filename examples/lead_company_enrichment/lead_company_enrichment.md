# Lead company enrichment

This example enriches a sales lead by looking up the organization behind its email address. It prints the organization, domain, headquarters, employee count and revenue.

## Prerequisites

- Ballerina Swan Lake 2201.12.0 or later
- Push the connector to the local repository:
  ```bash
  cd ballerina
  bal pack && bal push --repository=local
  ```
- Create a `Config.toml` in this directory:
  ```toml
  license = "<your-license-key>"
  leadEmail = "<email-address>"
  ```

## Run the example

```bash
bal run
```
