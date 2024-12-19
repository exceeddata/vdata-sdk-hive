## Introduction
This repository contains code (pending) and examples for EXD vData SDK for Hive (exceeddata-sdk-vdata).  vData is an edge database running on vehicles' domain controllers.  It stores signal data in a high-compression file format with the extension of .vsw.  EXD vData SDK offers vsw decoding capabilities in standard programming languages such as C++, [Java](https://github.com/exceeddata/sdk-vdata-java), [Python](https://github.com/exceeddata/sdk-vdata-python), [Javascript](https://github.com/exceeddata/sdk-vdata-javascript), and etc.  

The following sections demonstrates how to install and use the SDK.

## Table of Contents
- [System Requirement](#system-requirement)
- [Additional Dependencies](#additional-dependencies)
- [License](#license)
- [Installation](#installation)
- [VSW File Examples](#vsw-file-examples)
- [Getting Help](#getting-help)
- [Contributing to EXD](#contributing-to-exd)

## System Requirement
- Hive2/3 
- JDK 8

## Additional Dependencies
The following dependencies will be installed by the SDK if not already exists.
- zstd

## License
The codes in the repository are released with [MIT License](LICENSE).

## Step By Step Guide
 [Step By Step Guide CN](guide_cn.md)

## VSW File Examples
### Different Frequency Data  
- [data_diff_freqency.vsw](https://github.com/exceeddata/sdk-vdata-python/blob/main/sample_files/vsw/data_diff_freqency.vsw): sample data file with 10Hz, 20Hz, 100Hz datas. The Sample file can be found in the Python SDK code repo if the link failed.

## Getting Help
For usage questions, the best place to go to is [Github issues](https://github.com/exceeddata/sdk-vdata-hive//issues). For customers of EXCEEDDATA commercial solutions, you can contact [support](mailto:support@smartsct.com) for questions or support.

## Contributing to EXD
All contributions, bug reports, bug fixes, documentation improvements, code enhancements, and new ideas are welcome.

<hr>

[Go to Top](#table-of-contents)
