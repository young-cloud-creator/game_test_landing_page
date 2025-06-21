---
title: '主页'
date: 2025-06-03
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: hero
    content:
      title: 非侵入式自动化移动游戏测试框架
      text: '[自动化](#features) · [非侵入](#features) · [智能决策](#features)'
      primary_action:
        text: 查看演示
        url: "examples/"
        # icon: rocket-launch
      secondary_action:
        text: 了解原理
        url: "doc/"
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
          description: 基于视觉的智能决策模块，根据游戏画面实时操作
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
            url: "https://seg-models.group/#/"
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
---
