# rate-limiter

implement rate limiter in Java for API quota constrant

## requirement

### functional

- each client id has a quota for API calls within each minute
- the quota is universal across all teh API servers
- if the request cannot aquire a quota, provide two options: block until quota available, or discard the request

### non-functional

- the API rate limiter should not add latency to the API services

## design
