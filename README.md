# Desafio-Utilizando-TDD


[[package]]
name = "annotated-types"
version = "0.6.0"
description = "Reusable constraint types to use with typing.Annotated"
optional = false
python-versions = ">=3.8"
files = [
{file = "annotated_types-0.6.0-py3-none-any.whl", hash = "sha256:0641064de18ba7a25dee8f96403ebc39113d0cb953a01429249d5c7564666a43"},
{file = "annotated_types-0.6.0.tar.gz", hash = "sha256:563339e807e53ffd9c267e99fc6d9ea23eb8443c08f112651963e24e22f84a5d"},
]

[[package]]
name = "anyio"
version = "3.7.1"
description = "High level compatibility layer for multiple asynchronous event loop implementations"
optional = false
python-versions = ">=3.7"
files = [
{file = "anyio-3.7.1-py3-none-any.whl", hash = "sha256:91dee416e570e92c64041bd18b900d1d6fa78dff7048769ce5ac5ddad004fbb5"},
{file = "anyio-3.7.1.tar.gz", hash = "sha256:44a3c9aba0f5defa43261a8b3efb97891f2bd7d804e0e1f56419befa1adfc780"},
]

[package.dependencies]
idna = ">=2.8"
sniffio = ">=1.1"

[package.extras]
doc = ["Sphinx", "packaging", "sphinx-autodoc-typehints (>=1.2.0)", "sphinx-rtd-theme (>=1.2.2)", "sphinxcontrib-jquery"]
test = ["anyio[trio]", "coverage[toml] (>=4.5)", "hypothesis (>=4.0)", "mock (>=4)", "psutil (>=5.9)", "pytest (>=7.0)", "pytest-mock (>=3.6.1)", "trustme", "uvloop (>=0.17)"]
trio = ["trio (<0.22)"]

[[package]]
name = "certifi"
version = "2023.11.17"
description = "Python package for providing Mozilla's CA Bundle."
optional = false
python-versions = ">=3.6"
files = [
{file = "certifi-2023.11.17-py3-none-any.whl", hash = "sha256:e036ab49d5b79556f99cfc2d9320b34cfbe5be05c5871b51de9329f0603b0474"},
{file = "certifi-2023.11.17.tar.gz", hash = "sha256:9b469f3a900bf28dc19b8cfbf8019bf47f7fdd1a65a1d4ffb98fc14166beb4d1"},
]

[[package]]
name = "cfgv"
version = "3.4.0"
description = "Validate configuration and produce human readable error messages."
optional = false
python-versions = ">=3.8"
files = [
{file = "cfgv-3.4.0-py2.py3-none-any.whl", hash = "sha256:b7265b1f29fd3316bfcd2b330d63d024f2bfd8bcb8b0272f8e19a504856c48f9"},
{file = "cfgv-3.4.0.tar.gz", hash = "sha256:e52591d4c5f5dead8e0f673fb16db7949d2cfb3f7da4582893288f0ded8fe560"},
]

[[package]]
name = "click"
version = "8.1.7"
description = "Composable command line interface toolkit"
optional = false
python-versions = ">=3.7"
files = [
{file = "click-8.1.7-py3-none-any.whl", hash = "sha256:ae74fb96c20a0277a1d615f1e4d73c8414f5a98db8b799a7931d1582f3390c28"},
{file = "click-8.1.7.tar.gz", hash = "sha256:ca9853ad459e787e2192211578cc907e7594e294c7ccc834310722b41b9ca6de"},
]

[package.dependencies]
colorama = {version = "*", markers = "platform_system == "Windows""}

[[package]]
name = "colorama"
version = "0.4.6"
description = "Cross-platform colored terminal text."
optional = false
python-versions = "!=3.0.,!=3.1.,!=3.2.,!=3.3.,!=3.4.,!=3.5.,!=3.6.*,>=2.7"
files = [
{file = "colorama-0.4.6-py2.py3-none-any.whl", hash = "sha256:4f1d9991f5acc0ca119f9d443620b77f9d6b33703e51011c16baf57afb285fc6"},
{file = "colorama-0.4.6.tar.gz", hash = "sha256:08695f5cb7ed6e0531a20572697297273c47b8cae5a63ffc6d6ed5c201be6e44"},
]

[[package]]
name = "distlib"
version = "0.3.7"
description = "Distribution utilities"
optional = false
python-versions = "*"
files = [
{file = "distlib-0.3.7-py2.py3-none-any.whl", hash = "sha256:2e24928bc811348f0feb63014e97aaae3037f2cf48712d51ae61df7fd6075057"},
{file = "distlib-0.3.7.tar.gz", hash = "sha256:9dafe54b34a028eafd95039d5e5d4851a13734540f1331060d31c9916e7147a8"},
]

[[package]]
name = "dnspython"
version = "2.4.2"
description = "DNS toolkit"
optional = false
python-versions = ">=3.8,<4.0"
files = [
{file = "dnspython-2.4.2-py3-none-any.whl", hash = "sha256:57c6fbaaeaaf39c891292012060beb141791735dbb4004798328fc2c467402d8"},
{file = "dnspython-2.4.2.tar.gz", hash = "sha256:8dcfae8c7460a2f84b4072e26f1c9f4101ca20c071649cb7c34e8b6a93d58984"},
]

[package.extras]
dnssec = ["cryptography (>=2.6,<42.0)"]
doh = ["h2 (>=4.1.0)", "httpcore (>=0.17.3)", "httpx (>=0.24.1)"]
doq = ["aioquic (>=0.9.20)"]
idna = ["idna (>=2.1,<4.0)"]
trio = ["trio (>=0.14,<0.23)"]
wmi = ["wmi (>=1.5.1,<2.0.0)"]

[[package]]
name = "fastapi"
version = "0.104.1"
description = "FastAPI framework, high performance, easy to learn, fast to code, ready for production"
optional = false
python-versions = ">=3.8"
files = [
{file = "fastapi-0.104.1-py3-none-any.whl", hash = "sha256:752dc31160cdbd0436bb93bad51560b57e525cbb1d4bbf6f4904ceee75548241"},
{file = "fastapi-0.104.1.tar.gz", hash = "sha256:e5e4540a7c5e1dcfbbcf5b903c234feddcdcd881f191977a1c5dfd917487e7ae"},
]

[package.dependencies]
anyio = ">=3.7.1,<4.0.0"
pydantic = ">=1.7.4,<1.8 || >1.8,<1.8.1 || >1.8.1,<2.0.0 || >2.0.0,<2.0.1 || >2.0.1,<2.1.0 || >2.1.0,<3.0.0"
starlette = ">=0.27.0,<0.28.0"
typing-extensions = ">=4.8.0"

[package.extras]
all = ["email-validator (>=2.0.0)", "httpx (>=0.23.0)", "itsdangerous (>=1.1.0)", "jinja2 (>=2.11.2)", "orjson (>=3.2.1)", "pydantic-extra-types (>=2.0.0)", "pydantic-settings (>=2.0.0)", "python-multipart (>=0.0.5)", "pyyaml (>=5.3.1)", "ujson (>=4.0.1,!=4.0.2,!=4.1.0,!=4.2.0,!=4.3.0,!=5.0.0,!=5.1.0)", "uvicorn[standard] (>=0.12.0)"]

[[package]]
name = "filelock"
version = "3.13.1"
description = "A platform independent file lock."
optional = false
python-versions = ">=3.8"
files = [
{file = "filelock-3.13.1-py3-none-any.whl", hash = "sha256:57dbda9b35157b05fb3e58ee91448612eb674172fab98ee235ccb0b5bee19a1c"},
{file = "filelock-3.13.1.tar.gz", hash = "sha256:521f5f56c50f8426f5e03ad3b281b490a87ef15bc6c526f168290f0c7148d44e"},
]

[package.extras]
docs = ["furo (>=2023.9.10)", "sphinx (>=7.2.6)", "sphinx-autodoc-typehints (>=1.24)"]
testing = ["covdefaults (>=2.3)", "coverage (>=7.3.2)", "diff-cover (>=8)", "pytest (>=7.4.3)", "pytest-cov (>=4.1)", "pytest-mock (>=3.12)", "pytest-timeout (>=2.2)"]
typing = ["typing-extensions (>=4.8)"]

[[package]]
name = "h11"
version = "0.14.0"
description = "A pure-Python, bring-your-own-I/O implementation of HTTP/1.1"
optional = false
python-versions = ">=3.7"
files = [
{file = "h11-0.14.0-py3-none-any.whl", hash = "sha256:e3fe4ac4b851c468cc8363d500db52c2ead036020723024a109d37346efaa761"},
{file = "h11-0.14.0.tar.gz", hash = "sha256:8f19fbbe99e72420ff35c00b27a34cb9937e902a8b810e2c88300c6f0a3b699d"},
]

[[package]]
name = "httpcore"
version = "1.0.2"
description = "A minimal low-level HTTP client."
optional = false
python-versions = ">=3.8"
files = [
{file = "httpcore-1.0.2-py3-none-any.whl", hash = "sha256:096cc05bca73b8e459a1fc3dcf585148f63e534eae4339559c9b8a8d6399acc7"},
{file = "httpcore-1.0.2.tar.gz", hash = "sha256:9fc092e4799b26174648e54b74ed5f683132a464e95643b226e00c2ed2fa6535"},
]

[package.dependencies]
certifi = "*"
h11 = ">=0.13,<0.15"

[package.extras]
asyncio = ["anyio (>=4.0,<5.0)"]
http2 = ["h2 (>=3,<5)"]
socks = ["socksio (==1.*)"]
trio = ["trio (>=0.22.0,<0.23.0)"]

[[package]]
name = "httpx"
version = "0.25.1"
description = "The next generation HTTP client."
optional = false
python-versions = ">=3.8"
files = [
{file = "httpx-0.25.1-py3-none-any.whl", hash = "sha256:fec7d6cc5c27c578a391f7e87b9aa7d3d8fbcd034f6399f9f79b45bcc12a866a"},
{file = "httpx-0.25.1.tar.gz", hash = "sha256:ffd96d5cf901e63863d9f1b4b6807861dbea4d301613415d9e6e57ead15fc5d0"},
]

[package.dependencies]
anyio = ""
certifi = ""
httpcore = ""
idna = ""
sniffio = "*"

[package.extras]
brotli = ["brotli", "brotlicffi"]
cli = ["click (==8.)", "pygments (==2.)", "rich (>=10,<14)"]
http2 = ["h2 (>=3,<5)"]
socks = ["socksio (==1.*)"]

[[package]]
name = "identify"
version = "2.5.31"
description = "File identification library for Python"
optional = false
python-versions = ">=3.8"
files = [
{file = "identify-2.5.31-py2.py3-none-any.whl", hash = "sha256:90199cb9e7bd3c5407a9b7e81b4abec4bb9d249991c79439ec8af740afc6293d"},
{file = "identify-2.5.31.tar.gz", hash = "sha256:7736b3c7a28233637e3c36550646fc6389bedd74ae84cb788200cc8e2dd60b75"},
]

[package.extras]
license = ["ukkonen"]

[[package]]
name = "idna"
version = "3.4"
description = "Internationalized Domain Names in Applications (IDNA)"
optional = false
python-versions = ">=3.5"
files = [
{file = "idna-3.4-py3-none-any.whl", hash = "sha256:90b77e79eaa3eba6de819a0c442c0b4ceefc341a7a2ab77d7562bf49f425c5c2"},
{file = "idna-3.4.tar.gz", hash = "sha256:814f528e8dead7d329833b91c5faa87d60bf71824cd12a7530b5526063d02cb4"},
]

[[package]]
name = "iniconfig"
version = "2.0.0"
description = "brain-dead simple config-ini parsing"
optional = false
python-versions = ">=3.7"
files = [
{file = "iniconfig-2.0.0-py3-none-any.whl", hash = "sha256:b6a85871a79d2e3b22d2d1b94ac2824226a63c6b741c88f7ae975f18b6778374"},
{file = "iniconfig-2.0.0.tar.gz", hash = "sha256:2d91e135bf72d31a410b17c16da610a82cb55f6b0477d1a902134b24a455b8b3"},
]

[[package]]
name = "motor"
version = "3.3.2"
description = "Non-blocking MongoDB driver for Tornado or asyncio"
optional = false
python-versions = ">=3.7"
files = [
{file = "motor-3.3.2-py3-none-any.whl", hash = "sha256:6fe7e6f0c4f430b9e030b9d22549b732f7c2226af3ab71ecc309e4a1b7d19953"},
{file = "motor-3.3.2.tar.gz", hash = "sha256:d2fc38de15f1c8058f389c1a44a4d4105c0405c48c061cd492a654496f7bc26a"},
]

[package.dependencies]
pymongo = ">=4.5,<5"

[package.extras]
aws = ["pymongo[aws] (>=4.5,<5)"]
encryption = ["pymongo[encryption] (>=4.5,<5)"]
gssapi = ["pymongo[gssapi] (>=4.5,<5)"]
ocsp = ["pymongo[ocsp] (>=4.5,<5)"]
snappy = ["pymongo[snappy] (>=4.5,<5)"]
srv = ["pymongo[srv] (>=4.5,<5)"]
test = ["aiohttp (<3.8.6)", "mockupdb", "motor[encryption]", "pytest (>=7)", "tornado (>=5)"]
zstd = ["pymongo[zstd] (>=4.5,<5)"]

[[package]]
name = "nodeenv"
version = "1.8.0"
description = "Node.js virtual environment builder"
optional = false
python-versions = ">=2.7,!=3.0.,!=3.1.,!=3.2.,!=3.3.,!=3.4.,!=3.5.,!=3.6.*"
files = [
{file = "nodeenv-1.8.0-py2.py3-none-any.whl", hash = "sha256:df865724bb3c3adc86b3876fa209771517b0cfe596beff01a92700e0e8be4cec"},
{file = "nodeenv-1.8.0.tar.gz", hash = "sha256:d51e0c37e64fbf47d017feac3145cdbb58836d7eee8c6f6d3b6880c5456227d2"},
]

[package.dependencies]
setuptools = "*"

[[package]]
name = "packaging"
version = "23.2"
description = "Core utilities for Python packages"
optional = false
python-versions = ">=3.7"
files = [
{file = "packaging-23.2-py3-none-any.whl", hash = "sha256:8c491190033a9af7e1d931d0b5dacc2ef47509b34dd0de67ed209b5203fc88c7"},
{file = "packaging-23.2.tar.gz", hash = "sha256:048fb0e9405036518eaaf48a55953c750c11e1a1b68e0dd1a9d62ed0c092cfc5"},
]

[[package]]
name = "platformdirs"
version = "3.11.0"
description = "A small Python package for determining appropriate platform-specific dirs, e.g. a "user data dir"."
optional = false
python-versions = ">=3.7"
files = [
{file = "platformdirs-3.11.0-py3-none-any.whl", hash = "sha256:e9d171d00af68be50e9202731309c4e658fd8bc76f55c11c7dd760d023bda68e"},
{file = "platformdirs-3.11.0.tar.gz", hash = "sha256:cf8ee52a3afdb965072dcc652433e0c7e3e40cf5ea1477cd4b3b1d2eb75495b3"},
]

[package.extras]
docs = ["furo (>=2023.7.26)", "proselint (>=0.13)", "sphinx (>=7.1.1)", "sphinx-autodoc-typehints (>=1.24)"]
test = ["appdirs (==1.4.4)", "covdefaults (>=2.3)", "pytest (>=7.4)", "pytest-cov (>=4.1)", "pytest-mock (>=3.11.1)"]

[[package]]
name = "pluggy"
version = "1.3.0"
description = "plugin and hook calling mechanisms for python"
optional = false
python-versions = ">=3.8"
files = [
{file = "pluggy-1.3.0-py3-none-any.whl", hash = "sha256:d89c696a773f8bd377d18e5ecda92b7a3793cbe66c87060a6fb58c7b6e1061f7"},
{file = "pluggy-1.3.0.tar.gz", hash = "sha256:cf61ae8f126ac6f7c451172cf30e3e43d3ca77615509771b3a984a0730651e12"},
]

[package.extras]
dev = ["pre-commit", "tox"]
testing = ["pytest", "pytest-benchmark"]

[[package]]
name = "pre-commit"
version = "3.5.0"
description = "A framework for managing and maintaining multi-language pre-commit hooks."
optional = false
python-versions = ">=3.8"
files = [
{file = "pre_commit-3.5.0-py2.py3-none-any.whl", hash = "sha256:841dc9aef25daba9a0238cd27984041fa0467b4199fc4852e27950664919f660"},
{file = "pre_commit-3.5.0.tar.gz", hash = "sha256:5804465c675b659b0862f07907f96295d490822a450c4c40e747d0b1c6ebcb32"},
]

[package.dependencies]
cfgv = ">=2.0.0"
identify = ">=1.0.0"
nodeenv = ">=0.11.1"
pyyaml = ">=5.1"
virtualenv = ">=20.10.0"

[[package]]
name = "pydantic"
version = "2.5.1"
description = "Data validation using Python type hints"
optional = false
python-versions = ">=3.7"
files = [
{file = "pydantic-2.5.1-py3-none-any.whl", hash = "sha256:dc5244a8939e0d9a68f1f1b5f550b2e1c879912033b1becbedb315accc75441b"},
{file = "pydantic-2.5.1.tar.gz", hash = "sha256:0b8be5413c06aadfbe56f6dc1d45c9ed25fd43264414c571135c97dd77c2bedb"},
]

[package.dependencies]
annotated-types = ">=0.4.0"
pydantic-core = "2.14.3"
typing-extensions = ">=4.6.1"

[package.extras]
email = ["email-validator (>=2.0.0)"]

[[package]]
name = "pydantic-core"
version = "2.14.3"
description = ""
optional = false
python-versions = ">=3.7"
files = [
{file = "pydantic_core-2.14.3-cp310-cp310-macosx_10_7_x86_64.whl", hash = "sha256:ba44fad1d114539d6a1509966b20b74d2dec9a5b0ee12dd7fd0a1bb7b8785e5f"},
{file = "pydantic_core-2.14.3-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:4a70d23eedd88a6484aa79a732a90e36701048a1509078d1b59578ef0ea2cdf5"},
{file = "pydantic_core-2.14.3-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:7cc24728a1a9cef497697e53b3d085fb4d3bc0ef1ef4d9b424d9cf808f52c146"},
{file = "pydantic_core-2.14.3-cp310-cp310-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:ab4a2381005769a4af2ffddae74d769e8a4aae42e970596208ec6d615c6fb080"},
{file = "pydantic_core-2.14.3-cp310-cp310-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:905a12bf088d6fa20e094f9a477bf84bd823651d8b8384f59bcd50eaa92e6a52"},
{file = "pydantic_core-2.14.3-cp310-cp310-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:38aed5a1bbc3025859f56d6a32f6e53ca173283cb95348e03480f333b1091e7d"},
{file = "pydantic_core-2.14.3-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:1767bd3f6370458e60c1d3d7b1d9c2751cc1ad743434e8ec84625a610c8b9195"},
{file = "pydantic_core-2.14.3-cp310-cp310-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:7cb0c397f29688a5bd2c0dbd44451bc44ebb9b22babc90f97db5ec3e5bb69977"},
{file = "pydantic_core-2.14.3-cp310-cp310-musllinux_1_1_aarch64.whl", hash = "sha256:9ff737f24b34ed26de62d481ef522f233d3c5927279f6b7229de9b0deb3f76b5"},
{file = "pydantic_core-2.14.3-cp310-cp310-musllinux_1_1_x86_64.whl", hash = "sha256:a1a39fecb5f0b19faee9a8a8176c805ed78ce45d760259a4ff3d21a7daa4dfc1"},
{file = "pydantic_core-2.14.3-cp310-none-win32.whl", hash = "sha256:ccbf355b7276593c68fa824030e68cb29f630c50e20cb11ebb0ee450ae6b3d08"},
{file = "pydantic_core-2.14.3-cp310-none-win_amd64.whl", hash = "sha256:536e1f58419e1ec35f6d1310c88496f0d60e4f182cacb773d38076f66a60b149"},
{file = "pydantic_core-2.14.3-cp311-cp311-macosx_10_7_x86_64.whl", hash = "sha256:f1f46700402312bdc31912f6fc17f5ecaaaa3bafe5487c48f07c800052736289"},
{file = "pydantic_core-2.14.3-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:88ec906eb2d92420f5b074f59cf9e50b3bb44f3cb70e6512099fdd4d88c2f87c"},
{file = "pydantic_core-2.14.3-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:056ea7cc3c92a7d2a14b5bc9c9fa14efa794d9f05b9794206d089d06d3433dc7"},
{file = "pydantic_core-2.14.3-cp311-cp311-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:076edc972b68a66870cec41a4efdd72a6b655c4098a232314b02d2bfa3bfa157"},
{file = "pydantic_core-2.14.3-cp311-cp311-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:e71f666c3bf019f2490a47dddb44c3ccea2e69ac882f7495c68dc14d4065eac2"},
{file = "pydantic_core-2.14.3-cp311-cp311-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:f518eac285c9632be337323eef9824a856f2680f943a9b68ac41d5f5bad7df7c"},
{file = "pydantic_core-2.14.3-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:9dbab442a8d9ca918b4ed99db8d89d11b1f067a7dadb642476ad0889560dac79"},
{file = "pydantic_core-2.14.3-cp311-cp311-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:0653fb9fc2fa6787f2fa08631314ab7fc8070307bd344bf9471d1b7207c24623"},
{file = "pydantic_core-2.14.3-cp311-cp311-musllinux_1_1_aarch64.whl", hash = "sha256:c54af5069da58ea643ad34ff32fd6bc4eebb8ae0fef9821cd8919063e0aeeaab"},
{file = "pydantic_core-2.14.3-cp311-cp311-musllinux_1_1_x86_64.whl", hash = "sha256:cc956f78651778ec1ab105196e90e0e5f5275884793ab67c60938c75bcca3989"},
{file = "pydantic_core-2.14.3-cp311-none-win32.whl", hash = "sha256:5b73441a1159f1fb37353aaefb9e801ab35a07dd93cb8177504b25a317f4215a"},
{file = "pydantic_core-2.14.3-cp311-none-win_amd64.whl", hash = "sha256:7349f99f1ef8b940b309179733f2cad2e6037a29560f1b03fdc6aa6be0a8d03c"},
{file = "pydantic_core-2.14.3-cp311-none-win_arm64.whl", hash = "sha256:ec79dbe23702795944d2ae4c6925e35a075b88acd0d20acde7c77a817ebbce94"},
{file = "pydantic_core-2.14.3-cp312-cp312-macosx_10_7_x86_64.whl", hash = "sha256:8f5624f0f67f2b9ecaa812e1dfd2e35b256487566585160c6c19268bf2ffeccc"},
{file = "pydantic_core-2.14.3-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:6c2d118d1b6c9e2d577e215567eedbe11804c3aafa76d39ec1f8bc74e918fd07"},
{file = "pydantic_core-2.14.3-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:fe863491664c6720d65ae438d4efaa5eca766565a53adb53bf14bc3246c72fe0"},
{file = "pydantic_core-2.14.3-cp312-cp312-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:136bc7247e97a921a020abbd6ef3169af97569869cd6eff41b6a15a73c44ea9b"},
{file = "pydantic_core-2.14.3-cp312-cp312-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:aeafc7f5bbddc46213707266cadc94439bfa87ecf699444de8be044d6d6eb26f"},
{file = "pydantic_core-2.14.3-cp312-cp312-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:e16aaf788f1de5a85c8f8fcc9c1ca1dd7dd52b8ad30a7889ca31c7c7606615b8"},
{file = "pydantic_core-2.14.3-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:f8fc652c354d3362e2932a79d5ac4bbd7170757a41a62c4fe0f057d29f10bebb"},
{file = "pydantic_core-2.14.3-cp312-cp312-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:f1b92e72babfd56585c75caf44f0b15258c58e6be23bc33f90885cebffde3400"},
{file = "pydantic_core-2.14.3-cp312-cp312-musllinux_1_1_aarch64.whl", hash = "sha256:75f3f534f33651b73f4d3a16d0254de096f43737d51e981478d580f4b006b427"},
{file = "pydantic_core-2.14.3-cp312-cp312-musllinux_1_1_x86_64.whl", hash = "sha256:c9ffd823c46e05ef3eb28b821aa7bc501efa95ba8880b4a1380068e32c5bed47"},
{file = "pydantic_core-2.14.3-cp312-none-win32.whl", hash = "sha256:12e05a76b223577a4696c76d7a6b36a0ccc491ffb3c6a8cf92d8001d93ddfd63"},
{file = "pydantic_core-2.14.3-cp312-none-win_amd64.whl", hash = "sha256:1582f01eaf0537a696c846bea92082082b6bfc1103a88e777e983ea9fbdc2a0f"},
{file = "pydantic_core-2.14.3-cp312-none-win_arm64.whl", hash = "sha256:96fb679c7ca12a512d36d01c174a4fbfd912b5535cc722eb2c010c7b44eceb8e"},
{file = "pydantic_core-2.14.3-cp37-cp37m-macosx_10_7_x86_64.whl", hash = "sha256:71ed769b58d44e0bc2701aa59eb199b6665c16e8a5b8b4a84db01f71580ec448"},
{file = "pydantic_core-2.14.3-cp37-cp37m-macosx_11_0_arm64.whl", hash = "sha256:5402ee0f61e7798ea93a01b0489520f2abfd9b57b76b82c93714c4318c66ca06"},
{file = "pydantic_core-2.14.3-cp37-cp37m-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:eaab9dc009e22726c62fe3b850b797e7f0e7ba76d245284d1064081f512c7226"},
{file = "pydantic_core-2.14.3-cp37-cp37m-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:92486a04d54987054f8b4405a9af9d482e5100d6fe6374fc3303015983fc8bda"},
{file = "pydantic_core-2.14.3-cp37-cp37m-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:cf08b43d1d5d1678f295f0431a4a7e1707d4652576e1d0f8914b5e0213bfeee5"},
{file = "pydantic_core-2.14.3-cp37-cp37m-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:a8ca13480ce16daad0504be6ce893b0ee8ec34cd43b993b754198a89e2787f7e"},
{file = "pydantic_core-2.14.3-cp37-cp37m-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:44afa3c18d45053fe8d8228950ee4c8eaf3b5a7f3b64963fdeac19b8342c987f"},
{file = "pydantic_core-2.14.3-cp37-cp37m-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:56814b41486e2d712a8bc02a7b1f17b87fa30999d2323bbd13cf0e52296813a1"},
{file = "pydantic_core-2.14.3-cp37-cp37m-musllinux_1_1_aarch64.whl", hash = "sha256:c3dc2920cc96f9aa40c6dc54256e436cc95c0a15562eb7bd579e1811593c377e"},
{file = "pydantic_core-2.14.3-cp37-cp37m-musllinux_1_1_x86_64.whl", hash = "sha256:e483b8b913fcd3b48badec54185c150cb7ab0e6487914b84dc7cde2365e0c892"},
{file = "pydantic_core-2.14.3-cp37-none-win32.whl", hash = "sha256:364dba61494e48f01ef50ae430e392f67ee1ee27e048daeda0e9d21c3ab2d609"},
{file = "pydantic_core-2.14.3-cp37-none-win_amd64.whl", hash = "sha256:a402ae1066be594701ac45661278dc4a466fb684258d1a2c434de54971b006ca"},
{file = "pydantic_core-2.14.3-cp38-cp38-macosx_10_7_x86_64.whl", hash = "sha256:10904368261e4509c091cbcc067e5a88b070ed9a10f7ad78f3029c175487490f"},
{file = "pydantic_core-2.14.3-cp38-cp38-macosx_11_0_arm64.whl", hash = "sha256:260692420028319e201b8649b13ac0988974eeafaaef95d0dfbf7120c38dc000"},
{file = "pydantic_core-2.14.3-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:3c1bf1a7b05a65d3b37a9adea98e195e0081be6b17ca03a86f92aeb8b110f468"},
{file = "pydantic_core-2.14.3-cp38-cp38-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:d7abd17a838a52140e3aeca271054e321226f52df7e0a9f0da8f91ea123afe98"},
{file = "pydantic_core-2.14.3-cp38-cp38-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:a5c51460ede609fbb4fa883a8fe16e749964ddb459966d0518991ec02eb8dfb9"},
{file = "pydantic_core-2.14.3-cp38-cp38-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:d06c78074646111fb01836585f1198367b17d57c9f427e07aaa9ff499003e58d"},
{file = "pydantic_core-2.14.3-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:af452e69446fadf247f18ac5d153b1f7e61ef708f23ce85d8c52833748c58075"},
{file = "pydantic_core-2.14.3-cp38-cp38-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:e3ad4968711fb379a67c8c755beb4dae8b721a83737737b7bcee27c05400b047"},
{file = "pydantic_core-2.14.3-cp38-cp38-musllinux_1_1_aarch64.whl", hash = "sha256:c5ea0153482e5b4d601c25465771c7267c99fddf5d3f3bdc238ef930e6d051cf"},
{file = "pydantic_core-2.14.3-cp38-cp38-musllinux_1_1_x86_64.whl", hash = "sha256:96eb10ef8920990e703da348bb25fedb8b8653b5966e4e078e5be382b430f9e0"},
{file = "pydantic_core-2.14.3-cp38-none-win32.whl", hash = "sha256:ea1498ce4491236d1cffa0eee9ad0968b6ecb0c1cd711699c5677fc689905f00"},
{file = "pydantic_core-2.14.3-cp38-none-win_amd64.whl", hash = "sha256:2bc736725f9bd18a60eec0ed6ef9b06b9785454c8d0105f2be16e4d6274e63d0"},
{file = "pydantic_core-2.14.3-cp39-cp39-macosx_10_7_x86_64.whl", hash = "sha256:1ea992659c03c3ea811d55fc0a997bec9dde863a617cc7b25cfde69ef32e55af"},
{file = "pydantic_core-2.14.3-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:d2b53e1f851a2b406bbb5ac58e16c4a5496038eddd856cc900278fa0da97f3fc"},
{file = "pydantic_core-2.14.3-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:0c7f8e8a7cf8e81ca7d44bea4f181783630959d41b4b51d2f74bc50f348a090f"},
{file = "pydantic_core-2.14.3-cp39-cp39-manylinux_2_17_armv7l.manylinux2014_armv7l.whl", hash = "sha256:8d3b9c91eeb372a64ec6686c1402afd40cc20f61a0866850f7d989b6bf39a41a"},
{file = "pydantic_core-2.14.3-cp39-cp39-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:9ef3e2e407e4cad2df3c89488a761ed1f1c33f3b826a2ea9a411b0a7d1cccf1b"},
{file = "pydantic_core-2.14.3-cp39-cp39-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:f86f20a9d5bee1a6ede0f2757b917bac6908cde0f5ad9fcb3606db1e2968bcf5"},
{file = "pydantic_core-2.14.3-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:61beaa79d392d44dc19d6f11ccd824d3cccb865c4372157c40b92533f8d76dd0"},
{file = "pydantic_core-2.14.3-cp39-cp39-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:d41df8e10b094640a6b234851b624b76a41552f637b9fb34dc720b9fe4ef3be4"},
{file = "pydantic_core-2.14.3-cp39-cp39-musllinux_1_1_aarch64.whl", hash = "sha256:2c08ac60c3caa31f825b5dbac47e4875bd4954d8f559650ad9e0b225eaf8ed0c"},
{file = "pydantic_core-2.14.3-cp39-cp39-musllinux_1_1_x86_64.whl", hash = "sha256:98d8b3932f1a369364606417ded5412c4ffb15bedbcf797c31317e55bd5d920e"},
{file = "pydantic_core-2.14.3-cp39-none-win32.whl", hash = "sha256:caa94726791e316f0f63049ee00dff3b34a629b0d099f3b594770f7d0d8f1f56"},
{file = "pydantic_core-2.14.3-cp39-none-win_amd64.whl", hash = "sha256:2494d20e4c22beac30150b4be3b8339bf2a02ab5580fa6553ca274bc08681a65"},
{file = "pydantic_core-2.14.3-pp310-pypy310_pp73-macosx_10_7_x86_64.whl", hash = "sha256:fe272a72c7ed29f84c42fedd2d06c2f9858dc0c00dae3b34ba15d6d8ae0fbaaf"},
{file = "pydantic_core-2.14.3-pp310-pypy310_pp73-macosx_11_0_arm64.whl", hash = "sha256:7e63a56eb7fdee1587d62f753ccd6d5fa24fbeea57a40d9d8beaef679a24bdd6"},
{file = "pydantic_core-2.14.3-pp310-pypy310_pp73-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:b7692f539a26265cece1e27e366df5b976a6db6b1f825a9e0466395b314ee48b"},
{file = "pydantic_core-2.14.3-pp310-pypy310_pp73-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:af46f0b7a1342b49f208fed31f5a83b8495bb14b652f621e0a6787d2f10f24ee"},
{file = "pydantic_core-2.14.3-pp310-pypy310_pp73-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:6e2f9d76c00e805d47f19c7a96a14e4135238a7551a18bfd89bb757993fd0933"},
{file = "pydantic_core-2.14.3-pp310-pypy310_pp73-musllinux_1_1_aarch64.whl", hash = "sha256:de52ddfa6e10e892d00f747bf7135d7007302ad82e243cf16d89dd77b03b649d"},
{file = "pydantic_core-2.14.3-pp310-pypy310_pp73-musllinux_1_1_x86_64.whl", hash = "sha256:38113856c7fad8c19be7ddd57df0c3e77b1b2336459cb03ee3903ce9d5e236ce"},
{file = "pydantic_core-2.14.3-pp310-pypy310_pp73-win_amd64.whl", hash = "sha256:354db020b1f8f11207b35360b92d95725621eb92656725c849a61e4b550f4acc"},
{file = "pydantic_core-2.14.3-pp37-pypy37_pp73-macosx_10_7_x86_64.whl", hash = "sha256:76fc18653a5c95e5301a52d1b5afb27c9adc77175bf00f73e94f501caf0e05ad"},
{file = "pydantic_core-2.14.3-pp37-pypy37_pp73-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:2646f8270f932d79ba61102a15ea19a50ae0d43b314e22b3f8f4b5fabbfa6e38"},
{file = "pydantic_core-2.14.3-pp37-pypy37_pp73-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:37dad73a2f82975ed563d6a277fd9b50e5d9c79910c4aec787e2d63547202315"},
{file = "pydantic_core-2.14.3-pp37-pypy37_pp73-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:113752a55a8eaece2e4ac96bc8817f134c2c23477e477d085ba89e3aa0f4dc44"},
{file = "pydantic_core-2.14.3-pp37-pypy37_pp73-musllinux_1_1_aarch64.whl", hash = "sha256:8488e973547e8fb1b4193fd9faf5236cf1b7cd5e9e6dc7ff6b4d9afdc4c720cb"},
{file = "pydantic_core-2.14.3-pp37-pypy37_pp73-musllinux_1_1_x86_64.whl", hash = "sha256:3d1dde10bd9962b1434053239b1d5490fc31a2b02d8950a5f731bc584c7a5a0f"},
{file = "pydantic_core-2.14.3-pp38-pypy38_pp73-macosx_10_7_x86_64.whl", hash = "sha256:2c83892c7bf92b91d30faca53bb8ea21f9d7e39f0ae4008ef2c2f91116d0464a"},
{file = "pydantic_core-2.14.3-pp38-pypy38_pp73-macosx_11_0_arm64.whl", hash = "sha256:849cff945284c577c5f621d2df76ca7b60f803cc8663ff01b778ad0af0e39bb9"},
{file = "pydantic_core-2.14.3-pp38-pypy38_pp73-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:4aa89919fbd8a553cd7d03bf23d5bc5deee622e1b5db572121287f0e64979476"},
{file = "pydantic_core-2.14.3-pp38-pypy38_pp73-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:bf15145b1f8056d12c67255cd3ce5d317cd4450d5ee747760d8d088d85d12a2d"},
{file = "pydantic_core-2.14.3-pp38-pypy38_pp73-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:4cc6bb11f4e8e5ed91d78b9880774fbc0856cb226151b0a93b549c2b26a00c19"},
{file = "pydantic_core-2.14.3-pp38-pypy38_pp73-musllinux_1_1_aarch64.whl", hash = "sha256:832d16f248ca0cc96929139734ec32d21c67669dcf8a9f3f733c85054429c012"},
{file = "pydantic_core-2.14.3-pp38-pypy38_pp73-musllinux_1_1_x86_64.whl", hash = "sha256:b02b5e1f54c3396c48b665050464803c23c685716eb5d82a1d81bf81b5230da4"},
{file = "pydantic_core-2.14.3-pp38-pypy38_pp73-win_amd64.whl", hash = "sha256:1f2d4516c32255782153e858f9a900ca6deadfb217fd3fb21bb2b60b4e04d04d"},
{file = "pydantic_core-2.14.3-pp39-pypy39_pp73-macosx_10_7_x86_64.whl", hash = "sha256:0a3e51c2be472b7867eb0c5d025b91400c2b73a0823b89d4303a9097e2ec6655"},
{file = "pydantic_core-2.14.3-pp39-pypy39_pp73-macosx_11_0_arm64.whl", hash = "sha256:df33902464410a1f1a0411a235f0a34e7e129f12cb6340daca0f9d1390f5fe10"},
{file = "pydantic_core-2.14.3-pp39-pypy39_pp73-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:27828f0227b54804aac6fb077b6bb48e640b5435fdd7fbf0c274093a7b78b69c"},
{file = "pydantic_core-2.14.3-pp39-pypy39_pp73-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:1e2979dc80246e18e348de51246d4c9b410186ffa3c50e77924bec436b1e36cb"},
{file = "pydantic_core-2.14.3-pp39-pypy39_pp73-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:b28996872b48baf829ee75fa06998b607c66a4847ac838e6fd7473a6b2ab68e7"},
{file = "pydantic_core-2.14.3-pp39-pypy39_pp73-musllinux_1_1_aarch64.whl", hash = "sha256:ca55c9671bb637ce13d18ef352fd32ae7aba21b4402f300a63f1fb1fd18e0364"},
{file = "pydantic_core-2.14.3-pp39-pypy39_pp73-musllinux_1_1_x86_64.whl", hash = "sha256:aecd5ed096b0e5d93fb0367fd8f417cef38ea30b786f2501f6c34eabd9062c38"},
{file = "pydantic_core-2.14.3-pp39-pypy39_pp73-win_amd64.whl", hash = "sha256:44aaf1a07ad0824e407dafc637a852e9a44d94664293bbe7d8ee549c356c8882"},
{file = "pydantic_core-2.14.3.tar.gz", hash = "sha256:3ad083df8fe342d4d8d00cc1d3c1a23f0dc84fce416eb301e69f1ddbbe124d3f"},
]

[package.dependencies]
typing-extensions = ">=4.6.0,<4.7.0 || >4.7.0"

[[package]]
name = "pydantic-settings"
version = "2.1.0"
description = "Settings management using Pydantic"
optional = false
python-versions = ">=3.8"
files = [
{file = "pydantic_settings-2.1.0-py3-none-any.whl", hash = "sha256:7621c0cb5d90d1140d2f0ef557bdf03573aac7035948109adf2574770b77605a"},
{file = "pydantic_settings-2.1.0.tar.gz", hash = "sha256:26b1492e0a24755626ac5e6d715e9077ab7ad4fb5f19a8b7ed7011d52f36141c"},
]

[package.dependencies]
pydantic = ">=2.3.0"
python-dotenv = ">=0.21.0"

[[package]]
name = "pymongo"
version = "4.6.0"
description = "Python driver for MongoDB http://www.mongodb.org"
optional = false
python-versions = ">=3.7"
files = [
{file = "pymongo-4.6.0-cp310-cp310-macosx_10_9_universal2.whl", hash = "sha256:c011bd5ad03cc096f99ffcfdd18a1817354132c1331bed7a837a25226659845f"},
{file = "pymongo-4.6.0-cp310-cp310-manylinux1_i686.whl", hash = "sha256:5e63146dbdb1eac207464f6e0cfcdb640c9c5ff0f57b754fa96fe252314a1dc6"},
{file = "pymongo-4.6.0-cp310-cp310-manylinux2014_aarch64.whl", hash = "sha256:2972dd1f1285866aba027eff2f4a2bbf8aa98563c2ced14cb34ee5602b36afdf"},
{file = "pymongo-4.6.0-cp310-cp310-manylinux2014_i686.whl", hash = "sha256:a0be99b599da95b7a90a918dd927b20c434bea5e1c9b3efc6a3c6cd67c23f813"},
{file = "pymongo-4.6.0-cp310-cp310-manylinux2014_ppc64le.whl", hash = "sha256:9b0f98481ad5dc4cb430a60bbb8869f05505283b9ae1c62bdb65eb5e020ee8e3"},
{file = "pymongo-4.6.0-cp310-cp310-manylinux2014_s390x.whl", hash = "sha256:256c503a75bd71cf7fb9ebf889e7e222d49c6036a48aad5a619f98a0adf0e0d7"},
{file = "pymongo-4.6.0-cp310-cp310-manylinux2014_x86_64.whl", hash = "sha256:b4ad70d7cac4ca0c7b31444a0148bd3af01a2662fa12b1ad6f57cd4a04e21766"},
{file = "pymongo-4.6.0-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:5717a308a703dda2886a5796a07489c698b442f5e409cf7dc2ac93de8d61d764"},
{file = "pymongo-4.6.0-cp310-cp310-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:a8f7f9feecae53fa18d6a3ea7c75f9e9a1d4d20e5c3f9ce3fba83f07bcc4eee2"},
{file = "pymongo-4.6.0-cp310-cp310-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:128b1485753106c54af481789cdfea12b90a228afca0b11fb3828309a907e10e"},
{file = "pymongo-4.6.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:d3077a31633beef77d057c6523f5de7271ddef7bde5e019285b00c0cc9cac1e3"},
{file = "pymongo-4.6.0-cp310-cp310-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:ebf02c32afa6b67e5861a27183dd98ed88419a94a2ab843cc145fb0bafcc5b28"},
{file = "pymongo-4.6.0-cp310-cp310-win32.whl", hash = "sha256:b14dd73f595199f4275bed4fb509277470d9b9059310537e3b3daba12b30c157"},
{file = "pymongo-4.6.0-cp310-cp310-win_amd64.whl", hash = "sha256:8adf014f2779992eba3b513e060d06f075f0ab2fb3ad956f413a102312f65cdf"},
{file = "pymongo-4.6.0-cp311-cp311-macosx_10_9_universal2.whl", hash = "sha256:ba51129fcc510824b6ca6e2ce1c27e3e4d048b6e35d3ae6f7e517bed1b8b25ce"},
{file = "pymongo-4.6.0-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:2973f113e079fb98515722cd728e1820282721ec9fd52830e4b73cabdbf1eb28"},
{file = "pymongo-4.6.0-cp311-cp311-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:af425f323fce1b07755edd783581e7283557296946212f5b1a934441718e7528"},
{file = "pymongo-4.6.0-cp311-cp311-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:1ec71ac633b126c0775ed4604ca8f56c3540f5c21a1220639f299e7a544b55f9"},
{file = "pymongo-4.6.0-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:3ec6c20385c5a58e16b1ea60c5e4993ea060540671d7d12664f385f2fb32fe79"},
{file = "pymongo-4.6.0-cp311-cp311-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:85f2cdc400ee87f5952ebf2a117488f2525a3fb2e23863a8efe3e4ee9e54e4d1"},
{file = "pymongo-4.6.0-cp311-cp311-win32.whl", hash = "sha256:7fc2bb8a74dcfcdd32f89528e38dcbf70a3a6594963d60dc9595e3b35b66e414"},
{file = "pymongo-4.6.0-cp311-cp311-win_amd64.whl", hash = "sha256:6695d7136a435c1305b261a9ddb9b3ecec9863e05aab3935b96038145fd3a977"},
{file = "pymongo-4.6.0-cp312-cp312-macosx_10_9_universal2.whl", hash = "sha256:d603edea1ff7408638b2504905c032193b7dcee7af269802dbb35bc8c3310ed5"},
{file = "pymongo-4.6.0-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:79f41576b3022c2fe9780ae3e44202b2438128a25284a8ddfa038f0785d87019"},
{file = "pymongo-4.6.0-cp312-cp312-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:49f2af6cf82509b15093ce3569229e0d53c90ad8ae2eef940652d4cf1f81e045"},
{file = "pymongo-4.6.0-cp312-cp312-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:ecd9e1fa97aa11bf67472220285775fa15e896da108f425e55d23d7540a712ce"},
{file = "pymongo-4.6.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:2d2be5c9c3488fa8a70f83ed925940f488eac2837a996708d98a0e54a861f212"},
{file = "pymongo-4.6.0-cp312-cp312-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:8ab6bcc8e424e07c1d4ba6df96f7fb963bcb48f590b9456de9ebd03b88084fe8"},
{file = "pymongo-4.6.0-cp312-cp312-win32.whl", hash = "sha256:47aa128be2e66abd9d1a9b0437c62499d812d291f17b55185cb4aa33a5f710a4"},
{file = "pymongo-4.6.0-cp312-cp312-win_amd64.whl", hash = "sha256:014e7049dd019a6663747ca7dae328943e14f7261f7c1381045dfc26a04fa330"},
{file = "pymongo-4.6.0-cp37-cp37m-manylinux1_i686.whl", hash = "sha256:288c21ab9531b037f7efa4e467b33176bc73a0c27223c141b822ab4a0e66ff2a"},
{file = "pymongo-4.6.0-cp37-cp37m-manylinux1_x86_64.whl", hash = "sha256:747c84f4e690fbe6999c90ac97246c95d31460d890510e4a3fa61b7d2b87aa34"},
{file = "pymongo-4.6.0-cp37-cp37m-manylinux2014_aarch64.whl", hash = "sha256:055f5c266e2767a88bb585d01137d9c7f778b0195d3dbf4a487ef0638be9b651"},
{file = "pymongo-4.6.0-cp37-cp37m-manylinux2014_i686.whl", hash = "sha256:82e620842e12e8cb4050d2643a81c8149361cd82c0a920fa5a15dc4ca8a4000f"},
{file = "pymongo-4.6.0-cp37-cp37m-manylinux2014_ppc64le.whl", hash = "sha256:6b18276f14b4b6d92e707ab6db19b938e112bd2f1dc3f9f1a628df58e4fd3f0d"},
{file = "pymongo-4.6.0-cp37-cp37m-manylinux2014_s390x.whl", hash = "sha256:680fa0fc719e1a3dcb81130858368f51d83667d431924d0bcf249644bce8f303"},
{file = "pymongo-4.6.0-cp37-cp37m-manylinux2014_x86_64.whl", hash = "sha256:3919708594b86d0f5cdc713eb6fccd3f9b9532af09ea7a5d843c933825ef56c4"},
{file = "pymongo-4.6.0-cp37-cp37m-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:db082f728160369d9a6ed2e722438291558fc15ce06d0a7d696a8dad735c236b"},
{file = "pymongo-4.6.0-cp37-cp37m-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:1e4ed21029d80c4f62605ab16398fe1ce093fff4b5f22d114055e7d9fbc4adb0"},
{file = "pymongo-4.6.0-cp37-cp37m-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:9bea9138b0fc6e2218147e9c6ce1ff76ff8e29dc00bb1b64842bd1ca107aee9f"},
{file = "pymongo-4.6.0-cp37-cp37m-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:4a0269811661ba93c472c8a60ea82640e838c2eb148d252720a09b5123f2c2fe"},
{file = "pymongo-4.6.0-cp37-cp37m-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:6d6a1b1361f118e7fefa17ae3114e77f10ee1b228b20d50c47c9f351346180c8"},
{file = "pymongo-4.6.0-cp37-cp37m-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:7e3b0127b260d4abae7b62203c4c7ef0874c901b55155692353db19de4b18bc4"},
{file = "pymongo-4.6.0-cp37-cp37m-manylinux_2_5_x86_64.manylinux1_x86_64.whl", hash = "sha256:a49aca4d961823b2846b739380c847e8964ff7ae0f0a683992b9d926054f0d6d"},
{file = "pymongo-4.6.0-cp37-cp37m-win32.whl", hash = "sha256:09c7de516b08c57647176b9fc21d929d628e35bcebc7422220c89ae40b62126a"},
{file = "pymongo-4.6.0-cp37-cp37m-win_amd64.whl", hash = "sha256:81dd1308bd5630d2bb5980f00aa163b986b133f1e9ed66c66ce2a5bc3572e891"},
{file = "pymongo-4.6.0-cp38-cp38-macosx_11_0_universal2.whl", hash = "sha256:2f8c04277d879146eacda920476e93d520eff8bec6c022ac108cfa6280d84348"},
{file = "pymongo-4.6.0-cp38-cp38-manylinux1_i686.whl", hash = "sha256:5802acc012bbb4bce4dff92973dff76482f30ef35dd4cb8ab5b0e06aa8f08c80"},
{file = "pymongo-4.6.0-cp38-cp38-manylinux1_x86_64.whl", hash = "sha256:ccd785fafa1c931deff6a7116e9a0d402d59fabe51644b0d0c268295ff847b25"},
{file = "pymongo-4.6.0-cp38-cp38-manylinux2014_aarch64.whl", hash = "sha256:fe03bf25fae4b95d8afe40004a321df644400fdcba4c8e5e1a19c1085b740888"},
{file = "pymongo-4.6.0-cp38-cp38-manylinux2014_i686.whl", hash = "sha256:2ca0ba501898b2ec31e6c3acf90c31910944f01d454ad8e489213a156ccf1bda"},
{file = "pymongo-4.6.0-cp38-cp38-manylinux2014_ppc64le.whl", hash = "sha256:10a379fb60f1b2406ae57b8899bacfe20567918c8e9d2d545e1b93628fcf2050"},
{file = "pymongo-4.6.0-cp38-cp38-manylinux2014_s390x.whl", hash = "sha256:a4dc1319d0c162919ee7f4ee6face076becae2abbd351cc14f1fe70af5fb20d9"},
{file = "pymongo-4.6.0-cp38-cp38-manylinux2014_x86_64.whl", hash = "sha256:ddef295aaf80cefb0c1606f1995899efcb17edc6b327eb6589e234e614b87756"},
{file = "pymongo-4.6.0-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:518c90bdd6e842c446d01a766b9136fec5ec6cc94f3b8c3f8b4a332786ee6b64"},
{file = "pymongo-4.6.0-cp38-cp38-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:b80a4ee19b3442c57c38afa978adca546521a8822d663310b63ae2a7d7b13f3a"},
{file = "pymongo-4.6.0-cp38-cp38-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:eb438a8bf6b695bf50d57e6a059ff09652a07968b2041178b3744ea785fcef9b"},
{file = "pymongo-4.6.0-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:e3db7d833a7c38c317dc95b54e27f1d27012e031b45a7c24e360b53197d5f6e7"},
{file = "pymongo-4.6.0-cp38-cp38-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:3729b8db02063da50eeb3db88a27670d85953afb9a7f14c213ac9e3dca93034b"},
{file = "pymongo-4.6.0-cp38-cp38-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:39a1cd5d383b37285641d5a7a86be85274466ae336a61b51117155936529f9b3"},
{file = "pymongo-4.6.0-cp38-cp38-manylinux_2_5_x86_64.manylinux1_x86_64.whl", hash = "sha256:7b0e6361754ac596cd16bfc6ed49f69ffcd9b60b7bc4bcd3ea65c6a83475e4ff"},
{file = "pymongo-4.6.0-cp38-cp38-win32.whl", hash = "sha256:806e094e9e85d8badc978af8c95b69c556077f11844655cb8cd2d1758769e521"},
{file = "pymongo-4.6.0-cp38-cp38-win_amd64.whl", hash = "sha256:1394c4737b325166a65ae7c145af1ebdb9fb153ebedd37cf91d676313e4a67b8"},
{file = "pymongo-4.6.0-cp39-cp39-macosx_10_9_universal2.whl", hash = "sha256:a8273e1abbcff1d7d29cbbb1ea7e57d38be72f1af3c597c854168508b91516c2"},
{file = "pymongo-4.6.0-cp39-cp39-manylinux1_i686.whl", hash = "sha256:e16ade71c93f6814d095d25cd6d28a90d63511ea396bd96e9ffcb886b278baaa"},
{file = "pymongo-4.6.0-cp39-cp39-manylinux1_x86_64.whl", hash = "sha256:325701ae7b56daa5b0692305b7cb505ca50f80a1288abb32ff420a8a209b01ca"},
{file = "pymongo-4.6.0-cp39-cp39-manylinux2014_aarch64.whl", hash = "sha256:cc94f9fea17a5af8cf1a343597711a26b0117c0b812550d99934acb89d526ed2"},
{file = "pymongo-4.6.0-cp39-cp39-manylinux2014_i686.whl", hash = "sha256:21812453354b151200034750cd30b0140e82ec2a01fd4357390f67714a1bfbde"},
{file = "pymongo-4.6.0-cp39-cp39-manylinux2014_ppc64le.whl", hash = "sha256:0634994b026336195778e5693583c060418d4ab453eff21530422690a97e1ee8"},
{file = "pymongo-4.6.0-cp39-cp39-manylinux2014_s390x.whl", hash = "sha256:ad4f66fbb893b55f96f03020e67dcab49ffde0177c6565ccf9dec4fdf974eb61"},
{file = "pymongo-4.6.0-cp39-cp39-manylinux2014_x86_64.whl", hash = "sha256:2703a9f8f5767986b4f51c259ff452cc837c5a83c8ed5f5361f6e49933743b2f"},
{file = "pymongo-4.6.0-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:6bafea6061d63059d8bc2ffc545e2f049221c8a4457d236c5cd6a66678673eab"},
{file = "pymongo-4.6.0-cp39-cp39-manylinux_2_17_ppc64le.manylinux2014_ppc64le.whl", hash = "sha256:f28ae33dc5a0b9cee06e95fd420e42155d83271ab75964baf747ce959cac5f52"},
{file = "pymongo-4.6.0-cp39-cp39-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:d16a534da0e39785687b7295e2fcf9a339f4a20689024983d11afaa4657f8507"},
{file = "pymongo-4.6.0-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:ef67fedd863ffffd4adfd46d9d992b0f929c7f61a8307366d664d93517f2c78e"},
{file = "pymongo-4.6.0-cp39-cp39-manylinux_2_5_i686.manylinux1_i686.manylinux_2_17_i686.manylinux2014_i686.whl", hash = "sha256:05c30fd35cc97f14f354916b45feea535d59060ef867446b5c3c7f9b609dd5dc"},
{file = "pymongo-4.6.0-cp39-cp39-manylinux_2_5_i686.manylinux1_i686.whl", hash = "sha256:1c63e3a2e8fb815c4b1f738c284a4579897e37c3cfd95fdb199229a1ccfb638a"},
{file = "pymongo-4.6.0-cp39-cp39-manylinux_2_5_x86_64.manylinux1_x86_64.whl", hash = "sha256:e5e193f89f4f8c1fe273f9a6e6df915092c9f2af6db2d1afb8bd53855025c11f"},
{file = "pymongo-4.6.0-cp39-cp39-win32.whl", hash = "sha256:a09bfb51953930e7e838972ddf646c5d5f984992a66d79da6ba7f6a8d8a890cd"},
{file = "pymongo-4.6.0-cp39-cp39-win_amd64.whl", hash = "sha256:107a234dc55affc5802acb3b6d83cbb8c87355b38a9457fcd8806bdeb8bce161"},
{file = "pymongo-4.6.0.tar.gz", hash = "sha256:fb1c56d891f9e34303c451998ef62ba52659648bb0d75b03c5e4ac223a3342c2"},
]

[package.dependencies]
dnspython = ">=1.16.0,<3.0.0"

[package.extras]
aws = ["pymongo-auth-aws (<2.0.0)"]
encryption = ["certifi", "pymongo[aws]", "pymongocrypt (>=1.6.0,<2.0.0)"]
gssapi = ["pykerberos", "winkerberos (>=0.5.0)"]
ocsp = ["certifi", "cryptography (>=2.5)", "pyopenssl (>=17.2.0)", "requests (<3.0.0)", "service-identity (>=18.1.0)"]
snappy = ["python-snappy"]
test = ["pytest (>=7)"]
zstd = ["zstandard"]

[[package]]
name = "pytest"
version = "7.4.3"
description = "pytest: simple powerful testing with Python"
optional = false
python-versions = ">=3.7"
files = [
{file = "pytest-7.4.3-py3-none-any.whl", hash = "sha256:0d009c083ea859a71b76adf7c1d502e4bc170b80a8ef002da5806527b9591fac"},
{file = "pytest-7.4.3.tar.gz", hash = "sha256:d989d136982de4e3b29dabcc838ad581c64e8ed52c11fbe86ddebd9da0818cd5"},
]

[package.dependencies]
colorama = {version = "", markers = "sys_platform == "win32""}
iniconfig = ""
packaging = "*"
pluggy = ">=0.12,<2.0"

[package.extras]
testing = ["argcomplete", "attrs (>=19.2.0)", "hypothesis (>=3.56)", "mock", "nose", "pygments (>=2.7.2)", "requests", "setuptools", "xmlschema"]

[[package]]
name = "pytest-asyncio"
version = "0.21.1"
description = "Pytest support for asyncio"
optional = false
python-versions = ">=3.7"
files = [
{file = "pytest-asyncio-0.21.1.tar.gz", hash = "sha256:40a7eae6dded22c7b604986855ea48400ab15b069ae38116e8c01238e9eeb64d"},
{file = "pytest_asyncio-0.21.1-py3-none-any.whl", hash = "sha256:8666c1c8ac02631d7c51ba282e0c69a8a452b211ffedf2599099845da5c5c37b"},
]

[package.dependencies]
pytest = ">=7.0.0"

[package.extras]
docs = ["sphinx (>=5.3)", "sphinx-rtd-theme (>=1.0)"]
testing = ["coverage (>=6.2)", "flaky (>=3.5.0)", "hypothesis (>=5.7.1)", "mypy (>=0.931)", "pytest-trio (>=0.7.0)"]

[[package]]
name = "python-dotenv"
version = "1.0.0"
description = "Read key-value pairs from a .env file and set them as environment variables"
optional = false
python-versions = ">=3.8"
files = [
{file = "python-dotenv-1.0.0.tar.gz", hash = "sha256:a8df96034aae6d2d50a4ebe8216326c61c3eb64836776504fcca410e5937a3ba"},
{file = "python_dotenv-1.0.0-py3-none-any.whl", hash = "sha256:f5971a9226b701070a4bf2c38c89e5a3f0d64de8debda981d1db98583009122a"},
]

[package.extras]
cli = ["click (>=5.0)"]

[[package]]
name = "pyyaml"
version = "6.0.1"
description = "YAML parser and emitter for Python"
optional = false
python-versions = ">=3.6"
files = [
{file = "PyYAML-6.0.1-cp310-cp310-macosx_10_9_x86_64.whl", hash = "sha256:d858aa552c999bc8a8d57426ed01e40bef403cd8ccdd0fc5f6f04a00414cac2a"},
{file = "PyYAML-6.0.1-cp310-cp310-macosx_11_0_arm64.whl", hash = "sha256:fd66fc5d0da6d9815ba2cebeb4205f95818ff4b79c3ebe268e75d961704af52f"},
{file = "PyYAML-6.0.1-cp310-cp310-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:69b023b2b4daa7548bcfbd4aa3da05b3a74b772db9e23b982788168117739938"},
{file = "PyYAML-6.0.1-cp310-cp310-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:81e0b275a9ecc9c0c0c07b4b90ba548307583c125f54d5b6946cfee6360c733d"},
{file = "PyYAML-6.0.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:ba336e390cd8e4d1739f42dfe9bb83a3cc2e80f567d8805e11b46f4a943f5515"},
{file = "PyYAML-6.0.1-cp310-cp310-musllinux_1_1_x86_64.whl", hash = "sha256:326c013efe8048858a6d312ddd31d56e468118ad4cdeda36c719bf5bb6192290"},
{file = "PyYAML-6.0.1-cp310-cp310-win32.whl", hash = "sha256:bd4af7373a854424dabd882decdc5579653d7868b8fb26dc7d0e99f823aa5924"},
{file = "PyYAML-6.0.1-cp310-cp310-win_amd64.whl", hash = "sha256:fd1592b3fdf65fff2ad0004b5e363300ef59ced41c2e6b3a99d4089fa8c5435d"},
{file = "PyYAML-6.0.1-cp311-cp311-macosx_10_9_x86_64.whl", hash = "sha256:6965a7bc3cf88e5a1c3bd2e0b5c22f8d677dc88a455344035f03399034eb3007"},
{file = "PyYAML-6.0.1-cp311-cp311-macosx_11_0_arm64.whl", hash = "sha256:f003ed9ad21d6a4713f0a9b5a7a0a79e08dd0f221aff4525a2be4c346ee60aab"},
{file = "PyYAML-6.0.1-cp311-cp311-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:42f8152b8dbc4fe7d96729ec2b99c7097d656dc1213a3229ca5383f973a5ed6d"},
{file = "PyYAML-6.0.1-cp311-cp311-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:062582fca9fabdd2c8b54a3ef1c978d786e0f6b3a1510e0ac93ef59e0ddae2bc"},
{file = "PyYAML-6.0.1-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:d2b04aac4d386b172d5b9692e2d2da8de7bfb6c387fa4f801fbf6fb2e6ba4673"},
{file = "PyYAML-6.0.1-cp311-cp311-musllinux_1_1_x86_64.whl", hash = "sha256:e7d73685e87afe9f3b36c799222440d6cf362062f78be1013661b00c5c6f678b"},
{file = "PyYAML-6.0.1-cp311-cp311-win32.whl", hash = "sha256:1635fd110e8d85d55237ab316b5b011de701ea0f29d07611174a1b42f1444741"},
{file = "PyYAML-6.0.1-cp311-cp311-win_amd64.whl", hash = "sha256:bf07ee2fef7014951eeb99f56f39c9bb4af143d8aa3c21b1677805985307da34"},
{file = "PyYAML-6.0.1-cp312-cp312-macosx_10_9_x86_64.whl", hash = "sha256:855fb52b0dc35af121542a76b9a84f8d1cd886ea97c84703eaa6d88e37a2ad28"},
{file = "PyYAML-6.0.1-cp312-cp312-macosx_11_0_arm64.whl", hash = "sha256:40df9b996c2b73138957fe23a16a4f0ba614f4c0efce1e9406a184b6d07fa3a9"},
{file = "PyYAML-6.0.1-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:6c22bec3fbe2524cde73d7ada88f6566758a8f7227bfbf93a408a9d86bcc12a0"},
{file = "PyYAML-6.0.1-cp312-cp312-musllinux_1_1_x86_64.whl", hash = "sha256:8d4e9c88387b0f5c7d5f281e55304de64cf7f9c0021a3525bd3b1c542da3b0e4"},
{file = "PyYAML-6.0.1-cp312-cp312-win32.whl", hash = "sha256:d483d2cdf104e7c9fa60c544d92981f12ad66a457afae824d146093b8c294c54"},
{file = "PyYAML-6.0.1-cp312-cp312-win_amd64.whl", hash = "sha256:0d3304d8c0adc42be59c5f8a4d9e3d7379e6955ad754aa9d6ab7a398b59dd1df"},
{file = "PyYAML-6.0.1-cp36-cp36m-macosx_10_9_x86_64.whl", hash = "sha256:50550eb667afee136e9a77d6dc71ae76a44df8b3e51e41b77f6de2932bfe0f47"},
{file = "PyYAML-6.0.1-cp36-cp36m-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:1fe35611261b29bd1de0070f0b2f47cb6ff71fa6595c077e42bd0c419fa27b98"},
{file = "PyYAML-6.0.1-cp36-cp36m-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:704219a11b772aea0d8ecd7058d0082713c3562b4e271b849ad7dc4a5c90c13c"},
{file = "PyYAML-6.0.1-cp36-cp36m-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:afd7e57eddb1a54f0f1a974bc4391af8bcce0b444685d936840f125cf046d5bd"},
{file = "PyYAML-6.0.1-cp36-cp36m-win32.whl", hash = "sha256:fca0e3a251908a499833aa292323f32437106001d436eca0e6e7833256674585"},
{file = "PyYAML-6.0.1-cp36-cp36m-win_amd64.whl", hash = "sha256:f22ac1c3cac4dbc50079e965eba2c1058622631e526bd9afd45fedd49ba781fa"},
{file = "PyYAML-6.0.1-cp37-cp37m-macosx_10_9_x86_64.whl", hash = "sha256:b1275ad35a5d18c62a7220633c913e1b42d44b46ee12554e5fd39c70a243d6a3"},
{file = "PyYAML-6.0.1-cp37-cp37m-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:18aeb1bf9a78867dc38b259769503436b7c72f7a1f1f4c93ff9a17de54319b27"},
{file = "PyYAML-6.0.1-cp37-cp37m-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:596106435fa6ad000c2991a98fa58eeb8656ef2325d7e158344fb33864ed87e3"},
{file = "PyYAML-6.0.1-cp37-cp37m-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:baa90d3f661d43131ca170712d903e6295d1f7a0f595074f151c0aed377c9b9c"},
{file = "PyYAML-6.0.1-cp37-cp37m-win32.whl", hash = "sha256:9046c58c4395dff28dd494285c82ba00b546adfc7ef001486fbf0324bc174fba"},
{file = "PyYAML-6.0.1-cp37-cp37m-win_amd64.whl", hash = "sha256:4fb147e7a67ef577a588a0e2c17b6db51dda102c71de36f8549b6816a96e1867"},
{file = "PyYAML-6.0.1-cp38-cp38-macosx_10_9_x86_64.whl", hash = "sha256:1d4c7e777c441b20e32f52bd377e0c409713e8bb1386e1099c2415f26e479595"},
{file = "PyYAML-6.0.1-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:a0cd17c15d3bb3fa06978b4e8958dcdc6e0174ccea823003a106c7d4d7899ac5"},
{file = "PyYAML-6.0.1-cp38-cp38-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:28c119d996beec18c05208a8bd78cbe4007878c6dd15091efb73a30e90539696"},
{file = "PyYAML-6.0.1-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:7e07cbde391ba96ab58e532ff4803f79c4129397514e1413a7dc761ccd755735"},
{file = "PyYAML-6.0.1-cp38-cp38-musllinux_1_1_x86_64.whl", hash = "sha256:49a183be227561de579b4a36efbb21b3eab9651dd81b1858589f796549873dd6"},
{file = "PyYAML-6.0.1-cp38-cp38-win32.whl", hash = "sha256:184c5108a2aca3c5b3d3bf9395d50893a7ab82a38004c8f61c258d4428e80206"},
{file = "PyYAML-6.0.1-cp38-cp38-win_amd64.whl", hash = "sha256:1e2722cc9fbb45d9b87631ac70924c11d3a401b2d7f410cc0e3bbf249f2dca62"},
{file = "PyYAML-6.0.1-cp39-cp39-macosx_10_9_x86_64.whl", hash = "sha256:9eb6caa9a297fc2c2fb8862bc5370d0303ddba53ba97e71f08023b6cd73d16a8"},
{file = "PyYAML-6.0.1-cp39-cp39-macosx_11_0_arm64.whl", hash = "sha256:c8098ddcc2a85b61647b2590f825f3db38891662cfc2fc776415143f599bb859"},
{file = "PyYAML-6.0.1-cp39-cp39-manylinux_2_17_aarch64.manylinux2014_aarch64.whl", hash = "sha256:5773183b6446b2c99bb77e77595dd486303b4faab2b086e7b17bc6bef28865f6"},
{file = "PyYAML-6.0.1-cp39-cp39-manylinux_2_17_s390x.manylinux2014_s390x.whl", hash = "sha256:b786eecbdf8499b9ca1d697215862083bd6d2a99965554781d0d8d1ad31e13a0"},
{file = "PyYAML-6.0.1-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl", hash = "sha256:bc1bf2925a1ecd43da378f4db9e4f799775d6367bdb94671027b73b393a7c42c"},
{file = "PyYAML-6.0.1-cp39-cp39-musllinux_1_1_x86_64.whl", hash = "sha256:04ac92ad1925b2cff1db0cfebffb6ffc43457495c9b3c39d3fcae417d7125dc5"},
{file = "PyYAML-6.0.1-cp39-cp39-win32.whl", hash = "sha256:faca3bdcf85b2fc05d06ff3fbc1f83e1391b3e724afa3feba7d13eeab355484c"},
{file = "PyYAML-6.0.1-cp39-cp39-win_amd64.whl", hash = "sha256:510c9deebc5c0225e8c96813043e62b680ba2f9c50a08d3724c7f28a747d1486"},
{file = "PyYAML-6.0.1.tar.gz", hash = "sha256:bfdf460b1736c775f2ba9f6a92bca30bc2095067b8a9d77876d1fad6cc3b4a43"},
]

[[package]]
name = "setuptools"
version = "68.2.2"
description = "Easily download, build, install, upgrade, and uninstall Python packages"
optional = false
python-versions = ">=3.8"
files = [
{file = "setuptools-68.2.2-py3-none-any.whl", hash = "sha256:b454a35605876da60632df1a60f736524eb73cc47bbc9f3f1ef1b644de74fd2a"},
{file = "setuptools-68.2.2.tar.gz", hash = "sha256:4ac1475276d2f1c48684874089fefcd83bd7162ddaafb81fac866ba0db282a87"},
]

[package.extras]
docs = ["furo", "jaraco.packaging (>=9.3)", "jaraco.tidelift (>=1.4)", "pygments-github-lexers (==0.0.5)", "rst.linker (>=1.9)", "sphinx (>=3.5)", "sphinx-favicon", "sphinx-hoverxref (<2)", "sphinx-inline-tabs", "sphinx-lint", "sphinx-notfound-page (>=1,<2)", "sphinx-reredirects", "sphinxcontrib-towncrier"]
testing = ["build[virtualenv]", "filelock (>=3.4.0)", "flake8-2020", "ini2toml[lite] (>=0.9)", "jaraco.develop (>=7.21)", "jaraco.envs (>=2.2)", "jaraco.path (>=3.2.0)", "pip (>=19.1)", "pytest (>=6)", "pytest-black (>=0.3.7)", "pytest-checkdocs (>=2.4)", "pytest-cov", "pytest-enabler (>=2.2)", "pytest-mypy (>=0.9.1)", "pytest-perf", "pytest-ruff", "pytest-timeout", "pytest-xdist", "tomli-w (>=1.0.0)", "virtualenv (>=13.0.0)", "wheel"]
testing-integration = ["build[virtualenv] (>=1.0.3)", "filelock (>=3.4.0)", "jaraco.envs (>=2.2)", "jaraco.path (>=3.2.0)", "packaging (>=23.1)", "pytest", "pytest-enabler", "pytest-xdist", "tomli", "virtualenv (>=13.0.0)", "wheel"]

[[package]]
name = "sniffio"
version = "1.3.0"
description = "Sniff out which async library your code is running under"
optional = false
python-versions = ">=3.7"
files = [
{file = "sniffio-1.3.0-py3-none-any.whl", hash = "sha256:eecefdce1e5bbfb7ad2eeaabf7c1eeb404d7757c379bd1f7e5cce9d8bf425384"},
{file = "sniffio-1.3.0.tar.gz", hash = "sha256:e60305c5e5d314f5389259b7f22aaa33d8f7dee49763119234af3755c55b9101"},
]

[[package]]
name = "starlette"
version = "0.27.0"
description = "The little ASGI library that shines."
optional = false
python-versions = ">=3.7"
files = [
{file = "starlette-0.27.0-py3-none-any.whl", hash = "sha256:918416370e846586541235ccd38a474c08b80443ed31c578a418e2209b3eef91"},
{file = "starlette-0.27.0.tar.gz", hash = "sha256:6a6b0d042acb8d469a01eba54e9cda6cbd24ac602c4cd016723117d6a7e73b75"},
]

[package.dependencies]
anyio = ">=3.4.0,<5"

[package.extras]
full = ["httpx (>=0.22.0)", "itsdangerous", "jinja2", "python-multipart", "pyyaml"]

[[package]]
name = "typing-extensions"
version = "4.8.0"
description = "Backported and Experimental Type Hints for Python 3.8+"
optional = false
python-versions = ">=3.8"
files = [
{file = "typing_extensions-4.8.0-py3-none-any.whl", hash = "sha256:8f92fc8806f9a6b641eaa5318da32b44d401efaac0f6678c9bc448ba3605faa0"},
{file = "typing_extensions-4.8.0.tar.gz", hash = "sha256:df8e4339e9cb77357558cbdbceca33c303714cf861d1eef15e1070055ae8b7ef"},
]

[[package]]
name = "uvicorn"
version = "0.24.0.post1"
description = "The lightning-fast ASGI server."
optional = false
python-versions = ">=3.8"
files = [
{file = "uvicorn-0.24.0.post1-py3-none-any.whl", hash = "sha256:7c84fea70c619d4a710153482c0d230929af7bcf76c7bfa6de151f0a3a80121e"},
{file = "uvicorn-0.24.0.post1.tar.gz", hash = "sha256:09c8e5a79dc466bdf28dead50093957db184de356fcdc48697bad3bde4c2588e"},
]

[package.dependencies]
click = ">=7.0"
h11 = ">=0.8"

[package.extras]
standard = ["colorama (>=0.4)", "httptools (>=0.5.0)", "python-dotenv (>=0.13)", "pyyaml (>=5.1)", "uvloop (>=0.14.0,!=0.15.0,!=0.15.1)", "watchfiles (>=0.13)", "websockets (>=10.4)"]

[[package]]
name = "virtualenv"
version = "20.24.6"
description = "Virtual Python Environment builder"
optional = false
python-versions = ">=3.7"
files = [
{file = "virtualenv-20.24.6-py3-none-any.whl", hash = "sha256:520d056652454c5098a00c0f073611ccbea4c79089331f60bf9d7ba247bb7381"},
{file = "virtualenv-20.24.6.tar.gz", hash = "sha256:02ece4f56fbf939dbbc33c0715159951d6bf14aaf5457b092e4548e1382455af"},
]

[package.dependencies]
distlib = ">=0.3.7,<1"
filelock = ">=3.12.2,<4"
platformdirs = ">=3.9.1,<4"

[package.extras]
docs = ["furo (>=2023.7.26)", "proselint (>=0.13)", "sphinx (>=7.1.2)", "sphinx-argparse (>=0.4)", "sphinxcontrib-towncrier (>=0.2.1a0)", "towncrier (>=23.6)"]
test = ["covdefaults (>=2.3)", "coverage (>=7.2.7)", "coverage-enable-subprocess (>=1)", "flaky (>=3.7)", "packaging (>=23.1)", "pytest (>=7.4)", "pytest-env (>=0.8.2)", "pytest-freezer (>=0.4.8)", "pytest-mock (>=3.11.1)", "pytest-randomly (>=3.12)", "pytest-timeout (>=2.1)", "setuptools (>=68)", "time-machine (>=2.10)"]

[metadata]
lock-version = "2.0"
python-versions = "^3.12"
content-hash = "00486b0cd88562c8de0e54b8782a827b1515d95a612016742349956c76b1eed1"
