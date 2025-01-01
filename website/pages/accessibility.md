---
layout: "ssg-theme-astro/layouts/main.astro" # This line of code should remain unchanged.

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
address: 1312 Saratoga Ave, San Jose, CA 95129

banner:
  text:
    # - boldText: "🥳 Special Offer"
    - boldText: "20% off cash discount"
    - text: " on frozen handmade dumplings."
    - boldText: "10% off cash discount"
    - text: " on family meal takeout."
    - boldText: "Family Set:"
    - text: " Any 3 dishes for $40, includes free rice."
    - boldText: "Free rice"
    - text: " with lunch."
    - boldText: "Delivery and takeout "
    - text: "available."

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
    - { text: "Home", link: "/" }
    - { text: "Gallery", link: "/#gallery" }
    - { text: "About Us", link: "/#about-us" }
    - { text: "Contact Us", link: "/#contact-us" }
    - { text: "中文", link: "/zh-cn" }
  addOrderOnlineBtn: false
  orderOnlineBtnInsteadText: ""
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  addTelBtn: true
  telTextColor: "#000000"
  addOtherBtn: true
  otherBtnInsteadText: "See MENU & Order"
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
    isTextAlignCenter: true
    bgColor: "#000000"
    bgOpacity: "0.2" # 0~1
    title:
      - "Sweet Home Kitchen"
      - "家之味"
    titleColor: "#ffffff"
    description:
      - "A Chinese restaurant offers Jiangsu and Zhejiang dishes dedicated to restoring the original taste of food."
    descriptionColor: "#ffffff"

    addOrderOnlineBtn: false
    orderOnlineBtnInsteadText: ""
    addTableReservationBtn: false
    tableReservationBtnInsteadText: ""
    showOtherBtn: true
    btn1Text: "See MENU & Order" # default: order online
    btn1Href: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=456b427f-d650-4555-808c-c65bb2e17da3" # default: order online
    btn2Text: "" # default: table reservation
    btn2Href: "" # default: table reservation

    bannerImg: "sweet_home_kitchen.webp"
    imgAlt: "Sweet Home Kitchen 家之味 - Best Food Today"
    imgPosition: "imgLeft" # imgLeft | imgRight
    bannerMarginTopMobile: 32
    imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

    bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
    # bottomInfo: "We offer Takeout"

  # Video
  - type: "video"
    id: ""
    title:
      - "Discover Culinary Comfort"
    description:
      - "Dive into a diverse array of dishes at Sweet Home Kitchen, where Jiangsu and Zhejiang  cuisine meets classic Chinese flavors."
    videoType: "gjw" # vimeo | gjw | youtube
    videoId:
      - "1g5723hgukt5FVmEKhN2CDfAg16k1c"
      - "1gtkmtam2me6f0kfsaJV9gcfE12s1c"
    isOnlyDisplayOnMobile: false

  # Gallery
  - type: "accessibility"

footer:
  mode: 1 # 1
  noMarginTop: true
  bgImg: "Sweet Home Kitchen 家之味.webp"
  bgImgAlt: ""
  bgColor: "#000"
  bgOpacity: "0.7" # 0~1
  textColor: "#fff" # default white
  openingHoursInsteadText: ""
  openingHours:
    - "Monday"
    - "11:00 AM - 2:30 PM, 5:00 PM - 7:30 PM"
    - "Tuesday - Sunday"
    - "11:00 AM - 2:30 PM, 5:00 PM - 8:30 PM"

  isLogo: false
  logoSize: 60

  menu:
    - { text: "Home", link: "/" }
    - { text: "Gallery", link: "/#gallery" }
    - { text: "About Us", link: "/#about-us" }
    - { text: "Contact Us", link: "/#contact-us" }
    - { text: "中文", link: "/zh-cn" }

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

  paymentMethod: "applePay,visa,amex,alipay,mastercard" # alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal
  addressInsteadText: ""
  address:
    - address: "1312 Saratoga Ave, San Jose, CA 95129"
      url: "https://maps.app.goo.gl/Kqk8pwJxqrkELa2a9"
---

<!-- hello world -->
