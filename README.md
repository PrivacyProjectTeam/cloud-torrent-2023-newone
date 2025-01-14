<div align="center">
	<p><img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/160/apple/325/magnet_1f9f2.png" width="100px"></p>
	<h1>cloud-torrent</h1>
	<p>Built-from-source container image of <a href="https://github.com/jpillora/cloud-torrent">cloud-torrent</a></p>
	<code>docker pull quay.io/ricardbejarano/cloud-torrent</code>
</div>


## Features

* Compiled from source during build time
* Built `FROM scratch`, with zero bloat
* Reduced attack surface (no shell, no UNIX tools, no package manager...)
* Runs as unprivileged (non-`root`) user


## Tags

### Docker Hub

Available on Docker Hub as [`docker.io/ricardbejarano/cloud-torrent`](https://hub.docker.com/r/ricardbejarano/cloud-torrent):

- [`0.8.25`, `latest` *(Dockerfile)*](Dockerfile)

### RedHat Quay

Available on RedHat Quay as [`quay.io/ricardbejarano/cloud-torrent`](https://quay.io/repository/ricardbejarano/cloud-torrent):

- [`0.8.25`, `latest` *(Dockerfile)*](Dockerfile)


## Configuration

### Volumes

- Mount your **data** at `/downloads`.
