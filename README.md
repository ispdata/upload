# Upload

Hướng dẫn upload file có dung lượng lớn lên github

Tải về Git LFS và cài đặt:

Windows: https://github.com/git-lfs/git-lfs/releases/download/v3.0.2/git-lfs-windows-v3.0.2.exe

Linux: https://github.com/git-lfs/git-lfs/releases/download/v3.0.2/git-lfs-linux-amd64-v3.0.2.tar.gz


Mở repo lên:

Tạo git:

```sh
git init
```

Add LFS vào repo:

```sh
git lfs install
```

Add đuôi:

```sh
git lfs track "*.zip" "*.rar" "*.exe" "*.gz" "*.msi"
```

Add file config LFS:

```sh
git add .gitattributes
```

Sau đó có thể add, commit, push các file nặng bình thường :3