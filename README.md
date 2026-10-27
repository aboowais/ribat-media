# ribat-media

ملفات صوتية يُنزّلها تطبيق **رِباط** عند الطلب (الأذانات الكاملة)، حتى يبقى حجم التطبيق صغيرًا.

- `adhans/<id>.mp3` — الأذان كاملًا. `adhans/index.json` — الحجم وبصمة SHA-256 لكل ملف (يتحقق منها التطبيق بعد التنزيل).
- المصادر والتراخيص: `adhans/SOURCES.txt`.

يُخدَم عبر jsDelivr: `https://cdn.jsdelivr.net/gh/aboowais/ribat-media@main/adhans/<id>.mp3`
