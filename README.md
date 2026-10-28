# ♛ ترمینال فرماندهی ثروت و مشاور ارشد مالی | Sovereign Wealth & CFO Terminal V26

نسخه بازطراحی‌شده و ارتقایافته **Sovereign V26 (Institutional Private Banking & CFO Cash Advisory Edition)** با ۳ تحول بنیادی:

1. **بازطراحی کامل رابط کاربری (UI/UX) با ۳ تم لوکس انتخابی**:
   - **Obsidian Gold (تم پیش‌فرض پرایوت بانکینگ سوئیس)**: ترکیب کربن عمیق، طلای شامپاینی (`#d4af37`)، زمردی (`#10b981`) و یاقوتی با کارت‌های شیشه‌ای (Glassmorphism) و تایپوگرافی استاندارد فارسی (`Vazirmatn` + `JetBrains Mono`).
   - **Institutional Slate (تم کوانت/بلومبرگ)**: کنتراست بالا با طیف آبی تیره و فیروزه‌ای.
   - **Ivory Executive (تم روشن مدیریتی)**: پس‌زمینه گرم کاغذی برای مطالعه طولانی‌مدت در روز.

2. **بخش فوق‌حرفه‌ای «مدیر مالی و مشاور ارشد سرمایه‌گذاری وجه نقد (CFO & Cash Investment Advisory)» بر پایه اسکیل‌های گیت‌هاب**:
   - پیاده‌سازی مستقیم فریم‌ورک‌های ۴ اسکیل معتبر گیت‌هاب (`alirezarezvani/claude-skills/cfo-advisor`، `theneoai/awesome-skills/fund-manager`، `borghei/Claude-Skills/business-investment-advisor` و `anthropics/claude-for-financial-advisors`) + فایل مستند اسکیل در `skills/cfo-cash-advisor/SKILL.md`.
   - **معماری ۳ لایه خزانه‌داری (Tier 1: سپر اقساط T+0، Tier 2: موتور ضدتورمی روزشمار T+1، Tier 3: مهمات شکار کف Dry Powder)**.
   - **محاسبه‌گر زنده زیان خواب پول (Cash Drag Audit)**، **موتور تخصیص ۵ گانه وجه نقد در ۴ رژیم ریسک** (`Balanced CFO Core`، `Conservative Shield`، `Tactical Dip Hunter`، `Barbell Strategy`)، **برنامه ورود ۴ پله‌ای زمانی و قیمتی**، **غربالگر فرصت‌ها با امتیاز مرکب CFO (۰ تا ۱۰۰)** و **تولید خودکار مصوبه کمیته سرمایه‌گذاری (IC Executive Memo)**.

3. **مهندسی قیمت‌گیری زنده کوانتومی (Quantum Multi-Pipeline Live Price Engine) + کنسول تست خودکار**:
   - معماری ۴ کاناله با آبشار پروکسی ضدتحریم (`Direct` ⬅ `AllOrigins Proxy` ⬅ `CodeTabs Proxy`)، منابع چندگانه (`CoinGecko v3`، `Binance v3`، `Coinbase v2`، `Tetherland`، `Nobitex v3`، `BrsApi`، `TSETMC CDN`)، **مثلث‌سازی زنده طلای ۱۸ عیار از اونس جهانی و تتر (`PAXG × USDT`)**، نگهبان صحت دامنه قیمت (`Circuit Breaker & Sanity Guard`) و **تست خودکار ۶ مرحله‌ای موتور قیمت** در داخل برنامه و در اسکریپت `scripts/update_prices.py --self-test`.
