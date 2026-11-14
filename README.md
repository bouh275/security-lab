# Security Lab & AI Automation Workspace

A secure, containerized sandbox environment for web penetration testing, automation pipelines, and custom security scripts.

## 🛠️ مكونات المشروع:
1. **Camoufox:** متصفح متقدم ومخصص لتجاوز البصمات وحماية الخصوصية أثناء الاختبارات.
2. **PayloadsAllTheThings:** مرجع محلي وقاموس للحمولات الأمنية والثغرات.
3. **قوائم الحماية (Blacklists):** أكواد بايثون للتحقق من كلمات المرور الضعيفة والافتراضية للراوترات وأنظمة الشبكات.

## 🚀 الهيكل والتشغيل (Docker):
تم عزل البيئة بالكامل داخل حاوية Docker لتجنب تعارض المكتبات على جهازك الرئيسي:

```bash
# بناء حاوية المعمل الأمني
docker build -t security-lab-box .

# تشغيل التجربة
docker run --rm security-lab-box
4. انزل إلى الأسفل واضغط على زر **[Commit changes...]** ثم **[Commit changes]** لحفظ التعديلات نهرياً على السحابة.

---

### الطريقة الثانية: التعديل من جهازك (VS Code) ثم الرفع
إذا كنت تفضل العمل من جهازك (HP EliteBook):
1. افتح ملف `README.md` محلياً داخل مجلد المشروع `security-lab`.
2. حدّث محتواه بالنص أعلاه واحفظه.
3. نفذ الأوامر التالية في التيرمينال:
   ```bash
   git add README.md
   git commit -m "docs: update README with complete workspace details"
   git push origin main
