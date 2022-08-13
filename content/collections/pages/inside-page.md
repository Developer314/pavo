---
id: 1a20d580-df65-4164-9e40-9a659fd9298b
blueprint: pages
title: 'Inside Page'
author: cfa2488c-46e7-4087-aafa-6e0ca34a8371
template: home
seo_title: 'Inside Page'
meta_description: 'Inside Page'
meta_keywords: 'Inside Page'
og_site_name: 'Inside Page'
block_type:
  -
    hero_title: 'Hero Title'
    hero_text: "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum."
    hero_image: details-1.jpg
    hero_buttons:
      -
        button_color: primary
        button_icon: fa-apple
        button_link: 'http://www.google.com'
        button_label: 'Get me'
        link_target: _blank
      -
        button_color: secondary
        button_icon: fa-google-play
        button_link: 'entry::43300a37-b4bc-4025-98e4-722b3b1e94a1'
        button_label: 'Show Me'
        link_target: _blank
    edit_template: true
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
  -
    highlight_title: 'Highlight Box'
    highlight_data: "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum."
    image: conclusion-smartphone.png
    edit_template: true
    template: |-
      <!-- Details 1 -->
              <div id="details" class="pt-12 pb-16 lg:pt-16">
                  <div class="container px-4 sm:px-8 lg:grid lg:grid-cols-12 lg:gap-x-12">
                      <div class="lg:col-span-5">
                          <div class="mb-16 lg:mb-0 xl:mt-16">
                              <h2 class="mb-6">{{highlight_title}}</h2>
                              {{highlight_data}}
                          </div>
                      </div> <!-- end of col -->
                      <div class="lg:col-span-7">
                          <div class="xl:ml-14">
                              <img class="inline" src="{{image}}" alt="alternative" />
                          </div>
                      </div> <!-- end of col -->
                  </div> <!-- end of container -->
              </div>
              <!-- end of details 1 -->
    type: highlight_block
    enabled: true
  -
    image: article-details-large.jpg
    edit_template: true
    template: |-
      <!-- Basic -->
              <div class="ex-basic-1 py-12">
                  <div class="container px-4 sm:px-8">
                      <img class="inline mt-12 mb-4" src="{{image}}" alt="alternative" />
                  </div> <!-- end of container -->
              </div> <!-- end of ex-basic-1 -->
              <!-- end of basic -->
    type: image_block
    enabled: true
updated_by: cfa2488c-46e7-4087-aafa-6e0ca34a8371
updated_at: 1660366322
published: true
---
