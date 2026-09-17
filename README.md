# prak_pp14_09
<img width="1200" height="720" alt="Потоки" src="https://github.com/user-attachments/assets/0c71533b-25c8-44a2-a847-ad04f5d57c4f" />
<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="720" viewBox="0 0 1200 720">
  <rect width="100%" height="100%" fill="white"/>
  <style>
    text { font-family: Arial, sans-serif; fill: #1f2937; }
    .axis { stroke: #374151; stroke-width: 2; }
    .grid { stroke: #d1d5db; stroke-width: 1; stroke-dasharray: 5 5; }
    .bar { fill: #2563eb; }
    .value { font-size: 18px; font-weight: bold; }
  </style>

  <text x="600" y="55" text-anchor="middle" font-size="30" font-weight="bold">Время суммирования массива при разном числе потоков</text>
  <text x="600" y="85" text-anchor="middle" font-size="18">Размер массива: 1 000 000 000 элементов</text>

  <line class="axis" x1="130" y1="610" x2="1130" y2="610"/>
  <line class="axis" x1="130" y1="120" x2="130" y2="610"/>

  <line class="grid" x1="130" y1="610" x2="1130" y2="610"/>
  <line class="grid" x1="130" y1="496" x2="1130" y2="496"/>
  <line class="grid" x1="130" y1="382" x2="1130" y2="382"/>
  <line class="grid" x1="130" y1="268" x2="1130" y2="268"/>
  <line class="grid" x1="130" y1="154" x2="1130" y2="154"/>

  <text x="115" y="616" text-anchor="end" font-size="16">0</text>
  <text x="115" y="502" text-anchor="end" font-size="16">1000</text>
  <text x="115" y="388" text-anchor="end" font-size="16">2000</text>
  <text x="115" y="274" text-anchor="end" font-size="16">3000</text>
  <text x="115" y="160" text-anchor="end" font-size="16">4000</text>

  <rect class="bar" x="200" y="120" width="110" height="490" rx="4"/>
  <rect class="bar" x="390" y="318" width="110" height="292" rx="4"/>
  <rect class="bar" x="580" y="446" width="110" height="164" rx="4"/>
  <rect class="bar" x="770" y="473" width="110" height="137" rx="4"/>
  <rect class="bar" x="960" y="466" width="110" height="144" rx="4"/>

  <text class="value" x="255" y="108" text-anchor="middle">4298</text>
  <text class="value" x="445" y="306" text-anchor="middle">2564</text>
  <text class="value" x="635" y="434" text-anchor="middle">1442</text>
  <text class="value" x="825" y="461" text-anchor="middle">1202</text>
  <text class="value" x="1015" y="454" text-anchor="middle">1259</text>

  <text x="255" y="638" text-anchor="middle" font-size="18">1</text>
  <text x="445" y="638" text-anchor="middle" font-size="18">2</text>
  <text x="635" y="638" text-anchor="middle" font-size="18">4</text>
  <text x="825" y="638" text-anchor="middle" font-size="18">8</text>
  <text x="1015" y="638" text-anchor="middle" font-size="18">16</text>

  <text x="630" y="686" text-anchor="middle" font-size="20">Количество потоков</text>
  <text x="35" y="365" text-anchor="middle" font-size="20" transform="rotate(-90 35 365)">Время вычисления, мс</text>
</svg>
