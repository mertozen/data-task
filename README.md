# Tech Blog XML Task Listesi (Not: Bütün kaynaklar Tech-Blog-XML-Sources bölümündendir.)

## Backend / Data Engineering Görevleri

### 1️⃣ RSS Blog Çekme Servisi
- **Açıklama:** Python kullanarak listedeki tüm kaynaklardan günlük olarak son 5 makaleyi çeken bir servis yaz.
- **Kriterler:**
  - Her kaynak için: title, link, published_date, source_name bilgileri çekilecek.
  - MongoDB veya PostgreSQL’e kaydedilecek.
- **Ek Not:** Cron job veya scheduler kullanılacak.

### 2️⃣ RSS Feed Health Check Script
- **Açıklama:** XML kaynaklarının aktif olup olmadığını kontrol eden bir script hazırla.
- **Kriterler:**
  - 404, 500 gibi hata veren feed’ler loglanacak.
  - Rapor formatı: CSV veya JSON çıktısı.

## Frontend / Fullstack Görevleri

### 3️⃣ Tech Blog Reader Uygulaması
- **Açıklama:** React veya Next.js kullanarak teknoloji blog reader uygulaması geliştir.
- **Kriterler:**
  - Sol menü: Kaynak listesi (source_name)
  - Sağ panel: Seçilen kaynağın son 10 makalesi
  - Basit ve modern tasarım (Chakra UI veya Tailwind CSS önerilir)

### 4️⃣ RSS Feed Dashboard
- **Açıklama:** RSS içeriklerini ve kaynak durumlarını gösteren bir dashboard hazırla.
- **Kriterler:**
  - Son güncellenen kaynaklar listesi
  - Erişilemeyen kaynakların uyarısı

## AI / NLP Görevleri

### 5️⃣ Keyword Analiz Scripti
- **Açıklama:** Tüm RSS içerikleri üzerinden en çok geçen keyword’leri analiz et.
- **Kriterler:**
  - En çok geçen 20 kelimeyi haftalık olarak raporla.
  - Görsel grafik veya JSON çıktısı üret.

### 6️⃣ Otomatik Blog Özetleme Pipeline’ı
- **Açıklama:** RSS içeriklerinden summary (özet) oluşturan bir NLP pipeline hazırla.
- **Kriterler:**
  - LLM veya hazır NLP kütüphanesi kullanılabilir.
  - Özetler maksimum 300 karakter olacak şekilde ayarlanacak.

## DevOps / Automation Görevleri

### 7️⃣ RSS Fetching Cron Job
- **Açıklama:** RSS feed’leri periyodik çeken bir cron job veya AWS Lambda fonksiyonu oluştur.
- **Kriterler:**
  - 1 saatte bir çalışacak şekilde ayarlanacak.
  - Hata loglama ve monitoring yapılacak.

### 8️⃣ RSS Monitoring Paneli
- **Açıklama:** Tüm kaynakların erişilebilirlik durumunu gösteren bir monitoring paneli hazırla.
- **Kriterler:**
  - Aktif/pasif kaynak listesi
  - Son erişim zamanı
  - Opsiyonel: Slack veya e-posta bildirim entegrasyonu

---

# Tech-Blog-XML-Sources

* Airbnb https://medium.com/feed/airbnb-engineering  
* Adyen https://medium.com/feed/adyen 
* Atlassian https://developer.atlassian.com/blog/feed.xml 
* Auth0 https://auth0.com/blog/rss.xml 
* AWS https://aws.amazon.com/blogs/aws/feed/ 
* BBC https://medium.com/feed/bbc-design-engineering 
* BitTorrent https://engineering.bittorrent.com/feed/ 
* Booking.com https://medium.com/feed/booking-com-development
* Buzzfeed https://tech.buzzfeed.com/feed 
* Canva https://product.canva.com/feed.xml 
* Cloudflare https://blog.cloudflare.com/rss/ 
* Confluent https://www.confluent.io/feed/ 
* DigitalOcean https://www.digitalocean.com/community/tutorials/feed 
* Docker https://blog.docker.com/feed/ 
* Doordash  https://doordash.engineering/wp-json/wp/v2/posts  
* Dropbox https://blogs.dropbox.com/tech/feed/ 
* Ebay https://www.ebayinc.com/stories/blogs/tech/rss/ 
* Envoy https://envoy.engineering/feed 
* Evernote https://evernote.com/blog/feed/ 
* Facebook https://code.fb.com/feed/ 
* Facebook AI Research https://research.fb.com/feed/ 
* Flipboard http://engineering.flipboard.com/feed.xml 
* GIPHY https://engineering.giphy.com/rss 
* GitHub https://githubengineering.com/atom.xml 
* Google Cloud https://medium.com/feed/google-cloud 
* Google Online Security https://security.googleblog.com/feeds/posts/default 
* Google Research http://ai.googleblog.com/feeds/posts/default 
* Heroku https://blog.heroku.com/feed 
* IBM developerWorks https://developer.ibm.com/dwblog/feed/ 
* Imgur https://blog.imgur.com/feed/ 
* Indeed http://engineering.indeedblog.com/feed/ 
* Instagram https://instagram-engineering.com/feed 
* Kickstarter https://kickstarter.engineering/feed 
* LinkedIn https://engineering.linkedin.com/blog.rss.html 
* Lyft https://eng.lyft.com/feed 
* Medium https://medium.engineering/feed 
* MongoDB https://engineering.mongodb.com/post?format=RSS 
* Mozilla Hacks https://hacks.mozilla.org/feed/ 
* Mozilla Release Engineering http://planet.mozilla.org/releng/atom.xml 
* Netflix https://medium.com/feed/netflix-techblog 
* Nvidia https://blogs.nvidia.com/feed/ 
* Okta https://developer.okta.com/feed.xml
* OpenDNS https://umbrella.cisco.com/blog/feed/ 
* Paypal https://medium.com/feed/paypal-engineering
* Pinterest https://medium.com/feed/@Pinterest_Engineering 
* Postman https://medium.com/feed/better-practices
* Prezi https://engineering.prezi.com/feed 
* Red Hat https://developers.redhat.com/blog/feed/atom/ 
* Riot Games https://engineering.riotgames.com/rss.xml 
* Salesforce https://developer.salesforce.com/blogs/feed 
* Shopify http://engineering.shopify.com/blogs/engineering.atom 
* Skyscanner https://medium.com/feed/@SkyscannerEng 
* Slack https://slack.engineering/feed 
* Soundcloud https://developers.soundcloud.com/blog.rss 
* Square https://medium.com/feed/square-corner-blog 
* Stack Overflow https://stackoverflow.blog/engineering/feed/ 
* Stormpath https://stormpath.com/feed 
* Stripe https://stripe.com/blog/feed.rss 
* Strava https://medium.com/feed/strava-engineering 
* Spotify https://labs.spotify.com/feed/ 
* ThoughtWorks https://www.thoughtworks.com/rss/insights.xml 
* Tinder https://medium.com/feed/tinder-engineering 
* Toptal https://www.toptal.com/blog.rss 
* Trello https://tech.trello.com/feed.xml 
* Trivago https://tech.trivago.com/index.xml 
* Tumblr https://engineering.tumblr.com/rss 
* Twilio https://www.twilio.com/blog/feed  
* Twitter https://blog.twitter.com/engineering/feed 
* Twitch https://medium.com/feed/twitch-news/tagged/engineering 
* Uber https://eng.uber.com/feed/ 
* Venmo https://medium.com/feed/vevo-engineering 
* WalmartLabs https://medium.com/feed/walmartlabs 
* Wayfair https://tech.wayfair.com/feed/ 
* Yahoo https://yahooeng.tumblr.com/rss 
* Yelp https://engineeringblog.yelp.com/feed.xml 
* Zalando https://engineering.zalando.com/atom.xml 
* Zendesk https://medium.com/feed/zendesk-engineering 
* Hackernews https://news.ycombinator.com/rss 
* Machine Learning Apple https://machinelearning.apple.com/rss.xml 
* Martin Fowler https://martinfowler.com/feed.atom 
