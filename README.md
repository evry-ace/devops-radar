# EVRY DevOps Radar

At EVRY, we maintain a public DevOps Radar to help our engineering teams align
on DevOps technology choices. Is is based on the pioneering work by
[ThoughtWorks](https://www.thoughtworks.com/radar).

## Usage

To edit the radar edit the `_data/radar.yaml` and make a pull request:

```yaml
version: 2019-11
quadrants:
  - name: Security
    technologies:
      - name: Vault
        link: https://www.vaultproject.io/
        ring: 0
```

## Local Development

Start the local Jekyll server:

```
docker-compose up
```

Open the following URL in your browser:

```
http://localhost:4000/
```

## License

The MIT License (MIT)
