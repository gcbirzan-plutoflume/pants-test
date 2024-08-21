python_sources(
    name="sources",
    sources=["*.py"],
)

pex_binary(
    name="bin",
    dependencies=[":sources"],
    environment="test",
)
docker_environment(
    name="test",
    platform="linux_x86_64",
    image="python:3.11",
)
