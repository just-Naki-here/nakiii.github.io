---
layout: default
title: "About"
description: "A much more detailed profile of Naki / N4-K2."
permalink: /about/
---

{% include sections/page-hero.html eyebrow="PROFILE // COMPLETE RECORD" title="About Me" description=page.description %}

<section class="section section-tight">
  <div class="shell profile-layout">
    <article class="glass-card prose">
      ## Hello, Internet.

      I'm **Naki**, also known online as **N4-K2** and **Nawkies**.

      I am a developer, gamer, storyteller, worldbuilder, modder, puzzle enthusiast, and general creator of things that tend to expand far beyond their original plans.

      I like projects where technical and creative work overlap. A programming project becomes more interesting to me when it has a strong design idea behind it, and a writing project becomes more interesting when the world has systems, rules, history, and enough internal structure to feel consistent.

      ## What I Like Making

      I enjoy building Minecraft mods, Roblox systems, web projects, game mechanics, progression systems, achievements, puzzle frameworks, fictional species, character relationships, lore databases, and long-form story projects.

      The exact category matters less than whether the idea gives me room to keep building.

      ## How I Think About Projects

      I tend to think in systems.

      If a project has one mechanic, I immediately start thinking about how it connects to another mechanic. If a character has one ability, I want to know what its limits are, how it changes over time, and what it means for the rest of the setting.

      This is probably why small projects do not remain small for very long.

      ## Online Identity

      **N4-K2** is one of the names I use around online projects and creative spaces.

      **Nawkies** is the author name I use around writing projects.

      I use this website as a central directory instead of trying to fit everything into a short social-media bio.
    </article>

    <aside class="profile-stack">
      <article class="glass-card">
        <div class="card-label">QUICK DATA</div>
        <dl class="data-list">
          <div><dt>Name</dt><dd>{{ site.data.profile.display_name }}</dd></div>
          <div><dt>Aliases</dt><dd>{{ site.data.profile.aliases | join: " / " }}</dd></div>
          <div><dt>Pronouns</dt><dd>{{ site.data.profile.pronouns }}</dd></div>
          <div><dt>Region</dt><dd>{{ site.data.profile.region }}</dd></div>
          <div><dt>Timezone</dt><dd>{{ site.data.profile.timezone }}</dd></div>
          <div><dt>Author Name</dt><dd>{{ site.data.profile.author_name }}</dd></div>
        </dl>
      </article>

      <article class="glass-card">
        <div class="card-label">OPERATING CONDITIONS</div>
        <div class="meter-list">
          <div class="meter-row"><span>Ideas</span><div class="meter"><i style="--value:100%"></i></div><b>CONSTANT</b></div>
          <div class="meter-row"><span>Lore</span><div class="meter"><i style="--value:97%"></i></div><b>EXPANDING</b></div>
          <div class="meter-row"><span>Scope</span><div class="meter"><i style="--value:99%"></i></div><b>ESCALATING</b></div>
          <div class="meter-row"><span>Tabs</span><div class="meter"><i style="--value:91%"></i></div><b>MANY</b></div>
        </div>
      </article>
    </aside>
  </div>
</section>

<section class="section section-alt">
  <div class="shell">
    <div class="section-heading">
      <p class="eyebrow">PROFILE // ROLES</p>
      <h2>What I Do</h2>
    </div>

    <div class="interest-grid">
      <article class="feature-card">
        <div class="feature-number">01</div>
        <h3>Developer</h3>
        <p>I like building systems, tools, mechanics, mods, web interfaces, and experimental projects.</p>
      </article>
      <article class="feature-card">
        <div class="feature-number">02</div>
        <h3>Gamer</h3>
        <p>I especially enjoy games with customization, discovery, progression, puzzles, modding, or unusual systems.</p>
      </article>
      <article class="feature-card">
        <div class="feature-number">03</div>
        <h3>Storyteller</h3>
        <p>I write character-heavy fiction and enjoy turning ideas into long-running arcs rather than isolated scenes.</p>
      </article>
      <article class="feature-card">
        <div class="feature-number">04</div>
        <h3>Worldbuilder</h3>
        <p>I like building species, relationships, factions, rules, timelines, locations, progression, and lore archives.</p>
      </article>
    </div>
  </div>
</section>
