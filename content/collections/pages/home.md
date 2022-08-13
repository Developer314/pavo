---
id: home
blueprint: pages
title: Home
template: home
author: cfa2488c-46e7-4087-aafa-6e0ca34a8371
select_global_block_types:
  -
    select_block_types: '{{home_hero:home_hero_template}}'
  -
    select_block_types: '{{home_intro:intro_text_template}}'
updated_by: cfa2488c-46e7-4087-aafa-6e0ca34a8371
updated_at: 1660366299
block_types: '{{home_intro:home_introduction_template}}'
block_type:
  -
    hero_title: 'Team management mobile application'
    hero_text: "Start getting things done together with your team based on Pavo's revolutionary team management features"
    hero_image: header-smartphone.png
    hero_buttons:
      -
        button_color: primary
        button_icon: fa-apple
        button_link: 'http://www.apple.com'
        button_label: Download
        link_target: _blank
      -
        button_color: secondary
        button_icon: fa-google-play
        button_link: 'http://www.youtube.com'
        button_label: Download
        link_target: _blank
    type: home_hero
    enabled: true
    template: |-
      <header id="header" class="header py-28 text-center md:pt-36 lg:text-left xl:pt-44 xl:pb-32">
                  <div class="container px-4 sm:px-8 lg:grid lg:grid-cols-2 lg:gap-x-8">
                      <div class="mb-16 lg:mt-32 xl:mt-40 xl:mr-12">
                          <h1 class="h1-large mb-5">{{hero_title}}</h1>
                          <p class="p-large mb-8">{{hero_text}}</p>

                        {{hero_buttons}}
                          <a class="btn-solid-lg {{button_color}}" title="{{button_label}}" target="{{link_target}}" href="{{button_link}}"><i class="fab {{button_icon}}"></i>{{button_label}}</a>
                           {{/hero_buttons}}
                         

                      </div>
                      <div class="xl:text-right">
                          <img class="inline" src="{{hero_image}}" alt="alternative" />
                      </div>
                  </div>
              </header>
    edit_template: true
  -
    intro_text: 'Team management mobile apps don’t get better than Pavo. It’s probably the best app in the world for this purpose. Don’t hesitate to give it a try today and you will fall in love with it'
    type: home_intro
    enabled: true
    edit_template: false
  -
    highlight_title: 'Results driven ground breaking technology'
    highlight_data: |-
      <p class="mb-4">Based on our team's extensive experience in developing line of business applications and constructive customer feedback we reached a new level of revenue.</p>
      <p class="mb-4">We enjoy helping small and medium sized tech businesses take a shot at established Fortune 500 companies</p>
    type: highlight_block
    enabled: true
    image: details-1.jpg
    edit_template: false
  -
    features:
      -
        feature_title: 'Platform Integration'
        feature_text: 'You sales force can use the app on any smartphone platform without compatibility issue'
        feature_image: features-icon-1.svg
      -
        feature_title: 'Platform Integration'
        feature_text: 'You sales force can use the app on any smartphone platform without compatibility issues'
        feature_image: features-icon-2.svg
      -
        feature_title: 'Platform Integration'
        feature_text: 'You sales force can use the app on any smartphone platform without compatibility issues'
        feature_image: features-icon-3.svg
      -
        feature_title: 'Platform Integration'
        feature_text: 'You sales force can use the app on any smartphone platform without compatibility issues'
        feature_image: features-icon-4.svg
      -
        feature_title: 'Platform Integration'
        feature_text: 'You sales force can use the app on any smartphone platform without compatibility issues'
        feature_image: features-icon-5.svg
      -
        feature_title: 'Platform Integration'
        feature_text: 'You sales force can use the app on any smartphone platform without compatibility issues'
        feature_image: features-icon-6.svg
    type: features
    enabled: true
    edit_template: false
  -
    title: 'Instant results for the marketing department'
    data: |-
      <ul class="list mb-7 space-y-2">
                                  <li class="flex">
                                      <i class="fas fa-chevron-right"></i>
                                      <div>Features that will help you and your marketers</div>
                                  </li>
                                  <li class="flex">
                                      <i class="fas fa-chevron-right"></i>
                                      <div>Smooth learning curve due to the knowledge base</div>
                                  </li>
                                  <li class="flex">
                                      <i class="fas fa-chevron-right"></i>
                                      <div>Ready out-of-the-box with minor setup settings</div>
                                  </li>
                              </ul>
    image: details-2.jpg
    light_box_button_text: 'Quick view'
    button_2_text: Details
    button_2_link: 'entry::0c22ce92-cbd2-4935-a95d-f7b1035b973a'
    popup_title_1: 'Goals Setting'
    popup_data_1: 'The app can easily help you track your personal development evolution if you take the time to set it up.'
    popup_title_2: 'User Feedback'
    popup_data_2: |-
      <p class="mb-4">This is a great app which can help you save time and make your live easier. And it will help improve your productivity.</p>
      <ul class="list mb-6 space-y-2">
                              <li class="flex">
                                  <i class="fas fa-chevron-right"></i>
                                  <div>Splash screen panel</div>
                              </li>
                              <li class="flex">
                                  <i class="fas fa-chevron-right"></i>
                                  <div>Statistics graph report</div>
                              </li>
                              <li class="flex">
                                  <i class="fas fa-chevron-right"></i>
                                  <div>Events calendar layout</div>
                              </li>
                              <li class="flex">
                                  <i class="fas fa-chevron-right"></i>
                                  <div>Location details screen</div>
                              </li>
                              <li class="flex">
                                  <i class="fas fa-chevron-right"></i>
                                  <div>Onboarding steps interface</div>
                              </li>
                          </ul>
    popup_button_text_1: Download
    popup_button_link_1: 'entry::14a409d0-3fcf-4dc8-9d9c-9a0534a34e25'
    popup_button_1_target: _self
    popup_button_text_2: CLOSE
    popup_image: details-lightbox.jpg
    type: highlight_with_lightbox
    enabled: true
    edit_template: false
  -
    highlight_title: 'Platform integration and life time free updates'
    highlight_data: |-
      <p class="mb-4">Get a glimpse of what this app can do for your marketing automation and understand why current users are so excited when using Pavo
                                  together with their teams.</p>
                                  <p class="mb-4">We will promptly answer any questions and honor your requests based on the service level agreement</p>
    image: details-3.jpg
    type: highlight_block
    enabled: true
    edit_template: false
  -
    numbers:
      -
        name: 'Happy Users'
        digit: '231'
      -
        name: 'Issues Solved'
        digit: '1020'
      -
        name: 'Good Reviews'
        digit: '700'
      -
        name: 'Case Studies'
        digit: '234'
      -
        name: 'Orders Received'
        digit: '345'
    template: |-
      <!-- Statistics -->
              <div class="counter">
                  <div class="container px-4 sm:px-8">
                      
                      <!-- Counter -->
                      <div id="counter">
      	                {{numbers}}
                          <div class="cell">
                              <div class="counter-value number-count" data-count="{{digit}}">1</div>
                              <p class="counter-info">{{name}}</p>
                          </div>
                          {{/numbers}}
                      </div>
                      <!-- end of counter -->

                  </div> <!-- end of container -->
              </div> <!-- end of counter -->
              <!-- end of statistics -->
    type: our_numbers
    enabled: true
    edit_template: false
  -
    testimonial_title: 'What do users think about Pavo'
    testimonials:
      -
        client_name: 'Jude Thorn - Designer'
        client_image: testimonial-2.jpg
        testimonial_data: "It's been so fun to work with Pavo, I've managed to integrate it properly into my business flow and it's great"
      -
        client_name: 'Roy Smith - Developer'
        client_image: testimonial-1.jpg
        testimonial_data: "We were so focused on launching as many campaigns as possible that we've forgotten to target our loyal customers"
      -
        client_name: 'Jude Thorn - Designer'
        client_image: testimonial-6.jpg
        testimonial_data: "I've been searching for a tool like Pavo for so long. I love the reports it generates and the amazing high accuracy"
      -
        client_name: 'Jude Thorn - Designer'
        client_image: testimonial-5.jpg
        testimonial_data: "I've been searching for a tool like Pavo for so long. I love the reports it generates and the amazing high accuracy"
      -
        client_name: 'Jude Thorn - Designer'
        client_image: testimonial-4.jpg
        testimonial_data: "I've been searching for a tool like Pavo for so long. I love the reports it generates and the amazing high accuracy"
      -
        client_name: 'Jude Thorn - Designer'
        client_image: testimonial-3.jpg
        testimonial_data: "I've been searching for a tool like Pavo for so long. I love the reports it generates and the amazing high accuracy"
      -
        client_name: 'Jude Thorn - Designer'
        client_image: testimonial-2.jpg
        testimonial_data: "I've been searching for a tool like Pavo for so long. I love the reports it generates and the amazing high accuracy"
      -
        client_name: 'Jude Thorn - Designer'
        client_image: testimonial-1.jpg
        testimonial_data: "I've been searching for a tool like Pavo for so long. I love the reports it generates and the amazing high accuracy"
    type: testimonials
    enabled: true
    edit_template: false
  -
    pricing_title: 'Pricing options for all budgets'
    pricing_data: 'Our pricing plans are setup in such a way that any user can start enjoying Pavo without worrying so much about costs. They are flexible and work for any type of industry'
    pricing_info:
      -
        title: STANDARD
        price: '200'
        currency: $
        frequency: Monthly
        features: |-
          <p>This basic package covers the marketing needs of small startups</p>
                                  <ul class="list mb-7 space-y-2 text-left">
                                      <li class="flex">
                                          <i class="fas fa-chevron-right"></i>
                                          <div>List building and relations</div>
                                      </li>
                                      <li class="flex">
                                          <i class="fas fa-chevron-right"></i>
                                          <div>Seamless platform integration</div>
                                      </li>
                                      <li class="flex">
                                          <i class="fas fa-chevron-right"></i>
                                          <div>Great performance on devices</div>
                                      </li>
                                      <li class="flex">
                                          <i class="fas fa-chevron-right"></i>
                                          <div>Community support and videos</div>
                                      </li>
                                  </ul>
        button_label: Download
        button_link: 'http://www.revolve314.com'
        target: _blank
      -
        title: ADVANCED
        price: '350'
        currency: $
        frequency: monthly
        features: |-
          <p>This is a more advanced package suited for medium companies</p>
                                  <ul class="list mb-7 space-y-2 text-left">
                                      <li class="flex">
                                          <i class="fas fa-chevron-right"></i>
                                          <div>List building and relations</div>
                                      </li>
                                      <li class="flex">
                                          <i class="fas fa-chevron-right"></i>
                                          <div>Seamless platform integration</div>
                                      </li>
                                      <li class="flex">
                                          <i class="fas fa-chevron-right"></i>
                                          <div>Great performance on devices</div>
                                      </li>
                                      <li class="flex">
                                          <i class="fas fa-chevron-right"></i>
                                          <div>Community support and videos</div>
                                      </li>
                                  </ul>
        button_label: 'Get NOW'
        button_link: 'http://www.google.com'
        target: _blank
      -
        title: COMPLETE
        price: '500'
        currency: $
        frequency: Monthly
        features: |-
          <p>This is a comprehensive package designed for big organizations</p>
                                  <ul class="list mb-7 text-left space-y-2">
                                      <li class="flex">
                                          <i class="fas fa-chevron-right"></i>
                                          <div>List building and relations</div>
                                      </li>
                                      <li class="flex">
                                          <i class="fas fa-chevron-right"></i>
                                          <div>Seamless platform integration</div>
                                      </li>
                                      <li class="flex">
                                          <i class="fas fa-chevron-right"></i>
                                          <div>Great performance on devices</div>
                                      </li>
                                      <li class="flex">
                                          <i class="fas fa-chevron-right"></i>
                                          <div>Community support and videos</div>
                                      </li>
                                  </ul>
        button_label: 'Access NOW'
        button_link: 'http://www.gmail.com'
        target: _blank
    button_label: 'Access Now'
    type: pricing_block
    enabled: true
    edit_template: false
  -
    hero_title: 'Team management mobile applications don’t get much better than Pavo. Download it today'
    hero_image: conclusion-smartphone.png
    hero_buttons:
      -
        button_color: primary
        button_icon: fa-apple
        button_link: 'http://www.apple.com'
        button_label: Download
        link_target: _blank
      -
        button_color: secondary
        button_icon: fa-google-play
        button_link: 'http://www.google.com'
        button_label: Download
        link_target: _blank
    type: home_hero
    enabled: true
    edit_template: false
seo_title: 'PAVO Home'
meta_description: 'Pavo Description'
meta_keywords: 'SEO,Antler,Website'
og_site_name: 'PAVO Home'
og_site: 'http://127.0.0.1:8000/'
og_title: 'PAVO Home'
og_description: 'Pavo Description'
og_image: details-1.jpg
og_url: 'http://127.0.0.1:8000/'
twitter_card: 'Pavo Description'
published: true
---
## Welcome to your new brand Statamic site!

Not sure where to do next? Here are a few ideas, but feel free to explore in your own way, in your own time.

- [Jump into the Control Panel](/cp) and edit this page or begin setting up your own collections and blueprints.
- [Head to the docs](https://statamic.dev) and learn how Statamic works.
- [Watch some Statamic videos](https://youtube.com/statamic) on YouTube.
- [Join our Discord chat](https://statamic.com/discord) and meet thousands of other Statamic developers.
- [Start a discussion](https://github.com/statamic/cms/discussions) and get answers to your questions.
- [Star Statamic on Github](https://github.com/statamic/cms) if you enjoy using it!