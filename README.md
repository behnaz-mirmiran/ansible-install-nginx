
# 🛠 Ansible Install NGINX

پروژه‌ای برای نصب NGINX روی سرور لینوکسی با استفاده از Ansible.

---

## 📦 ابزارها

- Ansible
- Ubuntu Server (یا ماشین مجازی با SSH)
- NGINX

---

## ⚙️ اجرا:

ابتدا inventory فایل بساز (مثلاً `hosts.ini`):

```ini
[web]
192.168.56.10 ansible_user=ubuntu ansible_ssh_private_key_file=~/.ssh/id_rsa
