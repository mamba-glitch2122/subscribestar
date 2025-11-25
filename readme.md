# Subscribestar extractor

A script to extract the Subscribestar content

## Usage

```nim
import std/json
import pkg/subscribestar

let star = extractStar("Akitokit", "tsuMdi3EjLxGRwiWYLP4PjAXXlERJIj%2FkaoDghALwpFcv7sxMBBPlRa1zyIYXkMCF1qPkItu3T7MyMTjYH%2BpX4o7wrRwSVbssfLzyyTEpLKZRYfbcB3dXikMGfGCvHwK0c20raJiMPPyFYxZ4jatFyCCx9nfe5QooZdDB1uWLlo2mUiW6MSC2Hc1gQCQtjTUfL2kT51ro7GGcpjCKKmsEkagvRxBNdrswfSgf2qNJS0wgY7pkcvFa48Ht%2FDQJJmjFqVxt25PF8how27eA88lWoyY3jYQ6NlLEZnmK0QOvhGjfN2bezgq5cr%2FnVhnFpVvoZ6WYniMVUWbyntwJDU9JUuJAxGvgPRptTailjb9FekZ6JEMweRtR8UMBadkl3rVISDDNx%2F9xezIDDP%2FHDER0dYBx9Jp9XEcguGyoz7kvZRI1Q%3D%3D--srmwMGWxJNOF3rmq--Aw0BW%2FbtvgOcviZDujNY8A%3D%3D")
echo pretty %*star
```

## License

MIT
