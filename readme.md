نصب و راه اندازی پنل V2rayA  بر روی سیستم عامل هایو 
# v2rayA installer For Hiveos
توجه: قبل از نصب حتما سیستم عامل رو با دستور زیر بروز رسانی کنید
```sh
sudo apt update -y
```


## Usage

### Install v2rayA
### نصب و راه اندازی پنل با هسته V2ray

Install v2ray core:

```sh
sudo sh -c "$(wget -qO- https://github.com/v2rayA/v2rayA-installer/raw/main/installer.sh)" @ --with-v2ray
```
### نصب و راه اندازی پنل با هسته Xray
Install xray core:

```sh
sudo sh -c "$(wget -qO- https://github.com/v2rayA/v2rayA-installer/raw/main/installer.sh)" @ --with-xray
```

Use `curl -Ls` to replace `wget -qO-` if you want to use curl instead of wget.
### حذف پنل V2rayA
Remove v2rayA

```sh
sudo sh -c "$(wget -qO- https://github.com/v2rayA/v2rayA-installer/raw/main/uninstaller.sh)"
```

