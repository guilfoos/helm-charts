# helm-charts
Repository for any helm charts I needed to create.

- [Helm Repo](https://guilfoos.github.io/helm-charts/)
- [Git Repo](https://github.com/guilfoos/helm-charts)

Non of these charts are really "production" at this point it time. I'm learning or working around issues I've had with charts hosted elsewhere. Use with extreme caution.

To use:
```
helm repo add guilfoos-charts https://guilfoos.github.io/helm-charts/
helm install faster-whisper guilfoos-charts/faster-whisper
```

Charts:
 - faster-whisper. A packaging of the linuxserver gpu-enabled distribution of faster-whisper.
 - linkace. Experimenting with building charts
 - searxng. Copied from [Kubitodev/helm](https://github.com/kubitodev/helm) to work around a TLS error when trying to pull the chart.

Special thanks to drinkataco, whose [Media-Servarr](https://github.com/drinkataco/media-servarr/) charts served as a source of inspiration for the Github Actions that make this thing work.
