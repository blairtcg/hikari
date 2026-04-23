---
title: Blair | Anime TCG Discord Bot
description: Collect, trade, and battle with your favorite anime characters right in your Discord server.
layout: blocks

content_blocks:
  # 1. THE HERO SECTION
  # The first thing users see. Grabs attention with an invite link and a cool image.
  - _bookshop_name: hero
    heading:
      title: Meet Blair
      subtitle: The Ultimate Anime TCG Experience
      content: |-
        Bring your Discord community to life! Collect exclusive anime character cards, trade with friends, build your dream deck, and battle to climb the global leaderboards.
      width: 6
    background:
      color: primary
      subtle: true
    illustration:
      image: /img/blair-banner.jpg # Replace with your bot's actual banner or avatar
      ratio: 16x9
    width: 8
    links:
      - title: Invite to Server
        url: https://discord.com/oauth2/authorize?client_id=YOUR_CLIENT_ID&permissions=YOUR_PERMS&scope=bot
        icon: fab discord
      - title: Read the Docs
        url: /docs/getting-started
        icon: fas book-open
        outline: true
    orientation: horizontal
    justify: center

  # 2. THE FEATURES SECTION
  # Highlights the core mechanics of your TCG (Collecting, Trading, Battling)
  - _bookshop_name: features
    heading:
      title: Why add Blair to your server?
      content: Everything you need for an engaging, competitive, and fun gacha/card game experience.
    background:
      color: light
      subtle: true
    items:
      - title: Collect & Claim
        description: Drop cards randomly in chat or use daily commands to claim your favorite waifus and husbandos.
        icon: fas star
      - title: Global Trading
        description: Swap duplicates with players across different servers using our secure global trade network.
        icon: fas right-left
      - title: Turn-Based Battles
        description: Build your ultimate deck and challenge other users to tactical TCG battles directly in Discord.
        icon: fas crosshairs
      - title: Custom Profiles
        description: Showcase your absolute rarest cards and flex your win-rate stats with customizable player profiles.
        icon: fas id-card
    columns: 2

  # 3. BOTTOM CALL TO ACTION
  # A final push to get them into your support server or reading the docs
  - _bookshop_name: hero
    heading:
      title: Ready to start your collection?
      content: |-
        Join thousands of other players in the Blair TCG universe today. Need help? Drop by our support server!
      width: 8
    background:
      color: secondary
      subtle: true
    links:
      - title: Join Support Server
        url: https://discord.gg/your-invite-link
        icon: fas headset
    orientation: vertical
    justify: center
---
