# Data sources index · 大台北柔術課表

**Master source index** for refreshing gym / schedule / coach / transit data.

- **Data as-of:** 2026-10-02 / 2026-10-03 (Asia/Taipei)
- **Rule:** only public official sites / IG / FB (and taiwanbjj.org branch pages). Do not invent URLs or coaches.
- **UI:** the live Pages site also shows each gym’s `sources` links in the detail panel when you open a gym.
- **Canonical data in code:** `index.html` → `const GYMS` / `const SLOTS`

## Related files

| File | Role |
|---|---|
| [COACHES.md](./COACHES.md) | Coach coverage table + evidence notes |
| [transit_notes.txt](./transit_notes.txt) | Distance / MRT / walk / transit estimates from Taiwanogi |
| [sources_ufcgym.txt](./sources_ufcgym.txt) | UFC GYM Dunnan / Neihu schedule capture notes |
| [README.md](./README.md) | Site overview · points here for sources |
| `index.html` | Deployed UI + embedded GYMS/SLOTS |

## Per-gym registry

### Taiwanogi (`taiwannogi`)

- **District:** 大安
- **Address:** 台北市大安區延吉街131巷1弄26號B1
- **Transit (embedded):** MRT 忠孝敦化 · 0.0 km · ~0 min · access `easy`
- **Transit detail string:** 基準點（延吉街 · 近忠孝敦化／國父紀念館）
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** 許軒維 · Steve — [官網](https://www.taiwannogi.com/)
- **Schedule image:** `taiwannogi_october_schedule_clear.png`
- **Note:** 週四滾到飽 NEW；幾乎全 No-Gi
- **Schedule / page sources** (from `GYMS.sources`):
  - [IG 課表](https://www.instagram.com/taiwannogi/p/DdwXbzvRsUS/)
  - [官網](https://www.taiwannogi.com/)
  - [課表圖](https://images.squarespace-cdn.com/content/v1/662f7814966d1f3bf331af4a/ba39b56e-ad08-4170-ade9-2f922ada42dc/New+Schedule+%284%29.png)

### 10th Planet Taipei (`10thplanet`)

- **District:** 松山
- **Address:** 台北市松山區復興北路369號B1（公司登記另列信義基隆路一段398號4樓）
- **Transit (embedded):** MRT 中山國中 · 2.2 km · ~22 min · access `ok`
- **Transit detail string:** 忠孝復興轉文湖至中山國中再步行 · 約20–25分
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** Marshall Stamper — [官網課表](https://www.10thplanettaipei.com/schedule)
- **Schedule image:** _(none)_
- **Note:** 全館 No-Gi；無獨立 open mat
- **Schedule / page sources** (from `GYMS.sources`):
  - [官網課表](https://www.10thplanettaipei.com/schedule)
  - [官網](https://www.10thplanettaipei.com/)

### 腕鎖（土城） (`wristlock`)

- **District:** 新北土城
- **Address:** 新北市土城區中正路1號B1-2
- **Transit (embedded):** MRT 海山 · 12.5 km · ~38 min · access `ok`
- **Transit detail string:** 板南線直達海山 · 出口近
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** Nick Lok — [教練 Nick Lok](https://taiwanbjj.org/en/nick-lok/)
- **Schedule image:** `taiwanbjj_wristlock_schedule.png`
- **Note:** 台巴體系土城；平日 21:00 Open Mat（2026-03 圖）
- **Schedule / page sources** (from `GYMS.sources`):
  - [官網](https://wristlockjiujitsu.com/)
  - [教練 Nick Lok](https://taiwanbjj.org/en/nick-lok/)
  - [IG seminar](https://www.instagram.com/wristlockjiujitsu/p/Dd3iYvoT2QF/)

### 武甲 (`wuja`)

- **District:** 大直／古亭／永和
- **Address:** 新北市永和區民權路53號1樓（課表圖為永和館；另有大直／古亭）
- **Transit (embedded):** MRT 頂溪 · 5.3 km · ~30 min · access `ok`
- **Transit detail string:** 板南至忠孝復興轉中和新蘆至頂溪再步行
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** 宋明諺 · 王羅傑 — [教練頁](https://www.wu-ja.com/coaches)
- **Schedule image:** `wuja_yonghe_schedule_clear.png`
- **Note:** 自主對打未必純 BJJ
- **Schedule / page sources** (from `GYMS.sources`):
  - [官網](https://www.wu-ja.com/)
  - [教練頁](https://www.wu-ja.com/coaches)
  - [IG 永和](https://www.instagram.com/martial_armour/p/DbX21UGnfJv/)

### PMA 台北 (`pma`)

- **District:** 中山
- **Address:** 台北市中山區新生北路三段82巷33號1樓
- **Transit (embedded):** MRT 圓山 · 3.9 km · ~32 min · access `ok`
- **Transit detail string:** 忠孝復興轉淡水信義至圓山／雙連再步行
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** — (none evidenced; see COACHES.md)
- **Schedule image:** `pma_taipei_october_schedule_clear.png`
- **Schedule / page sources** (from `GYMS.sources`):
  - [IG 課表](https://www.instagram.com/pmabjjtaipei/p/DdyJbPPosJu/)

### DFA 降龍 (`dfa`)

- **District:** 中正
- **Address:** 台北市中正區杭州南路一段10號B1
- **Transit (embedded):** MRT 善導寺 · 2.9 km · ~18 min · access `easy`
- **Transit detail string:** 板南線直達善導寺 · 4號出口步行約5分
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** Eliot · 劉漢仁 — [教練師資](https://www.dfamma.com/contact/)
- **Schedule image:** `dfa_october_2026_schedule_clear.png`
- **Note:** BJJ 班未標 Gi/No-Gi
- **Schedule / page sources** (from `GYMS.sources`):
  - [IG 課表](https://www.instagram.com/dragonfightart/p/Dd6i9y_NgRQ/)
  - [教練師資](https://www.dfamma.com/contact/)

### 巴柔海山 (`haishan`)

- **District:** 新北土城
- **Address:** 新北市土城區清水路33號1F
- **Transit (embedded):** MRT 海山 · 12.1 km · ~42 min · access `hard`
- **Transit detail string:** 板南線直達海山再步行清水路
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** Otis Huang — [IG](https://www.instagram.com/taiwanbjj_hs/p/DcQrXDou5Ye/)
- **Schedule image:** `taiwanbjj_haishan_schedule_clear.png`
- **Note:** 體驗課表
- **Schedule / page sources** (from `GYMS.sources`):
  - [IG](https://www.instagram.com/taiwanbjj_hs/p/DcQrXDou5Ye/)

### 台巴·台北本院 (`twbjj_taipei`)

- **District:** 中山吉林
- **Address:** 台北市中山區吉林路12-3號B1
- **Transit (embedded):** MRT 松江南京 · 2.6 km · ~25 min · access `ok`
- **Transit detail string:** 忠孝新生轉松江南京 · 或步行／短程公車
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** 小笠原誠 · Makoto Ogasawara — [教練總覽](https://taiwanbjj.org/en/instructors/)
- **Schedule image:** `taiwanbjj_taipei_jilin_schedule.png`
- **Note:** 2026-09 課表；含多時段 Open Mat
- **Schedule / page sources** (from `GYMS.sources`):
  - [分館頁](https://taiwanbjj.org/en/taipei/)
  - [課表圖](https://taiwanbjj.org/twbjj-wp-04/wp-content/uploads/2026/09/20260914%E5%8F%B0%E5%8C%97%E6%9C%AC%E9%99%A2%E8%AA%B2%E8%A1%A8-1.jpg)
  - [Facebook](https://www.facebook.com/taiwanbjj/)
  - [教練總覽](https://taiwanbjj.org/en/instructors/)

### 台巴·中正 (`twbjj_zhongzheng`)

- **District:** 中正
- **Address:** 台北市中正區南昌路一段153號2F
- **Transit (embedded):** MRT 古亭 · 4.3 km · ~28 min · access `ok`
- **Transit detail string:** 忠孝復興轉淡水信義／中和新蘆至古亭再步行
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** Johnny Pai — [分館頁](https://taiwanbjj.org/en/zhongzheng/)
- **Schedule image:** `taiwanbjj_zhongzheng_schedule.png`
- **Note:** 平日 21:30 Open Mat
- **Schedule / page sources** (from `GYMS.sources`):
  - [分館頁](https://taiwanbjj.org/en/zhongzheng/)
  - [IG](https://www.instagram.com/taiwanbjj_zhzh/)

### 台巴·中和 (`twbjj_zhonghe`)

- **District:** 新北中和
- **Address:** 新北市中和區中正路755號2F
- **Transit (embedded):** MRT 橋和 · 8.0 km · ~40 min · access `ok`
- **Transit detail string:** 轉環狀線／中和新蘆至橋和再步行
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** Otis Huang — [分館頁](https://taiwanbjj.org/en/zhonghe/)
- **Schedule image:** `taiwanbjj_zhonghe_schedule.png`
- **Schedule / page sources** (from `GYMS.sources`):
  - [分館頁](https://taiwanbjj.org/en/zhonghe/)
  - [IG](https://www.instagram.com/taiwanbjj_zhonghe/)

### 台巴·海山 (`twbjj_haishan`)

- **District:** 新北土城
- **Address:** 新北市土城區清水路33號1F
- **Transit (embedded):** MRT 海山 · 12.1 km · ~42 min · access `hard`
- **Transit detail string:** 板南線直達海山再步行清水路
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** Otis Huang — [分館頁](https://taiwanbjj.org/en/taiwan-bjj-branch/)
- **Schedule image:** `taiwanbjj_haishan_schedule.png`
- **Note:** 與中和同教練體系
- **Schedule / page sources** (from `GYMS.sources`):
  - [分館頁](https://taiwanbjj.org/en/taiwan-bjj-branch/)
  - [IG](https://www.instagram.com/taiwanbjj_hs/)

### 台巴·安坑 (`twbjj_ankeng`)

- **District:** 新北新店
- **Address:** 新北市新店區安城街2巷3號
- **Transit (embedded):** MRT 安坑 · 10.0 km · ~55 min · access `hard`
- **Transit detail string:** 轉安坑輕軌／新店線 · 較偏遠
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** Sean Huang — [分館頁](https://taiwanbjj.org/en/ankeng/)
- **Schedule image:** `taiwanbjj_ankeng_schedule.png`
- **Note:** 課表偏週末／三五
- **Schedule / page sources** (from `GYMS.sources`):
  - [分館頁](https://taiwanbjj.org/en/ankeng/)
  - [IG](https://www.instagram.com/taiwanbjjankeng/)

### 台巴·林口 (`twbjj_linkou`)

- **District:** 新北林口
- **Address:** 新北市林口區忠孝三路28號
- **Transit (embedded):** MRT 林口 · 19.6 km · ~65 min · access `hard`
- **Transit detail string:** 轉機場線至林口 · 約50–70分
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** Jerry Cheng — [分館頁](https://taiwanbjj.org/en/linkou/)
- **Schedule image:** `taiwanbjj_linkou_schedule.png`
- **Schedule / page sources** (from `GYMS.sources`):
  - [分館頁](https://taiwanbjj.org/en/linkou/)
  - [FB](https://www.facebook.com/TWBJJLinkou/)

### 台巴·新莊 (`twbjj_xinzhuang`)

- **District:** 新北新莊
- **Address:** 新北市新莊區萬安街53號
- **Transit (embedded):** MRT 丹鳳 · 13.7 km · ~50 min · access `hard`
- **Transit detail string:** 轉中和新蘆至丹鳳／新莊再步行
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** — (none evidenced; see COACHES.md)
- **Schedule image:** `taiwanbjj_xinzhuang_schedule.png`
- **Note:** 含瑜珈／TRX 非柔術時段已略
- **Schedule / page sources** (from `GYMS.sources`):
  - [分館頁](https://taiwanbjj.org/en/xinzhuang/)

### 台巴·汐止 (`twbjj_xizhi`)

- **District:** 新北汐止
- **Address:** 新北市汐止區水源路一段122號1F
- **Transit (embedded):** MRT 汐科 · 10.4 km · ~55 min · access `hard`
- **Transit detail string:** 板南至南港轉台鐵至汐科／汐止再步行 · 無近捷運
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** — (none evidenced; see COACHES.md)
- **Schedule image:** `taiwanbjj_xizhi_schedule.png`
- **Schedule / page sources** (from `GYMS.sources`):
  - [分館頁](https://taiwanbjj.org/en/xi-zhi/)

### UFC GYM 敦南 (`ufcgym_dunnan`)

- **District:** 大安
- **Address:** 台北市大安區安和路一段27號B1
- **Transit (embedded):** MRT 忠孝敦化 · 0.5 km · ~12 min · access `easy`
- **Transit detail string:** 忠孝敦化5號出口步行約2分（同站圈）
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** — (none evidenced; see COACHES.md)
- **Schedule image:** `ufcgym_dunnan_schedule.png`
- **Note:** 課表圖為 2023-05 公開版；現行請以 App／館內為準。無標 Open Mat
- **Schedule / page sources** (from `GYMS.sources`):
  - [官網](https://www.ufcgym.com.tw/)
  - [FB 敦南](https://www.facebook.com/UFCGYMTWDunhua/)
  - [預約](https://booking.ufcgym.com.tw/)
- **UFC capture notes:** [sources_ufcgym.txt](./sources_ufcgym.txt)

### UFC GYM 內科 (`ufcgym_neihu`)

- **District:** 內湖
- **Address:** 台北市內湖區洲子街55號1F
- **Transit (embedded):** MRT 港墘 · 4.5 km · ~35 min · access `ok`
- **Transit detail string:** 需轉文湖線至港墘 · 2號出口步行約1分
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** — (none evidenced; see COACHES.md)
- **Schedule image:** `ufcgym_neihu_schedule.png`
- **Note:** 課表圖為 2024-09 公開版；無標 Open Mat
- **Schedule / page sources** (from `GYMS.sources`):
  - [官網](https://www.ufcgym.com.tw/)
  - [FB 內湖](https://www.facebook.com/UFCGYMTWNeihu/)
  - [預約](https://booking.ufcgym.com.tw/)
- **UFC capture notes:** [sources_ufcgym.txt](./sources_ufcgym.txt)

### 修羅場 (`shuraba`)

- **District:** 板橋
- **Address:** 新北市板橋區民生路二段226巷32號（公開資料；舊址曾列文化路）
- **Transit (embedded):** MRT 新埔 · 8.9 km · ~35 min · access `ok`
- **Transit detail string:** 板南線直達新埔再步行 · 約30–40分
- **Transit notes pointer:** see [transit_notes.txt](./transit_notes.txt) (Taiwanogi-origin estimates)
- **Coaches:** Scott · Eliot — [Facebook](https://www.facebook.com/SRBMMA)
- **Schedule image:** `shuraba_facebook_schedule_update.png`
- **Note:** 課表標示 Coach Scott／Eliot
- **Schedule / page sources** (from `GYMS.sources`):
  - [Facebook](https://www.facebook.com/SRBMMA)

## Refresh checklist

1. Re-check each gym’s official URLs above; update `GYMS.sources` in `index.html` if links move.
2. Re-OCR / replace schedule images; keep filenames or update `GYMS.image` + SLOTS.
3. Re-verify coaches against official pages; sync [COACHES.md](./COACHES.md) and `GYMS.coaches`.
4. Re-check transit with [transit_notes.txt](./transit_notes.txt); update `km` / `transitMin` / `access` / `transit`.
5. Bump the “資料截至” date in `index.html` header/meta copy.

## Pages

- Site: https://kuanting-wu.github.io/taipei-bjj-schedules/
- Repo: https://github.com/kuanting-wu/taipei-bjj-schedules

