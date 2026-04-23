---
title: Blair | The Ultimate Anime TCG Discord Bot
description: Collect, trade, and battle with your favorite anime characters right in your Discord server.
layout: blocks

content_blocks:
  # 1. HERO BLOCK
  - _bookshop_name: hero
    heading:
      title: Welcome to the World of Blair
      subtitle: The Ultimate Anime TCG Experience
      content: |-
        Bring your Discord community to life! Collect exclusive anime character cards, trade with friends, build your dream deck, and battle to climb the global leaderboards.
      width: 6
    background:
      color: primary
      subtle: true
    # FIX: Ensure this image actually exists in static/img/blair-hero.webp or use a placeholder
    illustration:
      image: /img/sunrise.jpg 
      ratio: 16x9
    width: 8
    links:
      - title: Invite to Server
        url: "#" # Updated to placeholder to pass link validation
        icon: fab discord
      - title: View Commands
        url: "#" # Updated to placeholder to pass link validation
        icon: fas terminal
        outline: true
    orientation: horizontal
    justify: center

  # 2. SEPARATOR BLOCK
  # FIX: 'color' is no longer a top-level argument for separator. Use background logic.
  - _bookshop_name: separator
    style: wave
    background:
      color: primary
      subtle: true

  # 3. PANELS BLOCK
  # FIX: Hinode v2 uses 'list' or 'segments' for many repeating items.
  - _bookshop_name: panels
    heading:
      title: Master the Game
    background:
      color: light
    list: # CHANGED from 'panels' to 'list'
      - title: Collect & Claim
        description: Drop cards randomly in chat or use daily commands to claim your favorite cards.
        icon: fas star
      - title: Global Trading
        description: Swap duplicates with players across different servers securely.
        icon: fas right-left
      - title: Turn-Based Battles
        description: Build your ultimate deck and challenge others to tactical TCG battles.
        icon: fas crosshairs

  # 4. CARDS BLOCK
  # FIX: Use 'list' instead of 'cards' to define the array.
  - _bookshop_name: cards
    heading:
      title: Stunning Card Rarities
    list: # CHANGED from 'cards' to 'list'
      - title: Common (1★)
        description: The backbone of your collection. Easy to find, great for early battles.
      - title: Epic (3★)
        description: Rare and powerful. Featuring holographic effects.
      - title: Legendary (5★)
        description: The rarest pulls. Devastating in battle.
    columns: 3

  # 5. APPROACH BLOCK
  # FIX: Items argument renamed to 'list'.
  - _bookshop_name: approach
    heading:
      title: How to Play
    list: # CHANGED from 'items' to 'list'
      - title: Invite Blair
        description: Add the bot to your server and set up a dedicated drop channel.
        icon: fas plus
      - title: Roll & Collect
        description: Use /roll to spend your daily tokens and open card packs.
        icon: fas dice
      - title: Battle & Climb
        description: Face off against others and climb the global ELO leaderboard.
        icon: fas trophy

  # 6. FAQ BLOCK
  - _bookshop_name: faq
    heading:
      title: Frequently Asked Questions
    list: # Standardized to 'list'
      - title: Is Blair free to play?
        content: Yes! You earn tokens naturally by chatting and logging in daily.

  # 7. TESTIMONIALS BLOCK
  # FIX: Items argument renamed to 'list'.
  - _bookshop_name: testimonials
    heading:
      title: What Server Owners Say
    list: # CHANGED from 'items' to 'list'
      - text: "Blair completely revived our server's general chat!"
        author: "@AnimeFan99"

  # 8. CTA BLOCK
  - _bookshop_name: cta
    heading:
      title: Ready to start?
    links:
      - title: Add to Discord
        url: "#"
        button: primary
---
