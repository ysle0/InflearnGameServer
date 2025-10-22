# SPDLOG compile error workaround
When compiling with SPDLOG version 1.11.0 or later, you may encounter the following error:
```
static assertion failed "Unicode support requires compiling with /utf-8" (base.h)
```

https://github.com/gabime/spdlog/issues/3251

giving "/utf-8" flag to C/C++ >  General >  Additional Options > Compiler Options resolves this issue.