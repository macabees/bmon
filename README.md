# bmon (Network Bandwidth Tool)
Monitors bandwidth by capturing network statistics, then visually displays them (Includes TUI)

## bmon (Project Info)
[Website](https://github.com/tgraf/bmon)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/bmon/)

## Build image
`$ docker build -t macabees/bmon:latest .`

## Docker Push
`$ docker push -t macabees/bmon:latest`

Note: requires `docker login`

## Run image
`$ docker run -it --rm --name=bmon --net=host macabees/bmon`
(Note: The '--net=host' option gives the container access to the network resources on the local system)

## Help
`$ docker run -it --rm macabees/bmon --help`
