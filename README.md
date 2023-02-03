# Teco API models

This repository contains derived JSON files from [TCCLI] and [TCCLI-intl-en], each representing API or example metadata for [Tencent Cloud]. It also contains error metadata files derived from [API error center].

These files serve as the raw models for the [Teco](https://github.com/teco-project/teco) project.

## Layout

```
├── en-US
│   └── services
│       ├── ams/v20201229
│       └── ...
└── zh-CN
    ├── services
    │   ├── aa/v20200224
    │   ├── ...
    │   ├── ams
    │   │   ├── v20200608
    │   │   └── v20201229
    │   └── ...
    └── error-codes.json
```

[API error center]: https://cloud.tencent.com/api/error-center
[TCCLI]: https://github.com/TencentCloud/tencentcloud-cli
[TCCLI-intl-en]: https://github.com/TencentCloud/tencentcloud-cli-intl-en
[Tencent Cloud]: https://www.tencentcloud.com
