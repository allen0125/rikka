# Upai Plugin

[中文版][version-zh]

Added in version 0.3.0. Inner name `upai`.

## Description

This plugin use UPai Cloud CND to store your image.

## Options

You should provide UPai operator name, password, bucket name and bucket host.

operator name and password should be add into your env variable, use key `RIKKA_UPAI_OPERATOR` and `RIKKA_UPAI_PASSWORD`.

Bucket name and bucket host should be provide use command line option:

`-bname` for the bucket name.

`-bhost` for bucket host.

BTW： you can set upload dir by provide `-bpath` option.

For example，ues `-bpath rikka`, then images will be under `rikka` folder。

Multi-level dir like `-bpath rikka/images` are also supported.

## Guide

See [Rikka Deploy Guide with UPai plugin on DaoCloud][upai-plugin-guide]

[version-zh]: https://github.com/7sDream/rikka/blob/master/plugins/upai/README.zh.md
[upai-plugin-guide]: https://github.com/7sDream/rikka/wiki/%E4%BD%BF%E7%94%A8%E5%8F%88%E6%8B%8D%E4%BA%91%E6%8F%92%E4%BB%B6
