# 控制台指令

## 配置

所有街机端配置相关的指令都由 `config` 开头

### 设置输入方式

```
config input
```

执行指令会跳转到输入设置界面，在这里配置输入方式和相机

### 设置输入串口设备名

```
config.set serial {dev}
```

`{dev}` 处填写串口的设备名，如 Windows 下的 `COM3` 或其他系统下的 `/dev/example`

### 设置 Api 地址

```
config.set api_addr {url}
```

`{url}` 处填写 Api 地址

### 设置 Location 信息

```
config.set location {id}:{secret}
```

`{id}` 处填写机厅ID

`{secret}` 处填写机厅 secret

### 设置文件存储

#### 设置七牛云 Bucket

```
config.set qiniu_bucket {bucket_name}
```

`{bucket_name}` 填入七牛云上 Bucket 的名称

#### 设置七牛云登录信息

```
config.set qiniu_cred {ak}:{sk}
```

`{ak}`, `{sk}` 填入七牛云上的密钥

### 设置文件存储服务器

```
config.set file_url {url}
```

`{url}` 设置 Bucket 对应域名，用于用户下载

### 设置录制时长

```
config.set record_interval {seconds}
```

`{seconds}` 录制时长，按秒计

### 设置 FFMPeg 信息

```
config.set ffmpeg_executable {path}
```

`{path}` 输入本地 FFMpeg 的路径

### 设置硬件加速

```
config.set ffmpeg_hw {type}
```

`{type}` 处填入硬件加速类型