# فایل‌های اذان

فایل‌های MP3 اذان را اینجا بگذارید و در `azans.json` (ریشه‌ی مخزن) یک ورودی برایشان بنویسید:

```json
{
  "version": 1,
  "azans": [
    {
      "id": "rahim",
      "name": "رحیم موذن‌زاده اردبیلی",
      "url": "https://raw.githubusercontent.com/mhsb/sunsetclock-releases/main/azan/rahim.mp3",
      "sizeKb": 2300
    }
  ]
}
```

- `id`: شناسه‌ی یکتا با حروف انگلیسی کوچک، عدد و `_`
- `url`: فقط https؛ حداکثر حجم هر فایل ۲۰ مگابایت
- فقط فایل‌هایی بگذارید که حق انتشارشان را بررسی کرده‌اید.
