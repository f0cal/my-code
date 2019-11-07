# Quick start

```bash
VENV_DIR=_venv
curl bootstrap.f0cal.com/master | python3 - git -v ${VENV_DIR}
f0cal my-device --help
```

# About

`f0cal/my-code` implements a user-friendly frontend to
[LTTng](https://lttng.org), a sophisticated application tracing framework.

The major contributions of this project are to:
* Make it easier to create, share, and leverage tracepoint definitions for
  third-party libraries.
* Facilitate test-time `assert`ions against hardware, software, and kernel
  conditions not visible to the calling test code.
* Provide rich analysis and visualization of trace data.

# Learn more

[f0cal.com/docs](f0cal.com/docs#my-code)
