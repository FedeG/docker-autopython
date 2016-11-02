# Docker-autopython

[autopython](https://github.com/gosella/autopython) docker implementation.
**autopython**: Automatic typing on the Python shell plus syntax highlighting, history navigation and more.

## Installation and documentation
- [Documentation](https://fedeg.github.io/docker-autopython/ "github page").
- [Image in docker hub](https://hub.docker.com/r/fedeg/autopython/ "docker hub").

### Badges

[![](https://images.microbadger.com/badges/version/fedeg/autopython:latest.svg)](http://microbadger.com/images/fedeg/autopython:latest "Get your own version badge on microbadger.com")  [![](https://images.microbadger.com/badges/image/fedeg/autopython:latest.svg)](http://microbadger.com/images/fedeg/autopython:latest "Get your own image badge on microbadger.com")

### Installation instructions:
A simple bash alias
```bash
alias autopython='docker run -it --rm -v $(pwd):/src fedeg/autopython:latest'
```

### Use instructions:
```bash
autopython file.py
```
