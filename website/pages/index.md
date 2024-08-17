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
tel: "408-216-0979"

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
    - { text: "Gallery", link: "#gallery" }
    - { text: "About Us", link: "#about-us" }
    - { text: "Contact Us", link: "#contact-us" }
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
  - type: "gallery"
    id: "gallery"
    mode: 3 # 1 - 3
    bgImg: ""
    bgImgAlt: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "A Flavorful Journey Awaits"
    titleColor: "#000000"
    description: 
      - "Our menu showcases everything from our nanjing salted duck to comforting noodles and dumplings."
    descriptionColor: "#333333"
    folderPath: "gallery3"
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
      - "About Us"
    titleColor: "#000000"
    description: 
      - "A Chinese restaurant offers Jiangsu and Zhejiang dishes dedicated to restoring the original taste of food. We provide traditional home flavor food with fresh ingredients and heart work. "
      - "Taste of traditional food, taste of happiness."
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
    noMarginTop: false
    id: ""
    bgImg: "sweet_home_kitchen2.webp"
    bgImgAlt: "aaa"
    bgColor: "#000"
    bgOpacity: "0.6" # 0~1
    title: 
      - "NEW! Online Ordering"
    titleColor: "#ffffff"
    description: 
      - "Online ordering NOW enabled for pick-up. Just tell us what you want and we'll prepare it as fast as we can. All orders are manually confirmed by us directly. Find out in real-time when your food is ready. All orders are manually confirmed by us in real-time. Watch on-screen when your food is ready for pickup."
    descriptionColor: "#ffffff"
  
# map  
  - type: "map"
    noMarginTop: true
    id: "contact-us"
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/Kqk8pwJxqrkELa2a9"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3173.782295865214!2d-121.98282168869802!3d37.30029317199242!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808fcbb7733ebcbf%3A0x30270741189d8d03!2sSweetHome%20Kitchen!5e0!3m2!1sen!2sus!4v1722820862843!5m2!1sen!2sus"
    addTelBtn: true
    getDirectionBtnInsteadText: ""
    telInsteadText: ""
 
 # The modal will only appear once within 30 minutes."
  - type: "modal" 
    bgColor: "#333"
    bgOpacity: "0.1" # 0~1
    title: 
      - "🎁 Special Offers"
    titleColor: "#FF2D2F"
    titleSize: 24
    description: 
      - "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
    descriptionColor: ""
    descriptionSize: 16
    imgName: "special_offer.webp"
    imgAlt: "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
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
    - { text: "Gallery", link: "#gallery" }
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

seo:
  metaDescription: "A Chinese restaurant located at 1312 Saratoga Ave, San Jose, CA, offers Jiangsu and Zhejiang dishes. We offer takeout and delivery."
  keywords: ""
  img: ""
  thisPageUrl: ""
  locale: "en_US" # zh_TW | zh_CN
  canonicalHref: "https://www.sweethomekitchensj.com/"
  
---
<!-- hello world -->