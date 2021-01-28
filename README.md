# lit-ncov-report
洛阳理工学院 "健康状况管控平台" 的一个非官方`Python封装库`兼`CLI工具`与`拓展实现` (for severless)

[![pypi version](https://img.shields.io/pypi/v/litncov)](https://pypi.org/project/litncov/)
[![pypi downloads per month](https://img.shields.io/pypi/dm/litncov)](https://pypi.org/project/litncov/)
[![Docker Pulls](https://img.shields.io/docker/pulls/icepie/litncov.svg)](https://hub.docker.com/r/icepie/litncov/)
[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)


> 如需旧版请前往[v1](https://github.com/icepie/lit-ncov-report/tree/v1)

## 打包与部署

### 腾讯云SCF

#### 触发器

```js
# 每日6点, 12点, 20点进行上报
0 0 6,12,20 * * * *
```
