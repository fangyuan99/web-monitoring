# 网站状态监控系统

一个简单高效的网站（域名）状态监控工具。

最近发现一些免费域名突然猝死，所以写了这个工具，监听域名状态，同时也可以监控网站状态。

## 功能特点

- 支持多站点监控
- 自动检测网站状态
- 可视化状态展示
- 支持自定义监控网站顺序
- 支持公开/私有模式
- 默认展示24小时、7天、30天状态

## 即将支持

- 异常推送通知（慢慢来，我很懒）

## 快速开始

1. 安装依赖：

```bash
pip install -r requirements.txt
```

2. 运行程序：

```bash
python app.py
```

3. 访问界面：
   - 打开浏览器访问 `http://localhost:5000`
   - 默认密码 admin , 可在设置中修改

## 许可证

MIT License @ heilo.cn
