python_requirements(name="reqs")

python_sources(name="test", sources=["foo.py"], dependencies=["//:reqs#requests"])

python_requirements(name="mypy", source="requirements-mypy.txt", resolve="mypy")
