# Stock Manager APT Repository

Ubuntu/Debian용 Stock Manager 패키지 저장소.

## 설치

```bash
echo "deb [trusted=yes] https://shartith.github.io/apt-stockmanager stable main" | sudo tee /etc/apt/sources.list.d/stock-manager.list
sudo apt update
sudo apt install stock-manager
```

## 업데이트

```bash
sudo apt update
sudo apt upgrade stock-manager
```
