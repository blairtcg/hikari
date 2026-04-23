---
title: Blair | The Ultimate Anime TCG Discord Bot
description: Collect, trade, and battle with your favorite anime characters right in your Discord server.
layout: blocks # Critical: Tells Hinode to process the content_blocks array

content_blocks:
  # 1. HERO BLOCK: The grand introduction at the top of the page
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
    illustration:
      image: /img/blair-hero.webp # Replace with a cool screenshot or bot avatar
      ratio: 16x9
    width: 8
    links:
      - title: Invite to Server
        url: https://discord.com/oauth2/authorize?client_id=YOUR_CLIENT_ID
        icon: fab discord
      - title: View Commands
        url: /docs/commands
        icon: fas terminal
        outline: true
    orientation: horizontal
    justify: center

  # 2. SEPARATOR BLOCK: Adds a cool visual transition between sections
  - _bookshop_name: separator
    style: wave
    color: primary
    subtle: true

  # 3. PANELS BLOCK: Great for highlighting core bot mechanics (Features)
  - _bookshop_name: panels
    heading:
      title: Master the Game
      content: Everything you need for an engaging, competitive, and fun gacha/card game experience.
    background:
      color: light
      subtle: false
    panels:
      - title: Collect & Claim
        description: Drop cards randomly in chat or use daily commands to claim your favorite waifus and husbandos.
        icon: fas star
        color: warning
      - title: Global Trading
        description: Swap duplicates with players across different servers using our secure global trade network.
        icon: fas right-left
        color: success
      - title: Turn-Based Battles
        description: Build your ultimate deck and challenge other users to tactical TCG battles directly in Discord.
        icon: fas crosshairs
        color: danger

  # 4. CARDS BLOCK: Perfect for a TCG! Show off card tiers or rarities
  - _bookshop_name: cards
    heading:
      title: Stunning Card Rarities
      content: Discover beautiful artwork and varying rarities of the cards you can collect.
    background:
      color: white
    cards:
      - title: Common (1★)
        description: The backbone of your collection. Easy to find, great for early battles.
        image: /img/rarity-common.jpg # Add a sample common card image
      - title: Epic (3★)
        description: Rare and powerful. Featuring holographic effects in their generated image.
        image: /img/rarity-epic.jpg # Add a sample epic card image
      - title: Legendary (5★)
        description: The rarest pulls. Devastating in battle and highly coveted in the global market.
        image: /img/rarity-legendary.jpg # Add a sample legendary card image
    columns: 3

  # 5. APPROACH BLOCK: A step-by-step guide on how to get started
  - _bookshop_name: approach
    heading:
      title: How to Play
    background:
      color: light
      subtle: true
    items:
      - title: Invite Blair
        description: Add the bot to your server and set up a dedicated drop channel.
        icon: fas plus
      - title: Roll & Collect
        description: Use `/roll` to spend your daily tokens and open card packs.
        icon: fas dice
      - title: Battle & Climb
        description: Face off against others and climb the global ELO leaderboard.
        icon: fas trophy

  # 6. FAQ BLOCK: Built-in accordion for frequently asked questions
  - _bookshop_name: faq
    heading:
      title: Frequently Asked Questions
    background:
      color: white
    items:
      - title: Is Blair completely free to play?
        content: Yes! You earn tokens naturally by chatting and logging in daily. There are no paywalls blocking card collection.
      - title: Can I trade cards with people in other servers?
        content: Absolutely. Our `/trade` command operates on a global database, allowing cross-server trading.
      - title: What Discord permissions does the bot need?
        content: Blair just needs basic permissions to read messages, send messages, embed links, and attach files (for rendering the cards).

  # 7. TESTIMONIALS BLOCK: Social proof to convince admins to invite the bot
  - _bookshop_name: testimonials
    heading:
      title: What Server Owners Say
    background:
      color: primary
      subtle: true
    items:
      - text: "Blair completely revived our server's general chat. People are talking constantly just to trigger random card drops!"
        author: "@AnimeFan99"
        title: Server Admin
        avatar: /img/avatar1.jpg # Optional user avatar
      - text: "The battle system is surprisingly deep for a Discord bot. Building decks around elemental combos is super fun."
        author: "@TCG_Master"
        title: Top 10 Global Player
        avatar: /img/avatar2.jpg

  # 8. CTA (Call to Action) BLOCK: Final push at the bottom of the page
  - _bookshop_name: cta
    heading:
      title: Ready to start your collection?
      content: Join thousands of other players in the Blair TCG universe today. 
    background:
      color: dark
    links:
      - title: Add to Discord
        url: https://discord.com/oauth2/authorize?client_id=YOUR_CLIENT_ID
        icon: fab discord
        button: primary
      - title: Join Support Server
        url: https://discord.gg/your-invite-link
        icon: fas headset
        button: secondary
---
