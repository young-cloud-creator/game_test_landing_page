---
title: '主页'
date: 2025-06-03
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: 非侵入式自动化移动游戏测试框架
      text: '[自动化](#features) · [非侵入](#features) · [智能决策](#features)'
      primary_action:
        text: 查看演示
        url: "examples/"
        # icon: rocket-launch
      # secondary_action:
      #   text: Read the docs
      #   url: https://docs.hugoblox.com
      # announcement:
      #   text: "Announcing the release of version 1."
      #   link:
      #     text: "Read more"
      #     url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg.png
          filters:
            brightness: 0.5
  # - block: stats
  #   content:
  #     items:
  #       - statistic: "1M+"
  #         description: |
  #           Websites built  
  #           with Hugo Blox
  #       - statistic: "10k+"
  #         description: |
  #           GitHub stars  
  #           since 2016
  #       - statistic: "3k+"
  #         description: |
  #           Discord community  
  #           for support
  #   design:
  #     # Section background color (CSS class)
  #     css_class: "bg-gray-100 dark:bg-gray-900"
  #     # Reduce spacing
  #     spacing:
  #       padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: 特性
      text: 不依赖游戏内部API的自动化测试方案
      items:
        - name: 自动化
          icon: "custom/robot"
          description: 无需人工录制游戏操作
        - name: 非侵入
          icon: "custom/game_controller"
          description: 通过模拟玩家操控实现测试，不依赖游戏API
        - name: 智能决策
          icon: "custom/smart"
          description: 基于视觉的智能决策模块，根据游戏画面实时做出操作
        # - name: No-Code
        #   icon: code-bracket
        #   description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
        # - name: Highly Rated
        #   icon: star
        #   description: Rated 5-stars by the community.
        # - name: Swappable Blocks
        #   icon: rectangle-group
        #   description: Build your pages with blocks - no coding required!
  - block: cta-image-paragraph
    id: contact
    content:
      items:
        - title: 与我们取得联系
          # text: As easy as 1, 2, 3!
          feature_icon: check
          features:
            - "获取支持"
            - "询问疑惑"
          # Upload image to `assets/media/` and reference the filename here
          image: contact.png
          button:
            text: 联系我们
            url: https://www.nju.edu.cn/
        # - title: Large Community
        #   text: Join our large community on Discord - ask questions and get live responses
        #   feature_icon: bolt
        #   features:
        #     - "Dedicated support channel"
        #     - "3,000+ users on Discord"
        #     - "Share your site and get feedback"
        #   # Upload image to `assets/media/` and reference the filename here
        #   image: coffee.jpg
        #   button:
        #     text: Join Discord
        #     url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  # - block: testimonials
  #   content:
  #     title: ""
  #     text: ""
  #     items:
  #       - name: "Hugo Smith"
  #         role: "Marketing Executive at X"
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: "testimonial-1.jpg"
  #         text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
  #   design:
  #     spacing:
  #       # Reduce bottom spacing so the testimonial appears vertically centered between sections
  #       padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: 了解项目功能与原理
      text: "自动化游戏测试框架的运行原理与特点"
      button:
        text: 查看介绍文档
        url: "doc/"
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
