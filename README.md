# Мета-теги для подтверждения владельца сайта

<details>
  <summary>📑 Оглавление</summary>

- [Цель](#цель)
- [Способы подтверждения](#способы-подтверждения)
- [Мета-теги для различных сервисов](#мета-теги-для-различных-сервисов)
  - [GitHub Pages](#github-pages)
  - [GitLab Pages](#gitlab-pages)
  - [Bitbucket Pages](#bitbucket-pages)
  - [Google](#google)
    - [Google Cloud Platform (GCP)](#google-cloud-platform-gcp)
    - [Google Merchant Center](#google-merchant-center)
    - [Google Optimize](#google-optimize)
    - [Google My Business](#google-my-business)
    - [Google Ads (AdWords)](#google-ads-google-adwords)
    - [Google Tag Manager](#google-tag-manager)
    - [Google Search Console](#google-search-console)
    - [Google Analytics (gtag.js)](#google-analytics-gtagjs)
  - [Яндекс](#яндекс)
  - [Mail Group / VK](#mail-group)
  - [LinkedIn](#linkedin)
  - [Bing](#bing)
  - [Pinterest](#pinterest)
  - [Baidu](#baidu)
  - [Meta (Facebook)](#meta-facebook)
  - [WeChat (微信)](#wechat-微信)
  - [Weibo (微博)](#weibo-微博)
  - [Douyin (抖音)](#douyin-抖ин)
  - [Naver](#naver-search-advisor)
  - [Alexa (by Amazon)](#alexa-by-amazon)
  - [🧰 CRM и SaaS](#-crm-и-saas)

</details>


## Цель

Позволяет использовать различные функции аналитики, рекламы и улучшенной видимости сайта в поисковой выдаче.

## Способы

В основном для использования некоторых сервисов требуется подтверждение владения сайтом
Подтверждение происходит несколькими способами:
- добавление мета-тега в <head>
- загрузка файла в корневую директорию сайта(на сервер)
- DNS-записи

## Мета-теги для различных сервисов

Список содержит мета-теги, которые можно использовать для подтверждения права на сайт в различных сервисах и поисковых системах.

Примечание:
Замените xxxxxx на свой уникальный код в соответствующем сервисе.

---


### GitHub Pages
Используется для подтверждения сайта, размещенного на GitHub Pages, в сторонних сервисах (например, Google или Bing). Сам GitHub не требует верификации через мета-теги, но некоторые SEO-инструменты могут использовать это.
```html
<meta name="github-site-verification" content="xxxxxx">
```

### GitLab Pages
Аналог GitHub Pages — верификация для сайтов, размещённых через GitLab CI/CD. Может использоваться сторонними платформами для подтверждения.
```html
<meta name="gitlab-site-verification" content="xxxxxx">
```

### Bitbucket Pages
Мета-тег для верификации сайтов, размещённых через Bitbucket Pipelines и Bitbucket Pages.
```html
<meta name="bitbucket-site-verification" content="xxxxxx">
```


---

## Google
### Google Cloud Platform (GCP)
```html
<meta name="google-cloud-verification" content="xxxxxx">
```

### Google Merchant Center
```html
<meta name="google-merchant-center" content="xxxxxx">
```

### Google Optimize
Для A/B-тестов и персонализации интерфейса.
```html
<script async src="https://www.googleoptimize.com/optimize.js?id=OPT-XXXXXX"></script>
```

### Google My Business
```html
<meta name="google-site-verification" content="xxxxxx">
```

### Google Ads (Google AdWords)
```html
<meta name="google-ads-site-verification" content="xxxxxx">
```

### Google Tag Manager
Инструмент для управления тегами на сайте.
```html
<script async src="https://www.googletagmanager.com/gtm.js?id=GTM-XXXXXX"></script>
```

### Google Search Console
```html
<meta name="google-site-verification" content="xxxxxx">
```

Google
### Google Analytics (gtag.js)
Отслеживание посещений, событий, пользовательского поведения.
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-XXXXXX-X"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'UA-XXXXXX-X');
</script>
```


---
## Яндекс

Мета-теги для сервисов Яндекса:

Используют тот же мета-тег, что и для Яндекс.Вебмастера
### Яндекс.Директ, Яндекс.Картинки , Yandex.Webmaster (Яндекс.Вебмастер):
```html
<meta name="yandex-verification" content="xxxxxx">
```

### Яндекс.Маркет:
```html
<meta name="yandex-market-verification" content="xxxxxx">
```

### Яндекс.Коннект (корпоративная почта):
```html
<meta name="yandex-connect-verification" content="xxxxxx">
```

### Яндекс.Телеметрика:
```html
<meta name="yandex-telemetrica-verification" content="xxxxxx">
```

### Yandex.Syndicator (Яндекс.Синдикатор):
```html
<meta name="yandex-syndicator-verification" content="xxxxxx">
```

### Yandex Analytics
```html
<meta name="yandex-analytics" content="xxxxxx">
```

### 7. Yandex.Metrica (Яндекс.Метрика)
```html
<script type="text/javascript" async src="https://mc.yandex.ru/metrika/tag.js"></script>
<script type="text/javascript">
(function (d, w, c) {
    (w[c] = w[c] || []).push(function() {
        try {
            w.yaCounterXXXXXX = new Ya.Metrika({
                id:XXXXXX,
                clickmap:true,
                trackLinks:true,
                accurateTrackBounce:true,
                webvisor:true
            });
        } catch(e) { }
    });
})(document, window, "yandex_metrika_callbacks");
</script>
```


---
## Mail Group

### Mail.ru
```html
<meta name="mailru-verification" content="xxxxxx">
```

### VK (ВКонтакте) Website Verification
```html
<meta name="vk-site-verification" content="xxxxxx">
```

### myTarget (платформа от VK/бывш. Mail.ru Group)
```html
<meta name="mytarget-verification" content="xxxxxx">
```

## VK / Mail.ru Group
### VK Pixel
Для сбора пользовательских данных, ретаргетинга и аналитики в рекламных кабинетах VK Реклама / myTarget.
```html
<script>
  !function(a,m,o,c,r,m){a[m]={id:"XXXXXX",hash:"",ts:Date.now(),start:function(p){a[m].queue.push(["start",p])},
  reachGoal:function(p){a[m].queue.push(["reachGoal",p])},queue:[]};
  var s=o.createElement(c);s.async=1;
  s.src="https://vk.com/js/api/openapi.js?169";
  var f=function(){o.getElementsByTagName(c)[0].parentNode.insertBefore(s,o.getElementsByTagName(c)[0]);};
  "complete"===o.readyState?f():a.addEventListener("load",f);
}(window,document,"script","_tmr");
_tmr.id = XXXXXX;
_tmr.start();
</script>
<noscript>
  <div><img src="https://vk.com/rtrg?p=XXXXXX" style="position:fixed; left:-999px;" alt="" /></div>
</noscript>
```

### myTarget Pixel (альтернатива)
```html
<script type="text/javascript">
    (function(w, d, s, h, id) {
        w.roistatProjectId = id; w.roistatHost = h;
        var p = d.location.protocol == "https:" ? "https://" : "http://";
        var u = p + h + '/api/site/1.0/' + id + '/init.js';
        var js = d.createElement(s); js.charset = "UTF-8"; js.async = 1; js.src = u;
        var js1 = d.getElementsByTagName(s)[0]; js1.parentNode.insertBefore(js, js1);
    })(window, document, 'script', 'top-fwz1.mail.ru', 'xxxxxx');
</script>
```


---

## LinkedIn

### LinkedIn Website Verification
```html
<meta name="linkedin-site-verification" content="xxxxxx">
```



## LinkedIn
### LinkedIn Insight Tag
Для отслеживания событий и аналитики в LinkedIn Ads.
```html
<script type="text/javascript">
  _linkedin_data_partner_id = "XXXXXX";
</script>
<script type="text/javascript">
  (function(){var s = document.createElement("script");
  s.type = "text/javascript"; s.async = true;
  s.src = "https://snap.licdn.com/li.lms-analytics/insight.min.js";
  var x = document.getElementsByTagName("script")[0];
  x.parentNode.insertBefore(s, x);})();
</script>
<noscript>
  <img height="1" width="1" style="display:none;" alt=""
       src="https://px.ads.linkedin.com/collect/?pid=XXXXXX&fmt=gif" />
</noscript>
```



---


## Bing

### Bing Webmaster Tools
Для подтверждения владельца сайта
```html
<meta name="msvalidate.01" content="xxxxxx">
```

### Bing Ads
Для рекламодателей
```html
<meta name="bing-ads-site-verification" content="xxxxxx">
```

### Bing Shopping
Для интеграции с Bing Shopping
```html
<meta name="bing-shopping-verification" content="xxxxxx">
```

### Bing Places
Для подтверждения местоположения бизнеса
```html
<meta name="bing-places-verification" content="xxxxxx">
```

---

## Pinterest

### Pinterest Webmaster Tools
Для подтверждения прав на сайт в Pinterest Business (например, чтобы подключить Rich Pins или аналитику).
```html
<meta name="pinterest-site-verification" content="xxxxxx">
<meta name="p:domain_verify" content="XXXXXX">
```

### Pinterest Tag (Pixel)
Для отслеживания конверсий, событий и ретаргетинга в Pinterest Ads.
```html
<script>
!function(e){if(!window.pintrk){window.pintrk = function () {
  window.pintrk.queue.push(Array.prototype.slice.call(arguments))};
  var n=window.pintrk;n.queue=[],n.version="3.0";
  var t=document.createElement("script");
  t.async=!0,t.src="https://s.pinimg.com/ct/core.js";
  var r=document.getElementsByTagName("script")[0];
  r.parentNode.insertBefore(t,r)}};
pintrk('load', 'XXXXXX');
pintrk('page');
</script>
<noscript>
  <img height="1" width="1" style="display:none;" alt=""
       src="https://ct.pinterest.com/v3/?event=init&tid=XXXXXX&noscript=1" />
</noscript>
```

---

## Baidu

### Baidu Webmaster Tools
Для подтверждения прав на сайт в инструментах для веб-мастеров Baidu.
```html
<meta name="baidu-site-verification" content="xxxxxx">
```

### Baidu Tongji (百度统计)
Это аналог Google Analytics — система веб-аналитики от Baidu.
```html
<script>
  var _hmt = _hmt || [];
  (function() {
    var hm = document.createElement("script");
    hm.src = "https://hm.baidu.com/hm.js?XXXXXX";
    var s = document.getElementsByTagName("script")[0]; 
    s.parentNode.insertBefore(hm, s);
  })();
</script>
```

### Baidu Ads Conversion Pixel (Baidu Tuiguang / 百度推广)
Для отслеживания конверсий в рекламной системе Baidu.
```html
<script type="text/javascript">
  var _bdhmProtocol = (("https:" == document.location.protocol) ? " https://" : " http://");
  document.write(unescape("%3Cscript src='" + _bdhmProtocol + "cpro.baidustatic.com/cpro/ui/f.js' type='text/javascript'%3E%3C/script%3E"));
</script>
```

### Baidu Event Tracking (через Tongji)
Для отслеживания пользовательских событий на сайте (например, кликов по кнопкам).
```html
<a href="#" onclick="_hmt.push(['_trackEvent', 'button', 'click', 'signup'])">Зарегистрироваться</a>
```

### Baidu Remarketing Pixel (再营销)
Для запуска ремаркетинга в Baidu Ads.
```html
<script>
  window._agl = window._agl || [];
  (function () {
    _agl.push(
      ['track', ['conversion', 'XXXXXX']]);
    var agl = document.createElement('script');
    agl.type = 'text/javascript';
    agl.async = true;
    agl.src = 'https://fxgate.baidu.com/track.js';
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(agl, s);
  })();
</script>
``

---

## Meta (Facebook)

### Верификация сайта в Facebook Business
Для подтверждения прав на сайт в Facebook Business
```html
<meta name="facebook-domain-verification" content="XXXXXX">
```

### Установка Facebook Pixel
Для отслеживания действий пользователей на вашем сайте с помощью Facebook Pixel
```html
<!-- Facebook Pixel -->
<script>
  !function(f,b,e,v,n,t,s){if(f.fbq)return;n=f.fbq=function(){n.callMethod
::contentReference[oaicite:44]{index=44}
```

### Meta Pixel (Facebook Pixel)
Для ретаргетинга и отслеживания конверсий.
```html
<script>
  !function(f,b,e,v,n,t,s){if(f.fbq)return;n=f.fbq=function(){n.callMethod ?
  n.callMethod.apply(n,arguments) : n.queue.push(arguments)};
  if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
  n.queue=[];t=b.createElement(e);t.async=!0;
  t.src=v;s=b.getElementsByTagName(e)[0];
  s.parentNode.insertBefore(t,s)}(window, document,'script',
  'https://connect.facebook.net/en_US/fbevents.js');
  fbq('init', 'XXXXXX');
  fbq('track', 'PageView');
</script>
<noscript>
  <img height="1" width="1" style="display:none"
    src="https://www.facebook.com/tr?id=XXXXXX&ev=PageView&noscript=1"/>
</noscript>
```



## WeChat (微信)
### Верификация сайта

Для привязки вашего сайта к официальному аккаунту WeChat необходимо:​
IT Workman
+1
IT Workman
+1

Войти в WeChat Official Accounts Platform. https://mp.weixin.qq.com/

Перейти в Настройки аккаунта → Настройки функционала → Бизнес-доменное имя.

Ввести домен вашего сайта и сохранить.​

⚠️ Обратите внимание, что домен должен быть подтверждён через ICP (Internet Content Provider) и иметь уровень 2 или выше.

### Установка WeChat JS SDK
Для интеграции функционала WeChat, такого как кнопка "Поделиться в WeChat", используйте следующий код:
```html
<!-- WeChat JS SDK -->
<script src="https://res.wx.qq.com/open/js/jweixin-1.6.0.js"></script>
<script>
  wx.config({
    debug: false,
    appId: 'YOUR_APP_ID',
    timestamp: 1234567890,
    nonceStr: 'YOUR_NONCE_STR',
    signature: 'YOUR_SIGNATURE',
    jsApiList: ['onMenuShareTimeline', 'onMenuShareAppMessage']
  });

  wx.ready(function () {
    wx.onMenuShareTimeline({
      title: 'YOUR_TITLE',
      link: 'YOUR_URL',
      imgUrl: 'YOUR_IMAGE_URL'
    });
    wx.onMenuShareAppMessage({
      title: 'YOUR_TITLE',
      desc: 'YOUR_DESCRIPTION',
      link: 'YOUR_URL',
      imgUrl: 'YOUR_IMAGE_URL'
    });
  });
</script>
<!-- End WeChat JS SDK -->
```



## Weibo (微博)
### Верификация аккаунта

Для получения "синей галочки" (Blue V) на Weibo необходимо:​
whatsonweibo.com

Зарегистрировать аккаунт на Weibo Official Account Platform.https://weibo.com/

Перейти в Настройки аккаунта → Верификация.

Выбрать тип верификации (индивидуальная или организационная) и следовать инструкциям.

### Установка Weibo Pixel
Для отслеживания конверсий и ретаргетинга на Weibo используйте следующий код:​
```html
<!-- Weibo Pixel -->
<script>
  var _wq = _wq || [];
  (function () {
    _wq.push(['track', ['conversion', 'YOUR_PIXEL_ID']]);
    var wq = document.createElement('script');
    wq.type = 'text/javascript';
    wq.async = true;
    wq.src = 'https://wq.weibo.com/track.js';
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(wq, s);
  })();
</script>
<!-- End Weibo Pixel -->
```

## Douyin (抖音)
### Верификация аккаунта
Для получения официального аккаунта на Douyin необходимо:​

Зарегистрировать аккаунт на Douyin Open Platform.https://open.douyin.com/

Перейти в Настройки аккаунта → Верификация.

Предоставить необходимые документы и информацию для проверки.​

### Установка Douyin Pixel
Для отслеживания действий пользователей и оптимизации рекламных кампаний на Douyin используйте следующий код:
```html
<!-- Douyin Pixel -->
<script>
  var _dy = _dy || [];
  (function () {
    _dy.push(['track', ['conversion', 'YOUR_PIXEL_ID']]);
    var dy = document.createElement('script');
    dy.type = 'text/javascript';
    dy.async = true;
    dy.src = 'https://fxgate.douyin.com/track.js';
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(dy, s);
  })();
</script>
<!-- End Douyin Pixel -->
```


### Naver Search Advisor
```html
<meta name="naver-site-verification" content="xxxxxx">
```

## Alexa (by Amazon)
### Alexa Site Verification
```html
<meta name="alexaVerifyID" content="xxxxxx">
```
⚠️ Внимание: Alexa Internet официально закрыта. Этот тег сегодня не имеет практической ценности, кроме как исторической или при миграции с устаревших систем.

## 🧰 CRM и SaaS
### HubSpot
```html
<meta name="hubspot-site-verification" content="xxxxxx">
```

### Slack
```html
<meta name="slack-site-verification" content="xxxxxx">
```

### Disqus
```html
<meta name="disqus-site-verification" content="xxxxxx">
```

### GoDaddy
```html
<meta name="disqus-site-verification" content="xxxxxx">
```
