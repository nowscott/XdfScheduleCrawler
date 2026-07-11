# 贡献指南

感谢你关注本项目。提交改动前，请先确认它不会记录、上传或展示任何真实课表、学生信息、登录 Cookie 或其他个人数据。

## 本地开发

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m playwright install chromium
python -m unittest discover -s tests -v
```

## 提交建议

- 保持代码兼容 Python 3.10+。
- 为行为改动补充或更新单元测试。
- 不要提交 `browser_data/`、`output/`、真实接口响应、截图或任何包含个人信息的文件。
- 如果涉及课表接口，请只在你有权访问的账号和环境中验证，并保持低频请求。

## 报告安全问题

请不要在公开 Issue 中粘贴 Cookie、账号信息、接口响应或真实课表。若发现可能泄露数据的问题，请联系仓库维护者并提供已脱敏的复现步骤。
