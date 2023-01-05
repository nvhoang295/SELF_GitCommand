# Connect folder to github repository
```console
git init
git add .
git commit -m "first commit"
git branch -M master
git remote add origin [Code -> Clone -> Copy SSH key]
git push -f origin master
```

# Push code to your connected github repository
```console
git add .
git commit -m "type something"
git push -f origin master
```

# Pull code from connected github repository
```console
git pull origin master
```

# Fix dont show contributions
Lỗi này do link sai email đăng nhập github

```console
$ git config --global user.email viethoang2952002@gmail.com
```
Nếu lỗi thì bỏ thử dấu $

[Read more](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address#about-commit-email-addresses)


# Clone repository
cd đến folder muốn lưu clone repo rồi gõ lệnh, sau khi clone sẽ có 1 thư mục trùng với tên của clone repo trên github

```console
git clone https://github.com/nvhoang295/Test_Git_Pull.git
```
<!-- Link lấy ở code -> clone (HTTPS hay SSH đều được) của repo muốn clone về máy, clone xong pull code như bình thường -->

# Pull code from clone repo
Đầu tiên cần vào đúng bên trong thư mục đã clone về máy, sau đó chỉ cần chạy lệnh
<!-- Giả sử repo tên là Test_Git_Pull thì phải cd đúng vào folder Test_Git_Pull đã clone về trên máy -->

```console
git pull
```
Done!

