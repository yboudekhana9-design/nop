# 🔧 نصائح استخدام Git (بدون أي خبرة سابقة)

## 📥 تثبيت Git

### لـ Windows:
1. اذهب إلى [git-scm.com](https://git-scm.com)
2. اضغط "Download"
3. ثبّت البرنامج (اختر الإعدادات الافتراضية)

### تحقق من التثبيت:
```bash
git --version
```

---

## 🎬 البدء السريع (GitHub Pages)

### الخطوة 1: إنشاء حساب GitHub

1. اذهب إلى [github.com](https://github.com)
2. اضغط "Sign up"
3. اختر اسم مستخدم (يفضل أن يكون بسيطاً)
4. أدخل بريدك الإلكتروني وكلمة مرور
5. اكمل التحقق

### الخطوة 2: إنشاء مستودع جديد

1. اضغط على الأيقونة `+` في الزاوية اليمين العلوية
2. اختر "New repository"
3. في "Repository name" اكتب: `your-username.github.io`
   - استبدل `your-username` باسم المستخدم الفعلي
4. اختر "Public"
5. اترك الخيارات الأخرى كما هي
6. اضغط "Create repository"

### الخطوة 3: فتح Command Prompt

اضغط على Windows Key وابحث عن `Command Prompt` ثم افتحه

### الخطوة 4: الانتقال للمجلد

```bash
cd "c:\Users\DELL\OneDrive\Desktop\غخ\D.ST"
```

### الخطوة 5: تهيئة المستودع

```bash
git init
git config user.name "Your Name"
git config user.email "your-email@example.com"
```

### الخطوة 6: إضافة الملفات

```bash
git add .
```

### الخطوة 7: حفظ التغييرات

```bash
git commit -m "Initial commit - Website launch"
```

### الخطوة 8: تثبيت الفرع

```bash
git branch -M main
```

### الخطوة 9: إضافة الرابط البعيد

```bash
git remote add origin https://github.com/your-username/your-username.github.io.git
```

### الخطوة 10: رفع الملفات

```bash
git push -u origin main
```

---

## ✅ تم!

موقعك سيكون متاح على:
```
https://your-username.github.io
```

قد يستغرق الأمر 5 دقائق حتى يظهر الموقع 🚀

---

## 📝 أوامر مهمة أخرى

### تحديث الموقع (بعد تغيير ملف):

```bash
git add .
git commit -m "Update - description here"
git push
```

### مشاهدة حالة المستودع:

```bash
git status
```

### رؤية السجل:

```bash
git log
```

---

## 🚨 حل المشاكل الشائعة

### المشكلة: "Permission denied"

الحل: استخدم SSH بدلاً من HTTPS

```bash
git remote remove origin
git remote add origin git@github.com:your-username/your-username.github.io.git
```

### المشكلة: "Please tell me who you are"

الحل:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

### المشكلة: الملفات لم تُرفع

الحل: تحقق من الاتصال بالإنترنت ثم جرّب:

```bash
git push -u origin main
```

---

## 💡 نصائح مهمة

1. **احفظ رسالة commit واضحة**: مثل "Add new exercises" أو "Fix logo display"

2. **رفع التحديثات بانتظام**: لا تنسَ أن تُرفع الملفات

3. **تحقق من الحالة**: استخدم `git status` قبل الرفع

4. **استخدم فروع مختلفة**: للعمل على ميزات جديدة

---

## 🎓 موارد إضافية

- [دليل Git الرسمي](https://git-scm.com/doc)
- [GitHub Learning Lab](https://lab.github.com)
- [تعليمي Git التفاعلي](https://learngitbranching.js.org)

---

**استمتع بالنشر! 🎉**
