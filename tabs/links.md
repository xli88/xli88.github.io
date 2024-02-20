---
layout: links
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_links

# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
#title: My title
#button_name: "My button"
# for override side_and_top_nav_buttons in _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# please use the "image_viewer_on" below to enable image viewer for individual pages or posts (_posts/ or [language]/_posts folders).
# image viewer can be enabled or disabled for all posts using the "image_viewer_posts: true" setting in _data/conf/main.yml.
#image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false


# you can always move this content to _data/content/ folder
# just create new file at _data/content/links/[language].yml and move content below.
###########################################################
#                Links Page Data
###########################################################
page_data:
  main:
    header: "Curriculum Vitae"
    info: "Over four years of hands-on experiences on quantitative modeling, and Python/C/C++/R library implementation from work in Citibank and UBS. Solid object-oriented design and quant model development skill. Solid understanding in model/library profiling. Solid understanding in Bond/mortgage pricing, futures/option pricing, interest rates, and fixed income. Hands on experience in developing and implementing quantitative financial models using Python/C/C++/R. Multiple years of research experience in derivative pricing, fixed income, and mathematical operations
"
  #  pdf: "https://github.com/SimoneDeBonis/SimoneDeBonis.github.io/raw/main/assets/pdf/CV_Simone_De_Bonis_eng.pdf"

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "Education"
      type: id_edu
      color: "#2C74B3"
    
    - title: "Work Experience"
      type: id_work
      color: "#5BC0F8"

    - title: "Skills"
      type: id_skill
      color: "#0081C9"

    

  list:
    # Education
    - type: id_edu
      title: "PhD in Economics"
      url: ""
      info: "Iowa State University"
      # School: "Iowa State University"
      date: "2015-2020"

    - type: id_edu
      title: "Master in Mathematical Finance"
      url: ""
      info: "Wuhan University, China"
      School: "Wuhan University, China"
      date: "2012-2015"

    # Work Experience
    - type: id_work
      title: "Barclays, Credit Desk Strategy VP"
      url: ""
      info: "Credit desk quant. Portfolio management and optimization."
      date: "September 2023 - "

    - type: id_work
      title: "UBS, Quant Modelling Manager"
      url: ""
      info: "Developed and implemented data-driven pricing and forecasting models for diverse credit products such as mortgage/MBS, leveraged loans/SBL, and Sweeps in Python, improving profitability and reducing potential losses."
      date: "March 2022 - September 2023"

    - type: id_work
      title: "Citibank, Senior Risk Quant Analyst"
      url: ""
      info: "Developed, implemented, and tested quantitative risk models using a variety of programming languages, such as Python, R
and Matlab, for monitoring credit and market risk exposure. Established robust model validation framework, adopting advanced validations methods to improve accuracy of credit
rating calculations. Analyzed and processed large scale data to derive financial patterns"
      date: "December 2019 - March 2022"

    -
    # Skills
    - type: id_skill
      title: "Languages"
      url: ""
      info: "Strong coding proficiency in Python, R, and SQL, work experienced with C/C++(11), Matlab, GitLab"
      date: ""
    - type: id_skill
      title: "Statistical Techniques"
      url: ""
      info: "Advanced mathematical modeling techniques in machine learning, data mining/cleaning, derivatives pricing. Abundant experience in quantitative analysis and model development and outstanding programmer"
      date: ""
    - type: id_skill
      title: "Financial Markets"
      url: ""
      info: "Creative professional and collaborator with 4+ years' experience in credit derivatives pricing & risk management. Expertized in derivatives pricing using statistical techniques including PDEs, Monte Carlo, and PCA."
      date: ""
---
---
