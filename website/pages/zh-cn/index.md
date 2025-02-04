---
layout: "ssg-theme-astro/layouts/main.astro" #Don't touch this line of code.
tag: "GTM-NHXRZ6W"
title: "Sweet Home Kitchen 家之味 - Best Food Today"
favicon: "favicon.ico"
logo: "logo.webp"
primaryColor: "#E7383D" # logo color
secondaryColor: "#ffffff"
primaryColorScheme: "dark" # dark | light
secondaryColorScheme: "light"
dataGlfCuid: ""
dataGlfRuid: ""
orderOnlineLink: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=456b427f-d650-4555-808c-c65bb2e17da3"
tableReservationLink: ""
tel: "408-689-7799"

banner:
  text:
    # - boldText: "🥳 Special Offer"
    - boldText: "冷凍手作水餃現金８折優惠。家庭套餐外賣現金９折優惠，午餐米飯免費。家庭套餐選擇3道菜$40，米飯免費。提供自取和送餐服務。"
  # add more text...
  textColor: "#ffffff"
  bgColor: "#E7383D"
  bgOpacity: "1" # 0~1

# header
header:
  logoSize: 45
  textAfterLogo:
    text: ""
    size: 16
    color: ""
  bgColor: "#ffffff"
  bgOpacity: "1" # 0~1
  menuTextColor: "#000000"
  menu:
    - { text: "首頁", link: "/zh-cn" }
    - { text: "菜品展示", link: "/zh-cn#gallery" }
    - { text: "關於我們", link: "/zh-cn#about-us" }
    - { text: "聯繫我們", link: "/zh-cn#contact-us" }
    - { text: "English", link: "/" }
  addOrderOnlineBtn: false
  orderOnlineBtnInsteadText: ""
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  addTelBtn: true
  telTextColor: "#000000"
  addOtherBtn: true
  otherBtnInsteadText: "在線訂餐"
  otherBtnHref: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=456b427f-d650-4555-808c-c65bb2e17da3"

sections:
  # hero
  - type: "hero"
    id: ""
    height: "100" # Conditionally use only when sectionType is imgBg
    sectionType: "video" # video | imgWithText | imgBg
    bgVideoType: "gjw" # youtube | vimeo | gjw
    bgVideoId: "1g5723hgukt5FVmEKhN2CDfAg16k1c"
    bgImg: "background_image.webp"
    bgImgAlt: "Sweet Home Kitchen 家之味 - Best Food Today"
    bgColor: "#000000"
    bgOpacity: "0.2" # 0~1
    title:
      - "Sweet Home Kitchen"
      - "家之味"
    titleColor: "#ffffff"
    isTextAlignCenter: true
    description:
      - "淮揚菜彎區一絕，大肚飽餃口齒留香。"
    descriptionColor: "#ffffff"

    addOrderOnlineBtn: false
    orderOnlineBtnInsteadText: ""
    addTableReservationBtn: false
    tableReservationBtnInsteadText: ""
    showOtherBtn: true
    btn1Text: "查看菜單 / 在線訂餐" # default: order online
    btn1Href: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=456b427f-d650-4555-808c-c65bb2e17da3" # default: order online
    btn2Text: "" # default: table reservation
    btn2Href: "" # default: table reservation

    bannerImg: "sweet_home_kitchen.webp"
    imgAlt: "Sweet Home Kitchen 家之味 - Best Food Today"
    imgPosition: "imgLeft" # imgLeft | imgRight
    bannerMarginTopMobile: 32
    imgRounded: "" # sm | md | lg | xl | 2xl | 3xl | full

    bottomRounded: "" # sm | md | lg | xl | 2xl | 3xl | full
    # bottomInfo: "We offer Takeout"

  # Video
  - type: "video"
    id: ""
    title:
      - "味蕾盛宴"
    description:
      - "快來 Sweet Home Kitchen 家之味，享受一次愉悅的美味之旅！"
    videoType: "gjw" # vimeo | gjw | youtube
    videoId:
      - "1g5723hgukt5FVmEKhN2CDfAg16k1c"
      - "1gtkmtam2me6f0kfsaJV9gcfE12s1c"
    isOnlyDisplayOnMobile: false

  # Gallery
  - type: "gallery"
    id: "gallery"
    mode: 4 # 1 - 4
    bgImg: ""
    bgImgAlt: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "美味匯聚"
    titleColor: "#000000"
    description:
      - "從招牌金陵鹽水鴨到溫馨的麵條和餃子，統統等你來品嚐！"
    descriptionColor: "#333333"
    folderPath: "gallery"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "md" # sm | md | lg | xl | 2xl | 3xl | full

  # # textBlock
  #   - type: "textBlock"
  #     id: "about-us"
  #     bgImg: ""
  #     bgImgAlt: ""
  #     bgColor: "#000"
  #     bgOpacity: "" # 0~1
  # title:
  #   - "A Corner of Tradition and Flavor"
  # titleColor: "#000000"
  # description:
  #   - "From the heart of Newark, CA, Crabby Crabby Restaurant is a corner where tradition meets flavor. Every corner of our restaurant is infused with authenticity, from the décor to every bite we serve."
  #   # - text: "We serve Imperial Soup dishes plus other Asian dishes. Feel free to message us about inquiries! We'll get back to you as soon as we can!"
  # descriptionColor: "#000000"

  # textBlock - only title
  - type: "textBlock"
    id: "about-us"
    bgImg: ""
    bgImgAlt: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "關於我們"
    titleColor: "#000000"
    description:
      - "我們是一家專注於江浙菜的中餐廳，致力於還原食物的原始風味。"
      - "我們提供以新鮮食材和用心製作的傳統家常風味美食。"
      - "品嚐傳統美食，品味幸福滋味。"
    descriptionColor: ""

  # # feature - 2
  #   - type: "feature"
  #     id: ""
  #     height: "100" # Conditionally use only when sectionType is imgBg
  #     noMarginTop: true
  #     sectionType: "imgWithText" # video | imgWithText | imgBg
  #     bgVideoType: "" # youtube | vimeo | gjw
  #     bgVideoId: ""
  #     bgImg: ""
  #     bgImgAlt: ""
  #     bgColor: ""
  #     bgOpacity: "" # 0~1
  #     title:
  #       - "Our Mission"
  #     titleColor: "#000000"
  #     description:
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
  #     # descriptionColor: "#000000"
  #     # # title2:
  #     # #   - "A Corner of Tradition and Flavor"
  #     # # title2Color: "#000000"
  #     # # description2:
  #     # #   - "From the heart of Newark, CA, Crabby Crabby Restaurant is a corner where tradition meets flavor. Every corner of our restaurant is infused with authenticity, from the décor to every bite we serve."
  #     # #   # - text: "We serve Imperial Soup dishes plus other Asian dishes. Feel free to message us about inquiries! We'll get back to you as soon as we can!"
  #     # # description2Color: "#000000"
  #     # # title2:
  #     # #   - "Committed to the Community"
  #     # # title2Color: "#000000"
  #     # # description2:
  #     # #   - "We are proud to be an active part of the Newark, CA community. Through special events, collaborations with local venues and participation in community initiatives, Crabby Crabby Restaurant seeks to strengthen the ties that bind us together."
  #     # # description2Color: "#000000"
  #     # isTextAlignCenter: false

  #     # addOrderOnlineBtn: false
  #     # orderOnlineBtnInsteadText: "See MENU & Order"
  #     # addTableReservationBtn: false
  #     # tableReservationBtnInsteadText: ""
  #     # showOtherBtn: false
  #     # btn1Text: "See MENU & Order" # default: order online
  #     # btn1Href: "#" # default: order online
  #     # btn2Text: "" # default: table reservation
  #     # btn2Href: "" # default: table reservation

  #     # bannerImg: "sample.webp"
  #     # imgAlt: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
  #     # imgPosition: "imgLeft" # imgLeft | imgRight

  #     # bottomRounded: "" # sm | md | lg | xl | 2xl | 3xl | full

  # # feature - 3
  #   - type: "feature"
  #     noMarginTop: true
  #     id: ""
  #     height: "100" # Conditionally use only when sectionType is imgBg
  #     sectionType: "imgWithText" # video | imgWithText | imgBg
  #     bgVideoType: "" # youtube | vimeo | gjw
  #     bgVideoId: ""
  #     bgImg: ""
  #     bgImgAlt: ""
  #     bgColor: ""
  #     bgOpacity: "" # 0~1
  #     title:
  #       - "Committed to the Community"
  #     titleColor: "#000000"
  #     description:
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
  #     descriptionColor: "#000000"

  #     addOrderOnlineBtn: false
  #     orderOnlineBtnInsteadText: "See MENU & Order"
  #     addTableReservationBtn: false
  #     tableReservationBtnInsteadText: ""
  #     showOtherBtn: false
  #     btn1Text: "See MENU & Order" # default: order online
  #     btn1Href: "#" # default: order online
  #     btn2Text: "" # default: table reservation
  #     btn2Href: "" # default: table reservation

  #     bannerImg: "sample.webp"
  #     imgAlt: "Lorem ipsum dolor sit amet"
  #     imgPosition: "imgRight" # imgLeft | imgRight

  #     bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

  # # textBlock
  #   - type: "textBlock"
  #     id: "about-us"
  #     bgImg: ""
  #     bgImgAlt: ""
  #     bgColor: ""
  #     bgOpacity: "" # 0~1
  #     title:
  #       - "About Us"
  #     titleColor: "#000000"
  #     description:
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."

  #       # - text: "We serve Imperial Soup dishes plus other Asian dishes. Feel free to message us about inquiries! We'll get back to you as soon as we can!"
  #     descriptionColor: "#000000"
  # # feature - 2
  #   - type: "feature"
  #     id: "contact-us"
  #     noMarginTop: false
  #     height: "100" # Conditionally use only when sectionType is imgBg
  #     sectionType: "imgWithText" # video | imgWithText | imgBg
  #     bgVideoType: "" # youtube | vimeo | gjw
  #     bgVideoId: ""
  #     bgImg: ""
  #     bgImgAlt: ""
  #     bgColor: ""
  #     bgOpacity: "" # 0~1
  #     title:
  #       - "Store 1: Kearny St"
  #     titleColor: "#000000"
  #     description:
  #       - "Lorem ipsum dolor sit amet, consectetur"
  #     descriptionColor: "#000000"
  #     # title2:
  #     #   - "A Corner of Tradition and Flavor"
  #     # title2Color: "#000000"
  #     # description2:
  #     #   - "From the heart of Newark, CA, Crabby Crabby Restaurant is a corner where tradition meets flavor. Every corner of our restaurant is infused with authenticity, from the décor to every bite we serve."
  #     #   # - text: "We serve Imperial Soup dishes plus other Asian dishes. Feel free to message us about inquiries! We'll get back to you as soon as we can!"
  #     # description2Color: "#000000"
  #     # title2:
  #     #   - "Committed to the Community"
  #     # title2Color: "#000000"
  #     # description2:
  #     #   - "We are proud to be an active part of the Newark, CA community. Through special events, collaborations with local venues and participation in community initiatives, Crabby Crabby Restaurant seeks to strengthen the ties that bind us together."
  #     # description2Color: "#000000"
  #     isTextAlignCenter: false

  #     addOrderOnlineBtn: false
  #     orderOnlineBtnInsteadText: "See MENU & Order"
  #     addTableReservationBtn: false
  #     tableReservationBtnInsteadText: ""
  #     showOtherBtn: true
  #     btn1Text: "Order online from Kearny St store"
  #     btn1Href: "#"
  #     btn2Text: ""
  #     btn2Href: ""

  #     bannerImg: ""
  #     imgAlt: ""
  #     imgPosition: "" # imgLeft | imgRight

  #     map: true
  #     url: "https://maps.app.goo.gl/nZ57LDJrofANer8J6"
  #     iframeUrl: "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d394.10234978168285!2d-122.4046165!3d37.7942861!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085808b1948e55b%3A0xcb3994bcd586810e!2sHon&#39;s%20Wun-Tun%20House!5e0!3m2!1sen!2sus!4v1722231832722!5m2!1sen!2sus"
  #     addTelBtn: true
  #     tel: "000000000"
  #     telInsteadText: "Call: (000) 000-0000"
  #     getDirectionBtnInsteadText: ""

  #     bottomRounded: "" # sm | md | lg | xl | 2xl | 3xl | full (only for background)
  # textBlock - Information
  - type: "textBlock"
    id: ""
    # bgImg: "/sweet_home_kitchen2.webp"
    # bgImgAlt: "Sweet Home Kitchen 家之味 - Best Food Today"
    bgColor: "#000"
    bgOpacity: "1" # 0~1
    title:
      - "新功能！在線訂餐"
    titleColor: "#ffffff"
    description:
      - "現在支援線上訂單自取。只要告訴我們您想要的菜餚，我們會​​盡快準備好。所有訂單都由我們手動確認。您可以即時查看您的食物何時準備好。訂單狀態會即時更新，您可以在螢幕上查看您的食物何時可以取走。"
    descriptionColor: "#ffffff"

  # map
  - type: "map"
    noMarginTop: true
    id: "contact-us"
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/Kqk8pwJxqrkELa2a9"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3173.782295865214!2d-121.98282168869802!3d37.30029317199242!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808fcbb7733ebcbf%3A0x30270741189d8d03!2sSweetHome%20Kitchen!5e0!3m2!1sen!2sus!4v1722820862843!5m2!1sen!2sus"
    addTelBtn: true
    getDirectionBtnInsteadText: "導航到餐廳"
    telInsteadText: "電話：408-689-7799"

  # The modal will only appear once within 30 minutes."
  - type: "modal"
    bgColor: "#333"
    bgOpacity: "0.1" # 0~1
    title:
      - "🎁 特價優惠"
    titleColor: "#FF2D2F"
    titleSize: 24
    description:
      - "冷凍手工水餃現金８折優惠。 家庭套餐外賣現金９折優惠，午餐米飯免費。家庭套餐任選3道菜$40，米飯免費。提供自取和送餐服務。"
    descriptionColor: ""
    descriptionSize: 16
    imgName: "special_offer.webp"
    imgAlt: "冷凍手工水餃現金８折優惠。 家庭套餐外賣現金９折優惠，午餐米飯免費。家庭套餐任選3道菜$40，米飯免費。"
    imgHref: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=456b427f-d650-4555-808c-c65bb2e17da3"
    buttonText: ""

footer:
  mode: 1 # 1
  noMarginTop: true
  bgImg: "Sweet Home Kitchen 家之味.webp"
  bgImgAlt: ""
  bgColor: "#000"
  bgOpacity: "0.7" # 0~1
  textColor: "#fff" # default white
  openingHoursInsteadText: "營業時間"
  openingHours:
    - "週一"
    - "11:00 AM - 2:30 PM, 5:00 PM - 7:30 PM"
    - "週二 ～ 週日"
    - "11:00 AM - 2:30 PM, 5:00 PM - 8:30 PM"

  isLogo: false
  logoSize: 60

  # menu:
  #   - { text: "首頁", link: "/zh-cn" }
  #   - { text: "菜品展示", link: "/zh-cn#gallery" }
  #   - { text: "關於我們", link: "/zh-cn#about-us" }
  #   - { text: "聯繫我們", link: "/zh-cn#contact-us" }
  #   - { text: "English", link: "/" }

  FB: false
  FBLink: ""
  IG: false
  IGLink: ""
  X: false
  XLink: ""
  youtube: false
  youtubeLink: ""
  yelp: false
  yelpLink: ""

  acceptedPaymentMethodsInsteadText: "付款方式"
  paymentMethod: "applePay,visa,amex,alipay,mastercard" # alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal
  addressInsteadText: "地址："
  address:
    - address: "1312 Saratoga Ave, San Jose, CA 95129"
      url: "https://maps.app.goo.gl/Kqk8pwJxqrkELa2a9"

  # optional
seo:
  metaDescription: "我們是一家专注于江浙菜，致力于还原食物原汁原味的中餐廳。位於圣何塞市的萨拉托加大道。我们提供外卖和送餐服务，让您随时享受地道的美食！"
  keywords: ""
  img: ""
  thisPageUrl: ""
  locale: "zh_TW" # zh_TW | zh_CN
  canonicalHref: "https://www.sweethomekitchensj.com/zh-cn/"
---

<!-- hello world -->
