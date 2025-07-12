
# ⚙️ نصب NGINX با Ansible

این پروژه شامل یک playbook برای نصب خودکار وب‌سرور NGINX روی سرور لینوکسی است.

## 🧰 پیش‌نیازها
- نصب Ansible روی سیستم شما
- فایل inventory برای دسترسی SSH به سرور

## 🛠️ اجرای playbook
```bash
ansible-playbook -i hosts.ini playbook.yml

🎯 کاربردها

یادگیری Infrastructure Automation

آماده‌سازی سرور در محیط Production
