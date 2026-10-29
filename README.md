# Hi, I'm Ahmed El Amir 👋 | مطور أوتوميشن

## 🚀 Xiaomi Note 13 Automation Factory
بصنع أدوات بتشتغل لوحدها وتجيب رزق حلال وانت نايم!

### 📱 اللي عملته على موبايلي:
- **Azkar Auto Bot** - مصنع فيديوهات HD 1080x1920 كل يوم 9PM بـ Termux + ffmpeg
- **Auto App Opener** - بيفتح TikTok 9PM و YouTube 8AM لوحده بـ cronie
- **Termux Wake Lock** - 6 sessions شغالة 24 ساعة!

```bash
0 21 * * * bash ~/azkar/azkar_bot.sh  # فيديو أذكار حلال
0 8 * * * am start -n com.google.android.youtube.HomeActivity
