---
title: Hikari — Blair Bot Documentation
description: >-
  Official documentation hub for Blair, your all-in-one Discord bot.
  Setup guides, command references, configuration, and more.
date: 2025-01-01
layout: home
showBreadcrumb: true

content_blocks:

  # ─── 1. HERO ──────────────────────────────────────────────────────────────
  - _bookshop_name: hero
    heading:
      title: "Blair · Hikari Docs"
      content: >-
        The official documentation for **Blair** — your all-in-one Discord bot.
        Commands, configuration guides, and release notes, all in one place.
      width: 7
    background:
      color: primary
      subtle: true
    illustration:
      image: /img/sunrise.jpg
      ratio: 16x9
    width: 8
    links:
      - title: Get started
        url: /docs/getting-started/
        icon: fas chevron-right
        color: primary
      - title: Command reference
        url: /docs/commands/
        icon: fas terminal
        color: secondary
        outline: true
    orientation: horizontal
    justify: center

  # ─── 2. SEPARATOR ─────────────────────────────────────────────────────────
  - _bookshop_name: separator
    title: "What Blair can do"

  # ─── 3. APPROACH — feature highlights ─────────────────────────────────────
  - _bookshop_name: approach
    heading:
      title: "A bot built for every server"
      content: >-
        From small friend groups to large community servers, Blair adapts
        to your needs with powerful, modular features.
    style: cards
    items:
      - title: Moderation
        description: >-
          Keep your server safe with auto-mod, infraction logging, warns,
          mutes, and bans — configurable per channel and role.
        icon: fas shield-halved
        color: primary

      - title: Music playback
        description: >-
          Stream high-quality audio from YouTube, Spotify, and SoundCloud
          with full queue management, shuffle, and audio filters.
        icon: fas music
        color: secondary

      - title: Economy & games
        description: >-
          Engage members with a full in-server economy, daily rewards,
          leaderboards, shops, and multiplayer minigames.
        icon: fas coins
        color: success

      - title: Custom commands
        description: >-
          Create server-specific slash commands, auto-responses, and
          rich embeds — zero coding required.
        icon: fas terminal
        color: info

      - title: Logging & audit
        description: >-
          Full audit trail for joins, leaves, edits, deletions, and
          all moderator actions. Outputs to any channel you choose.
        icon: fas clipboard-list
        color: warning

      - title: Role management
        description: >-
          Reaction roles, button roles, auto-roles on join, and
          role menus — manage your hierarchy with ease.
        icon: fas users-gear
        color: danger

  # ─── 4. SEPARATOR ─────────────────────────────────────────────────────────
  - _bookshop_name: separator
    title: "Explore the documentation"

  # ─── 5. CARDS — docs section quick-access ─────────────────────────────────
  - _bookshop_name: cards
    heading:
      title: "Jump to a section"
      content: >-
        Use these cards to navigate quickly to the area you need.
        All pages include breadcrumbs and a full table of contents.
    style: card-deck
    cards:
      - title: Getting started
        description: >-
          Invite Blair, grant the right permissions, and run your first
          commands in under five minutes.
        icon: fas rocket
        color: primary
        href: /docs/getting-started/

      - title: Commands reference
        description: >-
          Full alphabetical list of every slash command, its arguments,
          required permissions, and example usage.
        icon: fas terminal
        color: secondary
        href: /docs/commands/

      - title: Configuration
        description: >-
          Customize Blair's prefix, logging channels, module toggles,
          and guild-specific behaviour.
        icon: fas sliders
        color: info
        href: /docs/configuration/

      - title: Moderation guide
        description: >-
          Set up auto-mod filters, warning thresholds, ban lists,
          and logging channels for your staff team.
        icon: fas shield-halved
        color: success
        href: /docs/moderation/

      - title: Economy system
        description: >-
          Configure currencies, item shops, job roles, gambling limits,
          and a fully custom leaderboard.
        icon: fas coins
        color: warning
        href: /docs/economy/

      - title: Changelog
        description: >-
          Latest release notes, bug fixes, and a roadmap of
          upcoming features.
        icon: fas clock-rotate-left
        color: danger
        href: /docs/changelog/

  # ─── 6. SEPARATOR ─────────────────────────────────────────────────────────
  - _bookshop_name: separator
    title: ""

  # ─── 7. FEATURED — invite / support call-out ──────────────────────────────
  - _bookshop_name: featured
    heading:
      title: "Add Blair to your server"
      content: >-
        Blair is free to use and always improving. Invite it in one click,
        or join our support server if you run into any issues.
    image: /img/sunrise.jpg
    ratio: 4x3
    background:
      color: secondary
      subtle: true
    links:
      - title: Invite Blair
        url: "https://discord.com/oauth2/authorize?client_id=YOUR_CLIENT_ID&scope=bot+applications.commands&permissions=8"
        icon: fab discord
        color: primary
      - title: Support server
        url: "https://discord.gg/YOUR_INVITE"
        icon: fas headset
        color: secondary
        outline: true
    orientation: horizontal
    reverse: true

  # ─── 8. SEPARATOR ─────────────────────────────────────────────────────────
  - _bookshop_name: separator
    title: "Frequently asked questions"

  # ─── 9. FAQ ───────────────────────────────────────────────────────────────
  - _bookshop_name: faq
    heading:
      title: "Common questions"
      content: "Can't find your answer here? Ask us in the support server."
    items:
      - question: "Is Blair free to use?"
        answer: >-
          Yes — Blair is completely free. Core features will always remain
          free. Optional premium perks may be introduced in the future,
          but they will never gate essential functionality.

      - question: "How do I invite Blair to my server?"
        answer: >-
          Click **Invite Blair** above or visit the invite link in the
          navigation bar. You will need the **Manage Server** Discord
          permission on the target server.

      - question: "What permissions does Blair need?"
        answer: >-
          At minimum: *Read Messages*, *Send Messages*, *Embed Links*,
          and *Add Reactions*. For moderation commands you also need
          *Kick Members*, *Ban Members*, and *Manage Roles*.
          Granting Administrator is simpler but optional.

      - question: "A command is not working. What should I do?"
        answer: >-
          1. Confirm Blair has the required permissions in that channel.
          2. Check that you are using a valid slash command (type `/`).
          3. Try re-inviting Blair using the invite link to refresh scopes.
          4. If the issue persists, open a ticket in the support server with
             your server ID and a screenshot of the error.

      - question: "Can I self-host Blair?"
        answer: >-
          Blair is not currently open-source. We host it centrally to
          ensure reliability and rapid updates. Self-hosting support
          may be considered in a future roadmap item.

      - question: "How do I report a bug or request a feature?"
        answer: >-
          Use the `/feedback` command inside Discord to submit a report
          directly, or post in the **#suggestions** channel of the
          support server.

  # ─── 10. CTA ──────────────────────────────────────────────────────────────
  - _bookshop_name: cta
    heading:
      title: "Ready to get started?"
      content: >-
        Read the documentation, invite Blair to your server, and take
        your Discord community to the next level — for free.
    background:
      color: primary
      subtle: false
    links:
      - title: Read the docs
        url: /docs/
        icon: fas book-open
        color: light
      - title: Invite Blair
        url: "https://discord.com/oauth2/authorize?client_id=YOUR_CLIENT_ID&scope=bot+applications.commands&permissions=8"
        icon: fab discord
        color: secondary
        outline: true

---

{{< breadcrumb >}}

## Welcome to Hikari

This is the official documentation hub for **Blair**, an all-in-one Discord bot.
Use the cards above to navigate to the section you need, or search with the bar at the top of the page.

{{< alert color="info" icon="fas circle-info" dismissible="false" >}}
**New here?** Start with the [Getting Started](/docs/getting-started/) guide — it takes less than five minutes to invite Blair and run your first command.
{{< /alert >}}

{{< alert color="warning" icon="fas triangle-exclamation" dismissible="false" >}}
**Notice:** Always use the latest version of Blair's invite link to ensure all slash command scopes are registered correctly.
{{< /alert >}}

### On this page

Use the right-hand table of contents, or jump directly to a docs section using the cards above. Each page in this site follows a consistent structure:

- **Breadcrumb trail** — always at the top, so you know exactly where you are
- **Overview** — what the feature does and when to use it  
- **Prerequisites** — permissions or setup steps needed beforehand  
- **Step-by-step guide** — numbered instructions with command examples  
- **Reference table** — all arguments, defaults, and valid values  
- **Troubleshooting** — common errors and how to fix them

---

*This documentation is maintained by the Blair development team. Last updated: {{< param "date" >}}.*
