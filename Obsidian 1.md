# Obsidian Vault - Bütün qeydlər

*Toplanma tarixi: 2026-10-15*
*Mənbə: C:\Users\senan\Documents\Obsidian Vault*

---

## 📋 İNTERVIEW HAZIRLIĞI

1. [[Monitorinq Prinsipləri və Alətləri]] +
2. [[Veb-texnologiyalar]] +
3. [[Logging və Management]] +
4. Mikroservislər və Smartscape +
5. [[Troubleshooting]] +
6. [[SQL]] +
7. [[Network]] +
8. [[DevOps]] +
9. [[Git]]
10. docker + kubernest +
11. coolify

**Boş yerlər:** NVR, DHCP/DNS, VLAN, Acronis, Veeam, Norton Backup, SQL Server, Windows troubleshooting, Jira, Zoho Desk

**QA playlist:** https://www.youtube.com/watch?v=v3Qxf1PG0fo&list=PLfw_nI4u_6WM8200HlderALoIYKpSa4W6

---

## 🎯 MONİTORİNQ PRİNSİPLƏRİ VƏ ALƏTLƏRİ

Sistemlərin sağlamlığını (health), performansını və resurs istifadəsini izləmək üçündür.

1. **Prometheus** və **Grafana** — Prometheus sistemdən metrikaları (CPU, RAM istifadəsi və s.) toplayır. Grafana isə bu məlumatları gözəl vizual qrafiklərə (dashboard) çevirir.
2. **Dynatrace** — çox güclü, şəninki intellekt (AI) dəstəkli monitorinq alətidir. Sistemdəki xətanın kök səbəbini (Root cause) avtomatik tapmaq xüsusiyyəti var.
3. **Firebase** və **Google Analytics** — Daha çox frontend və mobil tətbiqlərdə istifadəçi davranışını, tətbiq çökmələrini (crashlytics) izləmək üçündür.

---

## 🌐 VEB-TEXNOLOGİYALAR

1. **REST** (Representational State Transfer): Sistemlərin (front və back-end) bir-biri ilə JSON və ya XML formatında əlaqə qurması üçün standartdır. Əsas HTTP metodları ilə işləyir: `GET` (məlumat almaq), `POST` (yaratmaq), `PUT` (yeniləmək), `DELETE` (silmək).
2. **Cloud-based tətbiqlər** — Lokal fiziki serverlərdə yox, bulud mühitində (AWS, Azure, Google Cloud) işləyən tətbiqlərdir. Üstünlüyü: Avtomatik miqyaslana bilməsi (scalability) və yüksək əlçatanlıqdır (high availability).

---

## 📊 NETWORK

- **HTTP/HTTPS:** Veb-brauzer və server arasındakı məlumat mübadiləsi protokolu (HTTPS bunun şifrələnmiş, təhlükəsiz versiyasıdır).

- **DNS (Domain Name System):** Sayt adlarını (məsələn, `google.com`) serverin oxuya biləcəyi IP ünvanlarına (məsələn, `142.250.190.46`) çevirən sistem. "İnternetin telefon kitabı" da deyilir.

- **Load-balancer:** Sistemə gələn istifadəçi trafikini bir neçə server arasında bərabər bölüşdürür ki, bir server yüklənməsin, digərlərini dayandırmasın.

---

## 📝 LOGGING VƏ MANAGEMENT

Sistemdə baş verən bütün hadisələrin və xətaların (log-ların) bir mərkəzə toplanması prosesidir. Buna çox vaxt **ELK Stack** (Elasticsearch, Logstash, Kibana) deyilir.

1. **Elasticsearch** — Log məlumatlarını saxlamaq və milyonlarla sətir log içərisində saniyələr ərzində axtarış etmək üçün mühərrikdir.
2. **Logstash**
3. **Kibana** — Elasticsearch-də olan loqları oxuyub vizuallaşdıran interfeysdir.

---

## 🔧 TROUBLESHOOTING

Müsahibədə səndən problem həll etmə məntiqini (Root Cause Analysis) soruşa bilərlər. Yanaşma belə olmalıdır:

1. Grafana və ya Dynatrace-dən xətanı (alert) görmək.

2. Kibana vasitəsilə həmin vaxta aid loqları oxumaq.

3. Problemin haradan qaynaqlandığını (məsələn: bazada sorğu gecikməsi, yaddaş sızması (memory leak), şəbəkə xətası) tapıb həll etmək.

---

## 🗄️ SQL

Məlumatların saxlanması və idarə olunması. SQL (Relational Database) üçün əsas bilməli olduğun anlayışlar:

- **CRUD əməliyyatları:** Create, Read, Update, Delete.

- **JOIN-lər:** İki və ya daha çox cədvəli (table) birləşdirib məlumat çəkmək.

- **İndeksləmə (Indexing):** Axtarış sorğularının (query) sürətli işləməsi üçün istifadə olunur.

---

## ⚙️ DEVOPS

- **Kubernetes** (K8s): Konteynerləşdirilmiş (adətən Docker) tətbiqləri idarə edən (orchestration) sistemdir. Tətbiq çökdükdə onu yenidən başladır, trafik artdıqda yeni kopyalarını yaradır (auto-scaling).

- **OpenShift** — Red Hat şirkətinin Kubernetes üzərində qurduğu daha inkişaf etmiş, təhlükəsiz və idarəetmə interfeysi hazır olan enterprise platformadır.

---

## ☁️ CLOUD-BASED TƏTBİQLƏR

1. AWS
2. Azure
3. Google Cloud

---

## 🔀 GIT

Versiya nəzarət sistemidir (Version Control System). Kod üzərində komanda şəklində işləməyə imkan verir. Əsas komandalar:

- `git clone` (kodu lokal kompüterə yükləmək)

- `git commit` (dəyişiklikləri yadda saxlamaq)

- `git push` (dəyişiklikləri mərkəzi repozitoriyaya göndərmək)

- `git branch` / `git merge` (yeni xüsusiyyətlər üçün ayrılmış qol yaratmaq və sonra əsas koda birləşdirmək).

---

## 🌐 ENG (İngilis dili)

### 1- Hobbies

Everyone has different hobbies, and people usually pick them up to escape from the daily routine and stress. I have different hobbies. In my free time, I'm deeply into gaming. I play a lot of Valorant, which is a competitive shooter with esports tournaments, and I also love story-driven games like GTA V, Cyberpunk 2077.

And to stay active, I play football every couple of weeks. My downtime is fueled by music, mostly American tracks, electronic styles, and nostalgic electronic music that makes me feel like I'm in a Sigma edit. When I need a quieter hobby, I play my harmonica at home. That's how I balance things out.

---

## 📁 BOŞ FAYLLAR (içindəki məzmun yoxdur)

- Dynatrace.md
- Google Cloud.md
- Grafana.md
- Prometheus.md
- Untitled.md

---

## 📌 BU SESSİYADA ƏLAVƏ EDİLMİŞ MODULLAR (vakansiya roadmap)

| # | Modul | Status |
|---|---|---|
| 1 | TCP/IP, IP, subnet, ping, portlar | ✅ |
| 2 | DHCP, DNS, nslookup | ✅ |
| 3 | Switch, router, AP, VLAN, LAN/WAN | ✅ |
| 4 | IP kameralar, NVR, DVR | ✅ |
| 5 | Windows Server + Active Directory | ✅ |
| 6 | RJ45 kabel, crimping, patch panel | ✅ |
| 7 | Backup/restore, 3-2-1 | ✅ |
| 8 | SQL Server, SQL əmrləri | ✅ |
| 9 | Helpdesk, SLA, problem scoping | ✅ |
| 10 | Windows troubleshooting | ✅ |

**Yarım qalanlar:**
- Düz/çarpax kabel (hansı halda)
- NVR troubleshooting (ping ilk addım)