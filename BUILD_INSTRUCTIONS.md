
# 🛠️ Инструкция по сборке

## Для Mac OS:
```bash
pip install pyinstaller requests pandas matplotlib vk-api openpyxl
pyinstaller --onefile --console --name="PhysicsMotivationBot" physics_bot_console.py
cp -r templates dist/
