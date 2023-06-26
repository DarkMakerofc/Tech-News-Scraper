<h3 align="center">🌐 TECHNOLOGY NEWS SCRAPER 🌐</h1> 
<p align="center">
<img src="https://telegra.ph/file/26212af0580bdc2733de7.jpg" width="300" height="300"/>
</p>

<p align="center"> This Tech News Scraper By Mr , By using this scraper you can get latest technology news, you can use it for your bot </p>

##### ✅ Install package 
```
yarn add tech-news-scraper
```

##### ℹ️ Example 
```
const { techNews } = require("tech-news-scraper")
const news = await techNews()

console.log(news)

```

##### 🔍 Result 


```
{
  creator: 'MR NIMA',
  status: true,
  result: [
    {
      no: 1,
      title: 'Amazfit Pop 3R Smartwatch With 1.43-Inch AMOLED Display, Bluetooth Calling Launched in India',      date: ' 26 June 2023',
      catname: 'Wearables',
      img: 'https://i.gadgets360cdn.com/large/amazfit_pop_3r_smartwatch_thumb_1687777139176.jpg',                 link: 'https://www.gadgets360.com/wearables/news/amazfit-pop-3r-smartwatch-price-in-india-rs-3499-launch-sale-date-june-29-specifications-features-4153680'     },
    {
      no: 2,
      title: 'Google Parent Alphabet, Airtel Bet on Laser Technology to Deliver Internet Service in Remote Areas',
      date: ' 26 June 2023',
      catname: 'Internet',
      img: 'https://i.gadgets360cdn.com/large/google_reuters_thumb_1680153631910.jpg',
      link: 'https://www.gadgets360.com/internet/news/google-alphabet-internet-access-bharti-airtel-remote-areas-laser-beam-taara-4153831'
    },
    {
      no: 3,
      title: 'Samsung SeeColors Accessibility Mode for Colour Blind Users Added to 2023 TV and Monitor Lineup: Details',
      date: ' 26 June 2023',
      catname: 'Home Entertainment',
      img: 'https://i.gadgets360cdn.com/large/seecolors_accessibility_colour_blindness_samsung_thumb_1687779004907.jpg',
      link: 'https://www.gadgets360.com/tv/news/samsung-seecolors-mode-tv-monitor-colour-blind-users-accessibility-feature-4153497'
    },
    {
      no: 4,
      title: 'Nothing Phone 2 Pre-Orders to Start in India on June 29 Via Flipkart: All Details',
      date: ' 26 June 2023',
      catname: 'Mobiles',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/mobiles/news/nothing-phone-2-india-pre-order-june-29-launch-july-11-flipkart-carl-pei-4153594'
    },
    {
      no: 5,
      title: 'Oppo, OnePlus or Realme Could Offer Smartphones With Up to 24GB RAM Soon: All Details',
      date: ' 26 June 2023',
      catname: 'Mobiles',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/mobiles/news/oneplus-oppo-realme-24gb-ram-smartphone-launch-details-leak-4153535'
    },
    {
      no: 6,
      title: 'Cybercriminals Send Bomb Threats to US Retail Stores, Demand Bitcoin Payments: Report',
      date: ' 26 June 2023',
      catname: 'Cryptocurrency',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/cryptocurrency/news/bitcoin-demand-notorious-actors-bomb-threat-walmart-whole-foods-us-4153505'
    },
    {
      no: 7,
      title: 'Sony Bravia XR X90L Television Series With Dolby Vision, Google TV Launched in India: Price, Specifications',
      date: ' 26 June 2023',
      catname: 'Home Entertainment',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/tv/news/sony-bravia-xr-x90l-tv-55-65-75-inch-price-in-india-rs-139999-launch-specifications-features-4153486'
    },
    {
      no: 8,
      title: 'iPhone 15 Pro Max Leaked Case Tips Design Changes to Mute Button: All Details',
      date: ' 26 June 2023',
      catname: 'Mobiles',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/mobiles/news/iphone-15-pro-max-case-design-mute-button-camera-apple-leak-4153251'
    },
    {
      no: 9,
      title: 'Vivo X90S With MediaTek Dimensity 9200+ SoC, 120W Wired Fast Charging Launched: Price, Specifications',
      date: ' 26 June 2023',
      catname: 'Mobiles',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/mobiles/news/vivo-x90s-price-cny-3999-4299-4699-launch-specifications-features-4153218'
    },
    {
      no: 10,
      title: 'Apple Vision Pro $3,499 Price Might Not Include Overhead Strap For Headset: Mark Gurman',
      date: ' 26 June 2023',
      catname: 'Wearables',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/wearables/news/apple-vision-pro-price-usd-3499-overhead-strap-headset-extra-cost-mark-gurman-4152914'
    },
    {
      no: 11,
      title: '‘Not a Given That AI Will Only Have a Positive Impact’: After AI Boom, Investors Wary of Possible Risks',
      date: ' 26 June 2023',
      catname: 'Internet',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/internet/news/generative-ai-boom-investors-wary-of-possible-risks-markets-boost-4153217'
    },
    {
      no: 12,
      title: 'OnePlus Ace 2 Pro Specifications Leak Again, Tipped to Use Snapdragon 8+ Gen 2 SoC',
      date: ' 26 June 2023',
      catname: 'Mobiles',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/mobiles/news/oneplus-ace-2-pro-specifications-features-snapdragon-8-plus-gen-2-soc-expected-leak-4152946'
    },
    {
      no: 13,
      title: 'Tech Giants Could Face Fines Worth Up to 5 Percent of Annual Turnover Under Proposed Australian Laws',
      date: ' 26 June 2023',
      catname: 'Internet',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/internet/news/facebook-google-twitter-tiktok-tech-giants-billions-of-dollars-fine-tackling-disinformation-australian-laws-watchdog-4153047'
    },
    {
      no: 14,
      title: 'iQoo 11S, iQoo TWS 1 Earbuds Launch Set for July 6, Teased to Run on Snapdragon 8 Gen 2',
      date: ' 26 June 2023',
      catname: 'Mobiles',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/mobiles/news/iqoo-11s-tws-1-earbuds-launch-date-july-4-specifications-teaser-pre-order-ram-storage-specifications-4152915'
    },
    {
      no: 15,
      title: 'Automakers Plan a Second Life for Old EV Batteries, but That Depends How Long the First Is',
      date: ' 26 June 2023',
      catname: 'Auto',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/auto/news/ev-battery-second-life-re-use-global-automakers-energy-storage-4152893'
    },
    {
      no: 16,
      title: 'OnePlus 12 Tipped to Launch in December; Leaked Specifications Hint at Snapdragon 8 Gen 3 SoC: Details',
      date: ' 26 June 2023',
      catname: 'Mobiles',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/mobiles/news/oneplus-12-specifications-launch-timeline-leak-camera-4152865'
    },
    {
      no: 17,
      title: 'OnePlus Nord CE 3 Live Images Leak Online, Hint at Imminent Launch: Details',
      date: ' 26 June 2023',
      catname: 'Mobiles',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/mobiles/news/oneplus-nord-ce-3-design-live-images-leak-specifications-features-expected-4152614'
    },
    {
      no: 18,
      title: 'Crypto Market Watch: Bitcoin, Ether Carry Recovered Prices Into June End Amid Market Volatility',
      date: ' 26 June 2023',
      catname: 'Cryptocurrency',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/cryptocurrency/news/bitcoin-ether-cryptocurrency-price-today-june-26-volatile-crypto-market-watch-4152824'
    },
    {
      no: 19,
      title: 'Oppo A78 4G Design Renders, Key Specifications Tipped, Said to Launch Soon',
      date: ' 26 June 2023',
      catname: 'Mobiles',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/mobiles/news/oppo-a78-4g-design-renders-expected-launch-leak-specifications-report-4152591'
    },
    {
      no: 20,
      title: 'Apple Watch Ultra Refresh, 30-Inch iMac, iPad Air, More in Pipeline: Mark Gurman',
      date: ' 26 June 2023',
      catname: 'Wearables',
      img: 'https://www.gadgets360.com/static/icons/img_120n.png',
      link: 'https://www.gadgets360.com/wearables/news/apple-watch-series-9-ultra-launch-september-iphone-15-mac-ipad-imac-roadmap-mark-gurman-power-on-report-4152666'
    }
  ]
}
```
