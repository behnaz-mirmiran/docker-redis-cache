# 🚀 Docker Redis Cache Example

این پروژه یک نمونه ساده از استفاده Redis به‌عنوان کش در یک اپلیکیشن ساده است که با Docker اجرا می‌شود.

---

## 🔧 اجزای پروژه

| فایل | توضیح |
|------|--------|
| `app.js` | برنامه Node.js که داده را در Redis ذخیره و واکشی می‌کند |
| `Dockerfile` | اجرای اپلیکیشن Node داخل کانتینر |
| `docker-compose.yml` | اجرای Redis و اپ Node به‌صورت همزمان |

---

## 🧪 اجرای پروژه

### با Docker Compose:

```bash
docker-compose up --build
