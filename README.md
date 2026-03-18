<!-- Animated Gradient Wave Header -->
<svg width="100%" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad">
      <stop offset="0%" stop-color="#00c6ff">
        <animate attributeName="stop-color" values="#00c6ff;#0072ff;#00c6ff" dur="6s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#0072ff">
        <animate attributeName="stop-color" values="#0072ff;#00c6ff;#0072ff" dur="6s" repeatCount="indefinite" />
      </stop>
    </linearGradient>
  </defs>

  <rect width="800" height="200" fill="url(#grad)" />

  <path fill="#ffffff" fill-opacity="0.3">
    <animate attributeName="d" dur="8s" repeatCount="indefinite"
      values="
      M0,100 C150,200 350,0 800,100 L800,200 L0,200 Z;
      M0,120 C200,0 400,200 800,120 L800,200 L0,200 Z;
      M0,100 C150,200 350,0 800,100 L800,200 L0,200 Z
      " />
  </path>

  <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle"
        font-size="28" fill="white" font-family="Arial">
    Abdullah Tahir • Full Stack Developer
  </text>
</svg>
