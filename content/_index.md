---
title: Blair | Anime TCG
description: Collect, trade, and battle with your favorite anime characters.
layout: blocks

content_blocks:
  # 1. HERO (Works)
  - _bookshop_name: hero
    heading:
      title: Welcome to Blair
      content: |-
        The ultimate Anime TCG experience for Discord.
    background:
      color: primary
      subtle: true
    illustration:
      image: /img/sunrise.jpg # Use existing Hinode image to pass build
      ratio: 16x9
    links:
      - title: Invite
        url: "#"
        icon: fab discord
    orientation: horizontal
    justify: center

  # 2. SEPARATOR (Fixed: Flattened arguments)
  - _bookshop_name: separator
    style: wave
    color: primary
    subtle: true

  # 3. PANELS (Fixed: Using 'items' and removed 'background' wrapper)
  - _bookshop_name: panels
    heading:
      title: Features
    items:
      - title: Collect
        description: Claim cards daily.
        icon: fas star
      - title: Trade
        description: Global trading system.
        icon: fas right-left

  # 4. CARDS (Fixed: Removed 'columns' which was unsupported)
  - _bookshop_name: cards
    heading:
      title: Rarities
    items:
      - title: Common
        description: Easy to find.
      - title: Legendary
        description: Extremely rare.

  # 5. APPROACH (Fixed: Using 'items' without extra wrappers)
  - _bookshop_name: approach
    heading:
      title: Getting Started
    items:
      - title: Step 1
        description: Invite the bot.
      - title: Step 2
        description: Start rolling.

  # 6. FAQ (Fixed: Using 'items')
  - _bookshop_name: faq
    heading:
      title: FAQ
    items:
      - title: Is it free?
        content: Yes, absolutely.

  # 7. TESTIMONIALS (Fixed: Using 'items')
  - _bookshop_name: testimonials
    heading:
      title: Reviews
    items:
      - text: "Best bot ever!"
        author: "UserA"

  # 8. CTA (Final Footer)
  - _bookshop_name: cta
    heading:
      title: Join us
    links:
      - title: Add to Discord
        url: "#"
---
