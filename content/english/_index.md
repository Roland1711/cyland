---

########################### hero slider ############################
hero_slider:
  enable : true
  slider_item:
    # slider item
    - subtitle : "We are here to"
      title : "HELP START YOUR UK JOURNEY WITH CYLAND"
      content : "We’re hiring registered nurses and healthcare assistants from around the globe!"
      bg_image_webp : "images/slider/banner-1.webp"
      bg_image : "images/slider/banner-1.jpg"
      animation : "fadeInUp" # animation select from : https://daneden.github.io/animate.css/
      button:
        enable : true
        label : "more details"
        link : "about"
        animation : "zoomIn" # animation select from : https://daneden.github.io/animate.css/
        
    # slider item
    - subtitle : "We are here to"
      title : "CHANGE YOUR LIFE BETTER!"
      content : "We're here to genuinely help you pursue your career as a healthcare professional in the United Kingdom. That’s what we love to do."
      bg_image_webp : "images/slider/banner-2.webp"
      bg_image : "images/slider/banner-2.jpg"
      animation : "fadeInDown" # animation select from : https://daneden.github.io/animate.css/
      button:
        enable : true
        label : "more details"
        link : "about"
        animation : "zoomIn" # animation select from : https://daneden.github.io/animate.css/

################################## banner feature ############################
banner_feature:
  enable : true
  # Max use 4 item
  feature_item:
    # banner feature item loop
    - name : "FAST RECRUITMENT"
      icon : "far fa-gem" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Massive contacts with employers around the UK."
      
    # banner feature item loop
    - name : "IMMIGRATION"
      icon : "far fa-chart-bar" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Provides sponsorship to successful candidates."
      
    # banner feature item loop
    - name : "IELTS OR OET"
      icon : "far fa-lightbulb" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Helping you achieve the score you need."
      
    # banner feature item loop
    - name : "OSCE & CBT"
      icon : "fas fa-tachometer-alt" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Trains you to obtain the certificates you need."


################################## about ####################################
about:
  enable : true
  subtitle : "About Us"
  title : "HELPING YOU EVERYTHING YOU NEED"
  content : "Whether you are an employer looking for registered nurses from around the globe or a healthcare professional seeking to start a career in the United Kingdom, we are here for you!"
  bg_image : "images/backgrounds/about-us-bg.png"
  bg_image_webp : "images/backgrounds/about-us-bg.webp"
  image_webp : "images/about/about-us.webp"
  image : "images/about/about-us.png"
  button:
    enable : true;
    label : "more service"
    link : "service"

################################## funfacts ###############################
funfacts :
  enable : true
  funfacts_item :
    # fanfacts item loop
    - name : "project done"
      count : "50"
      icon : "fas fa-bullseye" # font-awesome 5 : https://fontawesome.com/icons/
      
    # fanfacts item loop
    - name : "Years Experience"
      count : "25"
      icon : "far fa-calendar-alt" # font-awesome 5 : https://fontawesome.com/icons/
      
    # fanfacts item loop
    - name : "Awards Win"
      count : "250"
      icon : "fas fa-award" # font-awesome 5 : https://fontawesome.com/icons/
      
    # fanfacts item loop
    - name : "Happy Coustomers"
      count : "500"
      icon : "far fa-smile" # font-awesome 5 : https://fontawesome.com/icons/


################################# feature ############################################
feature:
  enable : true
  subtitle : "Why Choose Us"
  title : "WHY THEY CHOOSE CYLAND"
  image_webp : "images/feature/feature.webp"
  image : "images/feature/feature.jpg"
  content : "For 8+ years, we have successfully recruit and place foreign healthcare professionals to hospitals and nursing homes throughout the UK."
  feature_item:
    # feature item loop
    - name : "Ethical Recruitment"
      icon : "far fa-snowflake" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Dedicated and adhere to the highest standard of ethical recruitment."
      
    # feature item loop
    - name : "Career Opportunities"
      icon : "fas fa-code" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Has a direct contact with hundreds of potential employers in the UK."

      # feature item loop
    - name : "Benefits"
      icon : "far fa-snowflake" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Access to a wide range of benefits including British citizenship and health benefits in the UK."
      
    # feature item loop
    - name : "Transitions Programme"
      icon : "fas fa-code" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Clinical and cultural transitions into your new life and career in the UK."

################################# service ############################################
service:
  enable : true
  section: "service"
  show_item : 3
  # service item comes from "content/*/service" folder

################################# team ##############################################
team:
  enable : true
  section: "team"
  show_item : 3
  # team member comes from "content/*/team" folder

################################# project ############################################
project:
  enable : true
  section: "project"
  show_item : 4
  button:
    enable : true
    label : "more projects"
    link : "project"
  # project item comes from "content/*/project" folder

################################# testimonial #########################################
testimonial:
  enable : true
  subtitle : "Testimonials"
  title : "What Clients Are Say?"
  testimonial_item:
    # testimonial item loop
    - client_image : "images/testimonial/client-1.jpg"
      name : "Dominic Allen"
      designation : "Designer"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit sed eiusmod tempor incididunt ut labore dolore magna aliqua.enim ad minim veniam.quis nostrud exercitation ullamco laboris nis aliquip ex ea commodo consequat. duis aute irure dolor in reprehen."
      
    # testimonial item loop
    - client_image : "images/testimonial/client-2.jpg"
      name : "Alex Pitt"
      designation : "Designer"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit sed eiusmod tempor incididunt ut labore dolore magna aliqua.enim ad minim veniam.quis nostrud exercitation ullamco laboris nis aliquip ex ea commodo consequat. duis aute irure dolor in reprehen."

    # testimonial item loop
    - client_image : "images/testimonial/client-3.jpg"
      name : "John Doe"
      designation : "Designer"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit sed eiusmod tempor incididunt ut labore dolore magna aliqua.enim ad minim veniam.quis nostrud exercitation ullamco laboris nis aliquip ex ea commodo consequat. duis aute irure dolor in reprehen."


################################# blog ################################################
cta:
  enable : true
  title : "Bexar give the smart solution for your business"
  bg_image_webp : "images/backgrounds/cta-lg.webp"
  bg_image : "images/backgrounds/cta-lg.jpg"
  button:
    enable : true
    label : "get a quote"
    link : "contact"

################################# blog ################################################
blog:
  enable : true
  section : "blog"
  show_item : 3
  # blog post comes from "content/*/blog" folder

---