<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="<svg xmlns="http://www.w3.org/2000/svg" width="1180" height="610" viewBox="0 0 1180 610" role="img" aria-label="Developer Profile Terminal Banner — Software and Systems Engineering">
  <title>Developer Profile — Systems & Software Engineering</title>
  <desc>Interactive SMIL-animated terminal hero banner featuring an ASCII portrait under VISUAL.MAP and engineering profile specifications under SYSTEM.INFO.</desc>

  <defs>
    <!-- Background & Surface Gradients -->
    <linearGradient id="bgBase" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#030712" />
      <stop offset="50%" stop-color="#07111F" />
      <stop offset="100%" stop-color="#0B1220" />
    </linearGradient>

    <radialGradient id="glowViolet" cx="22%" cy="28%" r="48%">
      <stop offset="0%" stop-color="#7C3AED" stop-opacity="0.22">
        <animate attributeName="stop-opacity" values="0.16;0.26;0.16" dur="8s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#7C3AED" stop-opacity="0" />
    </radialGradient>

    <radialGradient id="glowCyan" cx="78%" cy="72%" r="52%">
      <stop offset="0%" stop-color="#22D3EE" stop-opacity="0.18">
        <animate attributeName="stop-opacity" values="0.14;0.24;0.14" dur="10s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#22D3EE" stop-opacity="0" />
    </radialGradient>

    <linearGradient id="accentGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7C3AED">
        <animate attributeName="stop-color" values="#7C3AED;#22D3EE;#10B981;#7C3AED" dur="14s" repeatCount="indefinite" />
      </stop>
      <stop offset="50%" stop-color="#22D3EE">
        <animate attributeName="stop-color" values="#22D3EE;#10B981;#7C3AED;#22D3EE" dur="14s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#10B981">
        <animate attributeName="stop-color" values="#10B981;#7C3AED;#22D3EE;#10B981" dur="14s" repeatCount="indefinite" />
      </stop>
    </linearGradient>

    <linearGradient id="glassSurface" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#1E293B" stop-opacity="0.42" />
      <stop offset="100%" stop-color="#0F172A" stop-opacity="0.28" />
    </linearGradient>

    <linearGradient id="glassBorder" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#38BDF8" stop-opacity="0.45" />
      <stop offset="50%" stop-color="#94A3B8" stop-opacity="0.15" />
      <stop offset="100%" stop-color="#7C3AED" stop-opacity="0.40" />
    </linearGradient>

    <linearGradient id="asciiGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#E2E8F0" />
      <stop offset="55%" stop-color="#22D3EE" />
      <stop offset="100%" stop-color="#7C3AED" />
    </linearGradient>

    <linearGradient id="scanlineGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#22D3EE" stop-opacity="0" />
      <stop offset="50%" stop-color="#22D3EE" stop-opacity="0.22" />
      <stop offset="100%" stop-color="#22D3EE" stop-opacity="0" />
    </linearGradient>

    <linearGradient id="shimmerSweep" x1="0%" y1="0%" x2="100%" y2="20%">
      <stop offset="0%" stop-color="#FFFFFF" stop-opacity="0" />
      <stop offset="50%" stop-color="#FFFFFF" stop-opacity="0.04" />
      <stop offset="100%" stop-color="#FFFFFF" stop-opacity="0" />
    </linearGradient>

    <!-- Patterns -->
    <pattern id="gridPattern" width="32" height="32" patternUnits="userSpaceOnUse">
      <path d="M 32 0 L 0 0 0 32" fill="none" stroke="#94A3B8" stroke-width="0.5" stroke-opacity="0.07" />
    </pattern>

    <pattern id="scanPattern" width="4" height="4" patternUnits="userSpaceOnUse">
      <line x1="0" y1="0" x2="4" y2="0" stroke="#020617" stroke-width="1" stroke-opacity="0.32" />
    </pattern>

    <!-- Glow Filters -->
    <filter id="softGlow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3" result="blur" />
      <feComposite in="SourceGraphic" in2="blur" operator="over" />
    </filter>

    <!-- Clip Paths -->
    <clipPath id="outerClip">
      <rect x="12" y="12" width="1156" height="586" rx="24" />
    </clipPath>

    <clipPath id="portraitClip">
      <rect x="48" y="124" width="400" height="284" rx="12" />
    </clipPath>

    <!-- Discrete Character-by-Character Typing Clip for Left Prompt -->
    <clipPath id="cmdTypeClip">
      <rect x="166" y="522" width="168" height="26">
        <animate attributeName="width" calcMode="discrete" values="0;16;32;48;64;80;96;112;128;144;168;168;168" keyTimes="0;0.06;0.12;0.18;0.24;0.30;0.36;0.42;0.48;0.54;0.60;0.85;1" dur="8s" repeatCount="indefinite" />
      </rect>
    </clipPath>

    <!-- Discrete Character-by-Character Typing Clip for Right Role -->
    <clipPath id="roleTypeClip">
      <rect x="656" y="204" width="240" height="24">
        <animate attributeName="width" calcMode="discrete" values="0;24;48;72;96;120;144;168;192;216;240;240;240" keyTimes="0;0.05;0.10;0.15;0.20;0.25;0.30;0.35;0.40;0.45;0.50;0.90;1" dur="4s" repeatCount="indefinite" />
      </rect>
    </clipPath>
  </defs>

  <!-- Main Clipped Canvas -->
  <g clip-path="url(#outerClip)">
    <!-- Deep Background Layers -->
    <rect x="12" y="12" width="1156" height="586" rx="24" fill="url(#bgBase)" />
    <rect x="12" y="12" width="1156" height="586" fill="url(#glowViolet)" />
    <rect x="12" y="12" width="1156" height="586" fill="url(#glowCyan)" />
    <rect x="12" y="12" width="1156" height="586" fill="url(#gridPattern)" />

    <!-- Subtle Floating Particles -->
    <g fill="#22D3EE" fill-opacity="0.35">
      <circle cx="140" cy="520" r="1.5">
        <animate attributeName="cy" values="520;480;520" dur="9s" repeatCount="indefinite" />
        <animate attributeName="fill-opacity" values="0.15;0.45;0.15" dur="9s" repeatCount="indefinite" />
      </circle>
      <circle cx="420" cy="160" r="1.2">
        <animate attributeName="cy" values="160;130;160" dur="11s" repeatCount="indefinite" />
      </circle>
      <circle cx="880" cy="140" r="1.5">
        <animate attributeName="cy" values="140;110;140" dur="8s" repeatCount="indefinite" />
      </circle>
      <circle cx="1080" cy="460" r="1.8">
        <animate attributeName="cy" values="460;420;460" dur="12s" repeatCount="indefinite" />
      </circle>
    </g>

    <!-- ========================================== -->
    <!-- 1. TOP TERMINAL / EDITOR CHROME HEADER     -->
    <!-- ========================================== -->
    <g opacity="1">
      <animate attributeName="opacity" values="0;1" dur="0.3s" fill="freeze" />
      <rect x="28" y="24" width="1124" height="40" rx="12" fill="#0F172A" fill-opacity="0.55" stroke="url(#glassBorder)" stroke-width="1" />

      <!-- Window Controls -->
      <circle cx="52" cy="44" r="5.5" fill="#EF4444" />
      <circle cx="70" cy="44" r="5.5" fill="#F59E0B" />
      <circle cx="88" cy="44" r="5.5" fill="#10B981" />

      <!-- Host Prompt -->
      <text x="112" y="48" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="12.5" font-weight="600" fill="#E2E8F0">developer@profile:~</text>

      <!-- Editor Decorative Navigation -->
      <g font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="11.5" fill="#94A3B8" text-anchor="middle">
        <text x="590" y="48" xml:space="preserve">Code      Projects      Architecture      Contact</text>
      </g>

      <!-- Status Pill -->
      <rect x="1036" y="32" width="100" height="24" rx="12" fill="#064E3B" fill-opacity="0.45" stroke="#10B981" stroke-opacity="0.45" stroke-width="1" />
      <circle cx="1052" cy="44" r="3.8" fill="#10B981">
        <animate attributeName="opacity" values="1;0.35;1" dur="2.4s" repeatCount="indefinite" />
      </circle>
      <text x="1064" y="48" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="11" font-weight="600" fill="#A7F3D0" letter-spacing="0.8">ONLINE</text>
    </g>

    <!-- ========================================== -->
    <!-- 2. LEFT PANEL — VISUAL.MAP (39% WIDTH)     -->
    <!-- ========================================== -->
    <g opacity="1">
      <animate attributeName="opacity" values="0;1" dur="0.45s" fill="freeze" />

      <!-- Left Glass Panel Card -->
      <rect x="28" y="76" width="440" height="506" rx="16" fill="url(#glassSurface)" stroke="url(#glassBorder)" stroke-width="1" />

      <!-- Panel Header -->
      <text x="48" y="99" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="11.5" font-weight="700" fill="#22D3EE" letter-spacing="1.4">VISUAL.MAP</text>
      <text x="448" y="99" text-anchor="end" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="11" fill="#94A3B8">[ PORTRAIT.ASCII ]</text>
      <line x1="28" y1="112" x2="468" y2="112" stroke="#334155" stroke-opacity="0.6" stroke-width="1" />

      <!-- ASCII Portrait Viewport (Centered at X=248) -->
      <rect x="48" y="124" width="400" height="284" rx="12" fill="#030712" fill-opacity="0.65" stroke="#1E293B" stroke-width="1" />

      <g clip-path="url(#portraitClip)">
        <!-- Floating Portrait Matrix -->
        <g>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-2.5; 0,0" dur="6s" repeatCount="indefinite" />

          <g font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="10.2" font-weight="600" fill="url(#asciiGrad)" text-anchor="middle" letter-spacing="1.05" xml:space="preserve">
            <text x="248" y="145">              .·:+*######*+:·.              <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.05s" fill="freeze" /></text>
            <text x="248" y="157">           .·+*###%%%%%%%%###*+·.           <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.08s" fill="freeze" /></text>
            <text x="248" y="169">         .:*##%%%%@@@@@@@@%%%%##*:.         <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.11s" fill="freeze" /></text>
            <text x="248" y="181">        :*#%%%@@@@%%%%%%%%@@@@%%%#*:        <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.14s" fill="freeze" /></text>
            <text x="248" y="193">       +#%%@@@%%##**++++**##%%@@@%%#+       <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.17s" fill="freeze" /></text>
            <text x="248" y="205">      *#%%@@%#*+::··....··::+*#%@@%%#*      <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.20s" fill="freeze" /></text>
            <text x="248" y="217">     +#%%@%#+:·.            .·:+#%@%%#+     <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.23s" fill="freeze" /></text>
            <text x="248" y="229">     #%@@%+:·   .·:+*##*+:·.   ·:+%@@%#     <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.26s" fill="freeze" /></text>
            <text x="248" y="241">    .#%@@*·  :+*#%@@#++#@@%#*+:  ·*@@%#.    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.29s" fill="freeze" /></text>
            <text x="248" y="253">    :%@@%:  +#@@%#*+·::·+*#%@@#+  :%@@%:    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.32s" fill="freeze" /></text>
            <text x="248" y="265">    +@@@#·  *@#=:·+*#::#*+·:=#@*  ·#@@@+    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.35s" fill="freeze" /></text>
            <text x="248" y="277">    .#@@%·  :++:··:++::++:··:++:  ·%@@#.    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.38s" fill="freeze" /></text>
            <text x="248" y="289">     *@@%:      .·:·:++:·:·.      :%@@*     <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.41s" fill="freeze" /></text>
            <text x="248" y="301">      #@@*·       .·+**+·.       ·*@@#      <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.44s" fill="freeze" /></text>
            <text x="248" y="313">      :#@@#·    .·:+*##*+:·.    ·#@@#:      <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.47s" fill="freeze" /></text>
            <text x="248" y="325">       :#@@%+:·.  ·:+**+:·  .·:+%@@#:       <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.50s" fill="freeze" /></text>
            <text x="248" y="337">        .*%@@%#*+:··....··:+*#%@@%*.        <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.53s" fill="freeze" /></text>
            <text x="248" y="349">         .:+#%@@@%%######%%@@@%#+:.         <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.56s" fill="freeze" /></text>
            <text x="248" y="361">        .·+*#%@%#*+::··::+*#%@%#*+·.        <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.59s" fill="freeze" /></text>
            <text x="248" y="373">     .·+*#%%@@%+:·.      .·:+%@@%%#*+·.     <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.62s" fill="freeze" /></text>
            <text x="248" y="385">  .·+*#%%@@@@%#*:·.      .·:*#%@@@@%%#*+·.  <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.65s" fill="freeze" /></text>
            <text x="248" y="397">.:*#%%@@@@@@@%%#*+:.    .:+*#%%@@@@@@@%%#*:.<animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.68s" fill="freeze" /></text>
          </g>
        </g>

        <!-- Subtle Scanline Overlay & Animated Sweep -->
        <rect x="48" y="124" width="400" height="284" fill="url(#scanPattern)" pointer-events="none" />
        <rect x="48" y="124" width="400" height="28" fill="url(#scanlineGrad)">
          <animate attributeName="y" values="100;410;100" dur="7s" repeatCount="indefinite" />
        </rect>
      </g>

      <!-- Portrait Frame Corner Brackets -->
      <path d="M 48 140 L 48 124 L 64 124 M 432 124 L 448 124 L 448 140 M 48 392 L 48 408 L 64 408 M 432 408 L 448 408 L 448 392" fill="none" stroke="#22D3EE" stroke-width="1.5" stroke-opacity="0.65" />

      <!-- Left Supporting Identity Block (Centered at X=248) -->
      <text x="248" y="436" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="11" font-weight="600" fill="#22D3EE" letter-spacing="1.6">[ PROFILE / ENGINEERING ]</text>
      <text x="248" y="464" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="15.5" font-weight="700" fill="#F8FAFC">Systems & Software Engineering</text>
      <text x="248" y="488" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="11.5" fill="#94A3B8">Architecture · Reliability · Technical Craft</text>

      <!-- Bottom Command Prompt Box -->
      <rect x="48" y="512" width="400" height="46" rx="10" fill="#030712" fill-opacity="0.6" stroke="#1E293B" stroke-width="1" />
      <text x="68" y="540" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="12.5" fill="#10B981" font-weight="600">~/profile $</text>
      <g clip-path="url(#cmdTypeClip)">
        <text x="166" y="540" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="12.5" fill="#F8FAFC">build --ship --verify</text>
      </g>
      <!-- Cursor Synchronized Immediately After Visible Text -->
      <rect x="334" y="527" width="7" height="15" fill="#22D3EE">
        <animate attributeName="x" calcMode="discrete" values="166;182;198;214;230;246;262;278;294;310;334;334;334" keyTimes="0;0.06;0.12;0.18;0.24;0.30;0.36;0.42;0.48;0.54;0.60;0.85;1" dur="8s" repeatCount="indefinite" />
        <animate attributeName="opacity" values="1;0;1" dur="0.9s" repeatCount="indefinite" />
      </rect>
    </g>

    <!-- ========================================== -->
    <!-- 3. RIGHT PANEL — SYSTEM.INFO (61% WIDTH)   -->
    <!-- ========================================== -->
    <g opacity="1">
      <animate attributeName="opacity" values="0;1" dur="0.55s" fill="freeze" />

      <!-- Right Glass Panel Card -->
      <rect x="484" y="76" width="668" height="506" rx="16" fill="url(#glassSurface)" stroke="url(#glassBorder)" stroke-width="1" />

      <!-- Panel Header -->
      <text x="508" y="99" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="11.5" font-weight="700" fill="#22D3EE" letter-spacing="1.4">SYSTEM.INFO</text>
      <text x="1128" y="99" text-anchor="end" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="11.5" fill="#94A3B8">developer@profile:~$ ./profile.sh</text>
      <line x1="484" y1="112" x2="1152" y2="112" stroke="#334155" stroke-opacity="0.6" stroke-width="1" />

      <!-- Primary Identity & Headline -->
      <g>
        <text x="508" y="150" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="24" font-weight="700" fill="#F8FAFC" letter-spacing="0.6">DEVELOPER PROFILE</text>
        <text x="508" y="176" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="13.5" font-weight="600" fill="url(#accentGrad)">Software Engineer · Systems Architect · Technical Builder</text>
        <line x1="508" y1="192" x2="1128" y2="192" stroke="#334155" stroke-opacity="0.5" stroke-width="1" />
      </g>

      <!-- Balanced Information Grid (Right-Aligned Labels @ X=636, Left-Aligned Values @ X=656) -->
      <g font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="12.5">
        <!-- Row 1: Animated Role Rotation -->
        <text x="636" y="220" text-anchor="end" fill="#22D3EE" font-weight="600">> ROLE</text>
        <g clip-path="url(#roleTypeClip)">
          <text x="656" y="220" fill="#F8FAFC" font-weight="700">
            Software & Systems Engineer
            <animate attributeName="opacity" calcMode="discrete" values="1;0;0" keyTimes="0;0.333;1" dur="12s" repeatCount="indefinite" />
          </text>
          <text x="656" y="220" fill="#F8FAFC" font-weight="700" opacity="0">
            Full-Stack Platform Builder
            <animate attributeName="opacity" calcMode="discrete" values="0;1;0" keyTimes="0;0.333;0.666" dur="12s" repeatCount="indefinite" />
          </text>
          <text x="656" y="220" fill="#F8FAFC" font-weight="700" opacity="0">
            Distributed Systems Architect
            <animate attributeName="opacity" calcMode="discrete" values="0;0;1" keyTimes="0;0.666;1" dur="12s" repeatCount="indefinite" />
          </text>
        </g>
        <!-- Synchronized Role Cursor -->
        <rect x="896" y="207" width="7" height="15" fill="#22D3EE">
          <animate attributeName="x" calcMode="discrete" values="656;680;704;728;752;776;800;824;848;872;896;896;896" keyTimes="0;0.05;0.10;0.15;0.20;0.25;0.30;0.35;0.40;0.45;0.50;0.90;1" dur="4s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite" />
        </rect>

        <!-- Row 2: Focus -->
        <text x="636" y="248" text-anchor="end" fill="#22D3EE" font-weight="600">> FOCUS</text>
        <text x="656" y="248" fill="#E2E8F0">System Design · Scalable Services · Developer Tooling</text>

        <!-- Row 3: Stack -->
        <text x="636" y="276" text-anchor="end" fill="#22D3EE" font-weight="600">> STACK</text>
        <text x="656" y="276" fill="#E2E8F0">Languages · Backend · Frontend · Cloud · CI/CD · Data</text>

        <!-- Row 4: Building -->
        <text x="636" y="304" text-anchor="end" fill="#22D3EE" font-weight="600">> BUILDING</text>
        <text x="656" y="304" fill="#94A3B8">Resilient Architecture, Modular APIs & Production Systems</text>
      </g>

      <line x1="508" y1="324" x2="1128" y2="324" stroke="#334155" stroke-opacity="0.5" stroke-width="1" />

      <!-- Core Domains / Technology Stack Pills -->
      <text x="508" y="346" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="11" font-weight="700" fill="#94A3B8" letter-spacing="1.4">CORE.DOMAINS // ENGINEERING STACK</text>

      <g font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="11.5" font-weight="600" fill="#F8FAFC">
        <!-- Row 1 Pills -->
        <g>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-1.5; 0,0" dur="5s" repeatCount="indefinite" />
          <rect x="508" y="358" width="146" height="30" rx="8" fill="#0F172A" fill-opacity="0.65" stroke="#22D3EE" stroke-opacity="0.4" stroke-width="1" />
          <circle cx="524" cy="373" r="3.5" fill="#22D3EE" />
          <text x="536" y="377">System Design</text>
        </g>

        <g>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-1.5; 0,0" dur="5.5s" begin="0.4s" repeatCount="indefinite" />
          <rect x="666" y="358" width="146" height="30" rx="8" fill="#0F172A" fill-opacity="0.65" stroke="#7C3AED" stroke-opacity="0.45" stroke-width="1" />
          <circle cx="682" cy="373" r="3.5" fill="#7C3AED" />
          <text x="694" y="377">Backend APIs</text>
        </g>

        <g>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-1.5; 0,0" dur="6s" begin="0.8s" repeatCount="indefinite" />
          <rect x="824" y="358" width="146" height="30" rx="8" fill="#0F172A" fill-opacity="0.65" stroke="#10B981" stroke-opacity="0.4" stroke-width="1" />
          <circle cx="840" cy="373" r="3.5" fill="#10B981" />
          <text x="852" y="377">Web Interfaces</text>
        </g>

        <g>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-1.5; 0,0" dur="5.2s" begin="1.2s" repeatCount="indefinite" />
          <rect x="982" y="358" width="146" height="30" rx="8" fill="#0F172A" fill-opacity="0.65" stroke="#22D3EE" stroke-opacity="0.4" stroke-width="1" />
          <circle cx="998" cy="373" r="3.5" fill="#22D3EE" />
          <text x="1010" y="377">Cloud & Infra</text>
        </g>

        <!-- Row 2 Pills -->
        <g>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-1.5; 0,0" dur="5.8s" begin="0.2s" repeatCount="indefinite" />
          <rect x="508" y="396" width="146" height="30" rx="8" fill="#0F172A" fill-opacity="0.65" stroke="#7C3AED" stroke-opacity="0.45" stroke-width="1" />
          <circle cx="524" cy="411" r="3.5" fill="#7C3AED" />
          <text x="536" y="415">Data Systems</text>
        </g>

        <g>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-1.5; 0,0" dur="5.4s" begin="0.6s" repeatCount="indefinite" />
          <rect x="666" y="396" width="146" height="30" rx="8" fill="#0F172A" fill-opacity="0.65" stroke="#10B981" stroke-opacity="0.4" stroke-width="1" />
          <circle cx="682" cy="411" r="3.5" fill="#10B981" />
          <text x="694" y="415">Automation</text>
        </g>

        <g>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-1.5; 0,0" dur="6.2s" begin="1.0s" repeatCount="indefinite" />
          <rect x="824" y="396" width="146" height="30" rx="8" fill="#0F172A" fill-opacity="0.65" stroke="#22D3EE" stroke-opacity="0.4" stroke-width="1" />
          <circle cx="840" cy="411" r="3.5" fill="#22D3EE" />
          <text x="852" y="415">Testing & QA</text>
        </g>

        <g>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-1.5; 0,0" dur="5.6s" begin="1.4s" repeatCount="indefinite" />
          <rect x="982" y="396" width="146" height="30" rx="8" fill="#0F172A" fill-opacity="0.65" stroke="#7C3AED" stroke-opacity="0.45" stroke-width="1" />
          <circle cx="998" cy="411" r="3.5" fill="#7C3AED" />
          <text x="1010" y="415">Security & Auth</text>
        </g>
      </g>

      <line x1="508" y1="440" x2="1128" y2="440" stroke="#334155" stroke-opacity="0.5" stroke-width="1" />

      <!-- Selected Modules / Projects Section -->
      <text x="508" y="462" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="11" font-weight="700" fill="#94A3B8" letter-spacing="1.4">SELECTED.MODULES // WORKSPACE</text>

      <!-- Module Card 1 -->
      <rect x="508" y="472" width="302" height="54" rx="10" fill="#030712" fill-opacity="0.5" stroke="#1E293B" stroke-width="1" />
      <text x="524" y="493" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="12.5" font-weight="700" fill="#22D3EE">core-architecture</text>
      <text x="524" y="513" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="11" fill="#94A3B8">Modular service design & API contracts</text>

      <!-- Module Card 2 -->
      <rect x="826" y="472" width="302" height="54" rx="10" fill="#030712" fill-opacity="0.5" stroke="#1E293B" stroke-width="1" />
      <text x="842" y="493" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="12.5" font-weight="700" fill="#10B981">dev-workflow</text>
      <text x="842" y="513" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="11" fill="#94A3B8">Automated build, verification & release</text>

      <!-- Footer Channels Bar -->
      <line x1="508" y1="538" x2="1128" y2="538" stroke="#334155" stroke-opacity="0.5" stroke-width="1" />
      <g font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace" font-size="11.5">
        <text x="508" y="562" fill="#22D3EE" font-weight="700">CHANNELS //</text>
        <text x="604" y="562" fill="#E2E8F0" xml:space="preserve">[ GitHub ]   [ Portfolio ]   [ Writing ]   [ Connect ]</text>
        <text x="1128" y="562" text-anchor="end" fill="#10B981" font-weight="600">SYS.READY</text>
      </g>
    </g>

    <!-- Subtle Glass Reflection Sweep -->
    <rect x="-600" y="12" width="420" height="586" fill="url(#shimmerSweep)" transform="skewX(-20)" pointer-events="none">
      <animate attributeName="x" values="-600;1600;1600" keyTimes="0;0.35;1" dur="14s" repeatCount="indefinite" />
    </rect>
  </g>

  <!-- Outer Rounded Frame Border -->
  <rect x="12" y="12" width="1156" height="586" rx="24" fill="none" stroke="url(#glassBorder)" stroke-width="1.5" />
</svg>">
    <img src="./dark.svg" alt="Amirhossein Forouzan Najafabadi — Full-Stack Developer and Database Engineer" width="100%">
  </picture>
</div>

<br />

## ⚡ Engineering Focus

I am a **Software Developer and Database Engineer** specializing in full-stack web applications, relational database architecture, and custom desktop automation systems. My work centers on designing clean RESTful backends, responsive frontend interfaces, and resilient data workflows that solve practical operational problems.

- **Full-Stack Web Engineering:** Building scalable applications using **React**, **Tailwind CSS**, **TanStack Query/Router**, **Node.js**, and **Express**.
- **Database Architecture & Containerization:** Designing normalized schemas, dynamic SQL queries, and role-based access control (RBAC) across **PostgreSQL** (Dockerized environments), **MySQL**, and **Microsoft Access**.
- **Desktop & Enterprise Automation:** Developing custom **C# (.NET)** applications using **WPF** and **WinForms**, integrating complex Persian calendar scheduling algorithms, shift calculation engines, and **Stimulsoft Reports**.

---

## 🛠️ Selected Projects & Systems

| System | Architecture & Stack | Core Capabilities |
| :--- | :--- | :--- |
| **Student Planner** | `React` · `Node.js` · `Express` · `PostgreSQL 16` · `Docker` | Collaborative full-stack academic planning platform running a containerized PostgreSQL database and a shared REST API over local network infrastructure. |
| **TicketYar (تیکت‌یار)** | `React` · `Node.js` · `Express` · `MySQL` | Internal ticketing and office automation system designed to streamline organizational workflows, request tracking, and department communications. |
| **React Pizza Ordering App** | `React` · `TanStack Query` · `TanStack Router` · `Tailwind CSS` · `Vitest` | Modern web application featuring asynchronous state management, type-safe routing, Context API state patterns, and unit test coverage. |
| **AttendanceScheduler** | `C#` · `WPF` · `.NET` | Desktop workforce management application featuring a custom Persian calendar grid that calculates work shifts, accrued annual leave, and compensatory rest days. |
| **Shiftiha** | `C#` · `WinForms` · `Stimulsoft Reports` | Shift history and operational event logging system with native Persian calendar support and automated printable report generation. |
| **Quiz Master** | `JavaScript (ES6 Modules)` · `HTML5` · `CSS3` · `OpenTDB API` | Modular browser-based quiz application integrating external trivia APIs with clean state transitions. |

---

## 🧰 Technical Stack

| Category | Technologies |
| :--- | :--- |
| **Frontend Development** | React, JavaScript (ES6+), HTML5, CSS3, Tailwind CSS, TanStack Query, TanStack Router, Context API |
| **Backend & APIs** | Node.js, Express.js, RESTful API Design, CORS & LAN Service Configuration |
| **Databases & Storage** | PostgreSQL, MySQL, Microsoft Access, Relational Schema Design, Dynamic SQL |
| **Desktop & Automation** | C#, .NET, WPF, WinForms, VBA Automation, Stimulsoft Reports, Role-Based Access Control (RBAC) |
| **DevOps, Testing & Tools** | Docker, Git, Vitest, Visual Studio, Visual Branding & Logo Design |
