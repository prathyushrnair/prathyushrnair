# README 
<p align="center">
    <img src="banner.svg" width="100%">
</p>
<?xml version="1.0" encoding="UTF-8"?>
<svg width="1600" height="400"
     viewBox="0 0 1600 400"
     xmlns="http://www.w3.org/2000/svg">

    <defs>

        <!-- Background -->
        <linearGradient id="bg"
                        x1="0%"
                        y1="100%"
                        x2="100%"
                        y2="0%">
            <stop offset="0%" stop-color="#555555"/>
            <stop offset="45%" stop-color="#8a8a8a"/>
            <stop offset="100%" stop-color="#ffffff"/>
        </linearGradient>

        <!-- White Glow -->
        <filter id="glow" x="-40%" y="-40%" width="180%" height="180%">
            <feGaussianBlur stdDeviation="5"
                result="blur"/>
            <feMerge>
                <feMergeNode in="blur"/>
                <feMergeNode in="SourceGraphic"/>
            </feMerge>
        </filter>

        <!-- Shadow -->
        <filter id="shadow">
            <feDropShadow
                dx="0"
                dy="8"
                stdDeviation="10"
                flood-color="#000"
                flood-opacity="0.45"/>
        </filter>

    </defs>

    <!-- Background -->

    <rect
        width="1600"
        height="400"
        fill="url(#bg)"/>

    <!-- Top Wave -->

    <path
        d="
        M0,70
        C200,20
        350,120
        550,70
        C750,20
        950,120
        1200,60
        C1400,20
        1500,80
        1600,40"
        fill="none"
        stroke="white"
        stroke-width="3"
        opacity=".85"/>

    <path
        d="
        M0,80
        C200,30
        350,130
        550,80
        C750,30
        950,130
        1200,70
        C1400,30
        1500,90
        1600,50"
        fill="none"
        stroke="white"
        stroke-width="1"
        opacity=".35"/>

    <!-- Bottom Wave -->

    <path
        d="
        M0,360
        C180,330
        420,420
        650,360
        C900,300
        1100,420
        1350,340
        C1500,300
        1560,350
        1600,320"
        fill="none"
        stroke="white"
        stroke-width="3"
        opacity=".8"/>

    <path
        d="
        M0,350
        C180,320
        420,410
        650,350
        C900,290
        1100,410
        1350,330
        C1500,290
        1560,340
        1600,310"
        fill="none"
        stroke="white"
        stroke-width="1"
        opacity=".35"/>

    <!-- Stars -->

    <g fill="white">

        <circle cx="120" cy="60" r="3"/>
        <circle cx="260" cy="110" r="2"/>
        <circle cx="420" cy="80" r="2"/>
        <circle cx="710" cy="45" r="2"/>
        <circle cx="930" cy="95" r="3"/>
        <circle cx="1120" cy="50" r="2"/>
        <circle cx="1420" cy="90" r="3"/>
        <circle cx="1490" cy="40" r="2"/>

        <circle cx="320" cy="340" r="2"/>
        <circle cx="620" cy="305" r="2"/>
        <circle cx="820" cy="350" r="3"/>
        <circle cx="1050" cy="330" r="2"/>
        <circle cx="1280" cy="290" r="3"/>
        <circle cx="1480" cy="360" r="2"/>

    </g>

    <!-- Name -->

    <text
        x="800"
        y="215"
        text-anchor="middle"
        font-size="92"
        font-family="Segoe UI,Arial,sans-serif"
        font-weight="700"
        fill="white"
        filter="url(#shadow) url(#glow)">
        Prathyush R Nair
    </text>

    <!-- Subtitle -->

    <text
        x="800"
        y="290"
        text-anchor="middle"
        font-size="34"
        font-family="Segoe UI,Arial,sans-serif"
        font-weight="600"
        fill="white"
        opacity="0.98"
        filter="url(#shadow)">
        Web Developer │ Full-Stack │ Robotics (Perception Handling)
    </text>

</svg>



- 🔭 I’m currently working on Autonomous Navigation
- 🌱 I’m currently learning 3rd Btech on Muthooth Institute of Technology and Science
- 👯 I’m looking to collaborate on projects based on AI / ML / Aerial Drone / Underwater Sub 
- 🤔 I’m looking for help with implementation of begginer to all the way till  advanced logics on autonomy navigation on UAV / Underwater
- 📫 How to reach me: mail:prathyushrnair@gmail.com 
- ⚡ Fun fact: Just a regualr normal mtf... 
