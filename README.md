# 365-Rebecca
### Template for rebecca panel



### ربکا:  
### ابتدا قالب را با لینک زیر دانلود کنید

```bash
sudo wget -N -P /var/lib/rebecca/templates/subscription/ https://raw.githubusercontent.com/My-VEnZo/365-Rebecca/main/index.html
```
### سپس دستور زیر را بزنید تا تمپلیت ست شود

```bash
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/rebecca/templates/"' | sudo tee -a /opt/rebecca/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/rebecca/.env
```

### سپس با دستور زیر پنل خودتون رو ری‌استارت کنید

```bash
rebecca restart
```

