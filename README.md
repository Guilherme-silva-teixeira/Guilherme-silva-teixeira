<svg width="400" height="400"
     viewBox="0 0 400 400"
     xmlns="http://www.w3.org/2000/svg"
     style="background:#f00">

  <!-- SVG grande (logo) -->
  <g transform="scale(0.035)">
    <!-- TODO o path amarelo aqui -->
  </g>

  <!-- Typing SVG -->
  <g transform="translate(0 180) scale(0.92)">
    <path id="path0">
      <animate
        id="d0"
        attributeName="d"
        begin="0s;d0.end"
        dur="6000ms"
        fill="remove"
        values="
          m0,25 h0;
          m0,25 h435;
          m0,25 h435;
          m0,25 h0"
        keyTimes="0;0.66;0.83;1" />
    </path>
    <text font-family="Fira Code, monospace"
          fill="#F7D800"
          font-size="20"
          x="50%"
          text-anchor="middle">
      <textPath href="#path0">
        Hello World
      </textPath>
    </text>

  </g>

</svg>
