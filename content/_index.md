---
title: Welcome to Hikari!
description: Official documentation for Blair — your all-in-one Discord bot.

content_blocks:


  # ─── 3. FEATURED ─────────────────────────────────────────────────────────
  - _bookshop_name: featured
    heading:
      preheading: "Join today"
      title: "Add Blair to your server"
      content: >-
        Blair is free to use and always improving. Invite it in one click,
        or join our support server if you run into any issues.
      align: start
    background:
      color: body-tertiary
      subtle: false
    illustration:
      image: /img/sunrise.jpg
      ratio: 4x3
    link_type: button
    links:
      - title: Invite Blair
        url: "https://discord.com/oauth2/authorize?client_id=YOUR_CLIENT_ID&scope=bot+applications.commands&permissions=8"
        icon: fab discord
      - title: Support server
        url: "https://discord.gg/YOUR_INVITE"
        icon: fas headset
        outline: true

  # ─── 8. HEADING ──────────────────────────────────────────────────────────
  - _bookshop_name: heading
    heading:
      preheading: "Documentation"
      title: "Jump to a section"
      content: "All pages include breadcrumbs and a full table of contents."
      align: center
    justify: center

  # ─── 9. CARDS ────────────────────────────────────────────────────────────
  - _bookshop_name: cards
    heading:
      title: "Explore the docs"
      align: center
    background:
      color: body-tertiary
      subtle: false
    orientation: stacked
    icon_rounded: true
    icon_style: text-primary
    padding: 3
    elements:
      - title: Getting started
        icon: fas rocket
        content: >-
          Invite Blair, grant the right permissions, and run your first
          commands in under five minutes.
        url: "https://blairtcg.github.io/hikari/docs/getting-started/"
      - title: Commands reference
        icon: fas terminal
        content: >-
          Full alphabetical list of every slash command, its arguments,
          required permissions, and example usage.
        url: "https://blairtcg.github.io/hikari/docs/commands/"
      - title: Configuration
        icon: fas sliders
        content: >-
          Customize Blair's prefix, logging channels, module toggles,
          and guild-specific behaviour.
        url: "https://blairtcg.github.io/hikari/docs/configuration/"
      - title: Moderation guide
        icon: fas shield-halved
        content: >-
          Set up auto-mod filters, warning thresholds, ban lists,
          and logging channels for your staff team.
        url: "https://blairtcg.github.io/hikari/docs/moderation/"
      - title: Economy system
        icon: fas coins
        content: >-
          Configure currencies, item shops, job roles, gambling limits,
          and a fully custom leaderboard.
        url: "https://blairtcg.github.io/hikari/docs/economy/"
      - title: Changelog
        icon: fas clock-rotate-left
        content: >-
          Latest release notes, bug fixes, and a roadmap of
          upcoming features.
        url: "https://blairtcg.github.io/hikari/docs/changelog/"

  # ─── 13. FAQ (last) ───────────────────────────────────────────────────────
  - _bookshop_name: faq
    heading:
      preheading: "Help"
      title: "Frequently asked questions"
      content: "Can't find your answer? Ask in the support server."
      align: center
    background:
      color: body-tertiary
      subtle: false
    items:
      - title: "Is Blair free to use?"
        description: >-
          Yes — Blair is completely free. Core features will always remain free.
          Optional premium perks may be introduced in the future, but they will
          never gate essential functionality.
      - title: "How do I invite Blair to my server?"
        description: >-
          Click Invite Blair above or use the invite link in the navigation bar.
          You will need the Manage Server Discord permission on the target server.
      - title: "What permissions does Blair need?"
        description: >-
          At minimum — Read Messages, Send Messages, Embed Links, and Add Reactions.
          For moderation commands: Kick Members, Ban Members, and Manage Roles.
          Granting Administrator is simpler but optional.
      - title: "A command is not working. What should I do?"
        description: >-
          Check that Blair has the required permissions in that channel. Verify
          you are using a valid slash command (type /). If the issue persists,
          open a ticket in the support server with your server ID and a screenshot.
      - title: "Can I self-host Blair?"
        description: >-
          Blair is not currently open-source. We host it centrally to ensure
          reliability and rapid updates. Self-hosting may be considered in a
          future roadmap item.
      - title: "How do I report a bug or request a feature?"
        description: >-
          Use the /feedback command inside Discord to submit a report directly,
          or post in the #suggestions channel of the support server.

---

{{< breadcrumb >}}

## Welcome to Hikari

This is the official documentation for **Blair**, your Anime TCG Discord bot!

{{< alert color="info" icon="fas circle-info" >}}
**New here?** Start with the Getting Started guide — it takes less than five minutes to invite Blair and run your first command.
{{< /alert >}}
