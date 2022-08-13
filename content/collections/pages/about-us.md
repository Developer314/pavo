---
id: 43300a37-b4bc-4025-98e4-722b3b1e94a1
blueprint: pages
title: 'About Us'
author: cfa2488c-46e7-4087-aafa-6e0ca34a8371
template: home
published: true
seo_title: 'About Us'
meta_description: 'About Us'
meta_keywords: 'About Us'
og_site_name: 'About Us'
block_type:
  -
    hero_title: 'About Us'
    hero_text: "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum."
    hero_image: details-1.jpg
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
    type: home_hero
    enabled: true
updated_by: cfa2488c-46e7-4087-aafa-6e0ca34a8371
updated_at: 1660285621
---
