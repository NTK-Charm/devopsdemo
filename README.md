# HTML Demo: Tìm hiểu Docker & CI/CD


## Giới thiệu
Dự án nhỏ dùng HTML để minh họa cách Docker hoạt động và CI/CD tự động build, push image lên GitHub Container Registry.

## Công nghệ sử dụng
- HTML5, CSS3
- Docker & Nginx Alpine 
- GitHub Actions (CI/CD)
- GitHub Container Registry (GHCR)

## Cách chạy với Docker
Bước 1: Cài đặt Docker và mở lên trước

Bước 2: Clone dự án
Mở cmd hoặc powershell
git clone https://github.com/NTK-Charm/Docker--.git
cd Docker--

Bước 3: Build Docker image
docker build -t html-demo .

Bước 4: Chạy container
docker run -d -p 8080:80 html-demo

Bước 5: Mở trình duyệt
http://localhost:8080