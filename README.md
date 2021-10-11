# The Binaries

A public location to actually store compiled binaries of public libraries.

At this time, GitHub does not have a packages solution for Python so this is a way to distribute them without pypi and using GitHub auth.

```
pip install https://GITHUB_ACCESS_TOKEN@raw.githubusercontent.com/earthastronaut/thebinaries/main/{package}/{version}.tar.gz
```

Or in requirements.txt

```

{package_name}[extras] @ https://${GITHUB_ACCESS_TOKEN}@raw.githubusercontent.com/earthastronaut/thebinaries/main/{package}/{version}.tar.gz

```
