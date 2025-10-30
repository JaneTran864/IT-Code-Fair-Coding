![mermaid-diagram](https://github.com/user-attachments/assets/f505f9ec-b19c-4acf-b3a3-2d58c0c7ebe1)# **Gesture Trainer** — *Train Your Own Action Recognition Model in Minutes*  

**No coding. No setup. Just record, train, and use.**  

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1oUZ8oPbDD37RU9o6sNpXI27t2_rHDFof)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
![Python](https://img.shields.io/badge/python-3.9%2B-blue)  
![Gradio](https://img.shields.io/badge/Gradio-Interactive-orange)

---

## **Why This Exists**

> **"I want my computer to recognize *my* gestures — like waving, clapping, or sign language — without being a programmer."**

**Gesture Trainer** makes this possible.

- Record short video clips of **your own actions**  
- Click **"Train"** — no code, no terminal  
- Use the model **live in your webcam**  
- All in **Google Colab + your browser**

Perfect for:  
Educators  
Students  
Sign language learners  
Makers & hobbyists  
Anyone curious about computer vision

---

## **Live Demo (Try It Now!)**

[**Open in Google Colab**](https://colab.research.google.com/drive/1oUZ8oPbDD37RU9o6sNpXI27t2_rHDFof)  
*(Click the badge above — no install needed)*

> **Just allow webcam access and follow the tabs!**

---

## **How It Works (3 Simple Steps)**

| Step | What You Do |
|------|-------------|
| **1. Collect** | Record 10–30 short clips of each gesture ("hello", "thanks",...) |
| **2. Train** | Click **"Train LSTM"** — takes 10–60 seconds |
| **3. Test Live** | See real-time recognition with **landmarks + confidence bars** |

---

## **Screenshots**

| Collect Tab | Train Tab | Live Recognition |
|------------|-----------|------------------|
| ![Collect](screenshots/collect.png) | ![Train](screenshots/train.png) | ![Live](screenshots/live.gif) |

---

## **Tech Behind the Magic**

| Component | Role |
|---------|------|
| **MediaPipe Holistic** | Detects pose, face, and hand landmarks in real-time |
| **LSTM Neural Network** | Learns temporal patterns from keypoint sequences |
| **Gradio** | Beautiful, interactive web UI in your browser |
| **Google Colab** | GPU + no setup |

![Uploading mermaid-diagram.svg…<svg aria-roledescription="flowchart-v2" role="graphics-document document" viewBox="0.00000762939453125 0 437.02435302734375 933.1267700195312" style="max-width: 437.02435302734375px;" class="flowchart" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg" width="100%" id="mermaid-diagram-mermaid-btamp8p"><style>#mermaid-diagram-mermaid-btamp8p{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-diagram-mermaid-btamp8p .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-diagram-mermaid-btamp8p .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-diagram-mermaid-btamp8p .error-icon{fill:#552222;}#mermaid-diagram-mermaid-btamp8p .error-text{fill:#552222;stroke:#552222;}#mermaid-diagram-mermaid-btamp8p .edge-thickness-normal{stroke-width:1px;}#mermaid-diagram-mermaid-btamp8p .edge-thickness-thick{stroke-width:3.5px;}#mermaid-diagram-mermaid-btamp8p .edge-pattern-solid{stroke-dasharray:0;}#mermaid-diagram-mermaid-btamp8p .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-diagram-mermaid-btamp8p .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-diagram-mermaid-btamp8p .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-diagram-mermaid-btamp8p .marker{fill:#666;stroke:#666;}#mermaid-diagram-mermaid-btamp8p .marker.cross{stroke:#666;}#mermaid-diagram-mermaid-btamp8p svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-diagram-mermaid-btamp8p p{margin:0;}#mermaid-diagram-mermaid-btamp8p .label{font-family:"trebuchet ms",verdana,arial,sans-serif;color:#000000;}#mermaid-diagram-mermaid-btamp8p .cluster-label text{fill:#333;}#mermaid-diagram-mermaid-btamp8p .cluster-label span{color:#333;}#mermaid-diagram-mermaid-btamp8p .cluster-label span p{background-color:transparent;}#mermaid-diagram-mermaid-btamp8p .label text,#mermaid-diagram-mermaid-btamp8p span{fill:#000000;color:#000000;}#mermaid-diagram-mermaid-btamp8p .node rect,#mermaid-diagram-mermaid-btamp8p .node circle,#mermaid-diagram-mermaid-btamp8p .node ellipse,#mermaid-diagram-mermaid-btamp8p .node polygon,#mermaid-diagram-mermaid-btamp8p .node path{fill:#eee;stroke:#999;stroke-width:1px;}#mermaid-diagram-mermaid-btamp8p .rough-node .label text,#mermaid-diagram-mermaid-btamp8p .node .label text,#mermaid-diagram-mermaid-btamp8p .image-shape .label,#mermaid-diagram-mermaid-btamp8p .icon-shape .label{text-anchor:middle;}#mermaid-diagram-mermaid-btamp8p .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#mermaid-diagram-mermaid-btamp8p .rough-node .label,#mermaid-diagram-mermaid-btamp8p .node .label,#mermaid-diagram-mermaid-btamp8p .image-shape .label,#mermaid-diagram-mermaid-btamp8p .icon-shape .label{text-align:center;}#mermaid-diagram-mermaid-btamp8p .node.clickable{cursor:pointer;}#mermaid-diagram-mermaid-btamp8p .root .anchor path{fill:#666!important;stroke-width:0;stroke:#666;}#mermaid-diagram-mermaid-btamp8p .arrowheadPath{fill:#333333;}#mermaid-diagram-mermaid-btamp8p .edgePath .path{stroke:#666;stroke-width:2.0px;}#mermaid-diagram-mermaid-btamp8p .flowchart-link{stroke:#666;fill:none;}#mermaid-diagram-mermaid-btamp8p .edgeLabel{background-color:white;text-align:center;}#mermaid-diagram-mermaid-btamp8p .edgeLabel p{background-color:white;}#mermaid-diagram-mermaid-btamp8p .edgeLabel rect{opacity:0.5;background-color:white;fill:white;}#mermaid-diagram-mermaid-btamp8p .labelBkg{background-color:rgba(255, 255, 255, 0.5);}#mermaid-diagram-mermaid-btamp8p .cluster rect{fill:hsl(0, 0%, 98.9215686275%);stroke:#707070;stroke-width:1px;}#mermaid-diagram-mermaid-btamp8p .cluster text{fill:#333;}#mermaid-diagram-mermaid-btamp8p .cluster span{color:#333;}#mermaid-diagram-mermaid-btamp8p div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:12px;background:hsl(-160, 0%, 93.3333333333%);border:1px solid #707070;border-radius:2px;pointer-events:none;z-index:100;}#mermaid-diagram-mermaid-btamp8p .flowchartTitleText{text-anchor:middle;font-size:18px;fill:#000000;}#mermaid-diagram-mermaid-btamp8p rect.text{fill:none;stroke-width:0;}#mermaid-diagram-mermaid-btamp8p .icon-shape,#mermaid-diagram-mermaid-btamp8p .image-shape{background-color:white;text-align:center;}#mermaid-diagram-mermaid-btamp8p .icon-shape p,#mermaid-diagram-mermaid-btamp8p .image-shape p{background-color:white;padding:2px;}#mermaid-diagram-mermaid-btamp8p .icon-shape rect,#mermaid-diagram-mermaid-btamp8p .image-shape rect{opacity:0.5;background-color:white;fill:white;}#mermaid-diagram-mermaid-btamp8p :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}</style><g><marker orient="auto" markerHeight="8" markerWidth="8" markerUnits="userSpaceOnUse" refY="5" refX="5" viewBox="0 0 10 10" class="marker flowchart-v2" id="mermaid-diagram-mermaid-btamp8p_flowchart-v2-pointEnd"><path style="stroke-width: 1; stroke-dasharray: 1, 0;" class="arrowMarkerPath" d="M 0 0 L 10 5 L 0 10 z"></path></marker><marker orient="auto" markerHeight="8" markerWidth="8" markerUnits="userSpaceOnUse" refY="5" refX="4.5" viewBox="0 0 10 10" class="marker flowchart-v2" id="mermaid-diagram-mermaid-btamp8p_flowchart-v2-pointStart"><path style="stroke-width: 1; stroke-dasharray: 1, 0;" class="arrowMarkerPath" d="M 0 5 L 10 10 L 10 0 z"></path></marker><marker orient="auto" markerHeight="11" markerWidth="11" markerUnits="userSpaceOnUse" refY="5" refX="11" viewBox="0 0 10 10" class="marker flowchart-v2" id="mermaid-diagram-mermaid-btamp8p_flowchart-v2-circleEnd"><circle style="stroke-width: 1; stroke-dasharray: 1, 0;" class="arrowMarkerPath" r="5" cy="5" cx="5"></circle></marker><marker orient="auto" markerHeight="11" markerWidth="11" markerUnits="userSpaceOnUse" refY="5" refX="-1" viewBox="0 0 10 10" class="marker flowchart-v2" id="mermaid-diagram-mermaid-btamp8p_flowchart-v2-circleStart"><circle style="stroke-width: 1; stroke-dasharray: 1, 0;" class="arrowMarkerPath" r="5" cy="5" cx="5"></circle></marker><marker orient="auto" markerHeight="11" markerWidth="11" markerUnits="userSpaceOnUse" refY="5.2" refX="12" viewBox="0 0 11 11" class="marker cross flowchart-v2" id="mermaid-diagram-mermaid-btamp8p_flowchart-v2-crossEnd"><path style="stroke-width: 2; stroke-dasharray: 1, 0;" class="arrowMarkerPath" d="M 1,1 l 9,9 M 10,1 l -9,9"></path></marker><marker orient="auto" markerHeight="11" markerWidth="11" markerUnits="userSpaceOnUse" refY="5.2" refX="-1" viewBox="0 0 11 11" class="marker cross flowchart-v2" id="mermaid-diagram-mermaid-btamp8p_flowchart-v2-crossStart"><path style="stroke-width: 2; stroke-dasharray: 1, 0;" class="arrowMarkerPath" d="M 1,1 l 9,9 M 10,1 l -9,9"></path></marker><g class="root"><g class="clusters"></g><g class="edgePaths"><path marker-end="url(#mermaid-diagram-mermaid-btamp8p_flowchart-v2-pointEnd)" style="" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" id="L_A_B_0" d="M241.655,61.993L241.655,66.16C241.655,70.326,241.655,78.66,241.655,86.326C241.655,93.993,241.655,100.993,241.655,104.493L241.655,107.993"></path><path marker-end="url(#mermaid-diagram-mermaid-btamp8p_flowchart-v2-pointEnd)" style="" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" id="L_B_C_0" d="M241.655,165.986L241.655,170.153C241.655,174.319,241.655,182.653,241.725,190.403C241.795,198.153,241.936,205.32,242.006,208.903L242.076,212.487"></path><path marker-end="url(#mermaid-diagram-mermaid-btamp8p_flowchart-v2-pointEnd)" style="" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" id="L_C_D_0" d="M201.178,340.692L188.298,353.604C175.418,366.516,149.658,392.34,136.778,410.752C123.898,429.164,123.898,440.163,123.898,445.662L123.898,451.161"></path><path marker-end="url(#mermaid-diagram-mermaid-btamp8p_flowchart-v2-pointEnd)" style="" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" id="L_C_E_0" d="M283.131,340.692L295.845,353.604C308.558,366.516,333.984,392.34,346.697,410.752C359.411,429.164,359.411,440.163,359.411,445.662L359.411,451.161"></path><path marker-end="url(#mermaid-diagram-mermaid-btamp8p_flowchart-v2-pointEnd)" style="" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" id="L_D_F_0" d="M123.898,509.155L123.898,513.321C123.898,517.488,123.898,525.821,132.725,533.885C141.551,541.949,159.204,549.744,168.03,553.641L176.857,557.539"></path><path marker-end="url(#mermaid-diagram-mermaid-btamp8p_flowchart-v2-pointEnd)" style="" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" id="L_E_F_0" d="M359.411,509.155L359.411,513.321C359.411,517.488,359.411,525.821,350.584,533.885C341.758,541.949,324.105,549.744,315.279,553.641L306.452,557.539"></path><path marker-end="url(#mermaid-diagram-mermaid-btamp8p_flowchart-v2-pointEnd)" style="" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" id="L_F_G_0" d="M241.655,613.148L241.655,617.314C241.655,621.481,241.655,629.814,241.655,637.481C241.655,645.148,241.655,652.148,241.655,655.648L241.655,659.148"></path><path marker-end="url(#mermaid-diagram-mermaid-btamp8p_flowchart-v2-pointEnd)" style="" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" id="L_G_H_0" d="M241.655,717.141L241.655,721.307C241.655,725.474,241.655,733.807,241.655,741.474C241.655,749.141,241.655,756.141,241.655,759.641L241.655,763.141"></path><path marker-end="url(#mermaid-diagram-mermaid-btamp8p_flowchart-v2-pointEnd)" style="" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" id="L_H_I_0" d="M241.655,821.134L241.655,825.3C241.655,829.467,241.655,837.8,241.655,845.467C241.655,853.134,241.655,860.134,241.655,863.634L241.655,867.134"></path></g><g class="edgeLabels"><g class="edgeLabel"><g transform="translate(0, 0)" class="label"><foreignObject height="0" width="0"><div class="labelBkg" xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel"><g transform="translate(0, 0)" class="label"><foreignObject height="0" width="0"><div class="labelBkg" xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g><g transform="translate(123.89845275878906, 418.1649398803711)" class="edgeLabel"><g transform="translate(-11.176216125488281, -11.996528625488281)" class="label"><foreignObject height="23.993057250976562" width="22.352432250976562"><div class="labelBkg" xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"><p>Yes</p></span></div></foreignObject></g></g><g transform="translate(359.4106216430664, 418.1649398803711)" class="edgeLabel"><g transform="translate(-9.301216125488281, -11.996528625488281)" class="label"><foreignObject height="23.993057250976562" width="18.602432250976562"><div class="labelBkg" xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"><p>No</p></span></div></foreignObject></g></g><g class="edgeLabel"><g transform="translate(0, 0)" class="label"><foreignObject height="0" width="0"><div class="labelBkg" xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel"><g transform="translate(0, 0)" class="label"><foreignObject height="0" width="0"><div class="labelBkg" xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel"><g transform="translate(0, 0)" class="label"><foreignObject height="0" width="0"><div class="labelBkg" xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel"><g transform="translate(0, 0)" class="label"><foreignObject height="0" width="0"><div class="labelBkg" xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g><g class="edgeLabel"><g transform="translate(0, 0)" class="label"><foreignObject height="0" width="0"><div class="labelBkg" xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="edgeLabel"></span></div></foreignObject></g></g></g><g class="nodes"><g transform="translate(241.65453720092773, 34.99652862548828)" id="flowchart-A-0" class="node default"><rect height="53.99305725097656" width="152.14410400390625" y="-26.99652862548828" x="-76.07205200195312" style="" class="basic label-container"></rect><g transform="translate(-46.072052001953125, -11.996528625488281)" style="" class="label"><rect></rect><foreignObject height="23.993057250976562" width="92.14410400390625"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Load Dataset</p></span></div></foreignObject></g></g><g transform="translate(241.65453720092773, 138.98958587646484)" id="flowchart-B-1" class="node default"><rect height="53.99305725097656" width="144.93923950195312" y="-26.99652862548828" x="-72.46961975097656" style="" class="basic label-container"></rect><g transform="translate(-42.46961975097656, -11.996528625488281)" style="" class="label"><rect></rect><foreignObject height="23.993057250976562" width="84.93923950195312"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Normalize X</p></span></div></foreignObject></g></g><g transform="translate(241.65453720092773, 298.57726287841797)" id="flowchart-C-3" class="node default"><polygon transform="translate(-82.59114837646484,82.59114837646484)" class="label-container" points="82.59114837646484,0 165.1822967529297,-82.59114837646484 82.59114837646484,-165.1822967529297 0,-82.59114837646484"></polygon><g transform="translate(-55.59461975097656, -11.996528625488281)" style="" class="label"><rect></rect><foreignObject height="23.993057250976562" width="111.18923950195312"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Sufficient Data?</p></span></div></foreignObject></g></g><g transform="translate(123.89845275878906, 482.15799713134766)" id="flowchart-D-5" class="node default"><rect height="53.99305725097656" width="231.79689025878906" y="-26.99652862548828" x="-115.89844512939453" style="" class="basic label-container"></rect><g transform="translate(-85.89844512939453, -11.996528625488281)" style="" class="label"><rect></rect><foreignObject height="23.993057250976562" width="171.79689025878906"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Stratified Train/Val Split</p></span></div></foreignObject></g></g><g transform="translate(359.4106216430664, 482.15799713134766)" id="flowchart-E-7" class="node default"><rect height="53.99305725097656" width="139.22743225097656" y="-26.99652862548828" x="-69.61371612548828" style="" class="basic label-container"></rect><g transform="translate(-39.61371612548828, -11.996528625488281)" style="" class="label"><rect></rect><foreignObject height="23.993057250976562" width="79.22743225097656"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Train on All</p></span></div></foreignObject></g></g><g transform="translate(241.65453720092773, 586.1510543823242)" id="flowchart-F-9" class="node default"><rect height="53.99305725097656" width="135.72048950195312" y="-26.99652862548828" x="-67.86024475097656" style="" class="basic label-container"></rect><g transform="translate(-37.86024475097656, -11.996528625488281)" style="" class="label"><rect></rect><foreignObject height="23.993057250976562" width="75.72048950195312"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Train LSTM</p></span></div></foreignObject></g></g><g transform="translate(241.65453720092773, 690.1441116333008)" id="flowchart-G-13" class="node default"><rect height="53.99305725097656" width="260.00001525878906" y="-26.99652862548828" x="-130.00000762939453" style="" class="basic label-container"></rect><g transform="translate(-100.00000762939453, -11.996528625488281)" style="" class="label"><rect></rect><foreignObject height="23.993057250976562" width="200.00001525878906"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Save Model + Labels + Norm Stats</p></span></div></foreignObject></g></g><g transform="translate(241.65453720092773, 794.1371688842773)" id="flowchart-H-15" class="node default"><rect height="53.99305725097656" width="167.4479217529297" y="-26.99652862548828" x="-83.72396087646484" style="" class="basic label-container"></rect><g transform="translate(-53.723960876464844, -11.996528625488281)" style="" class="label"><rect></rect><foreignObject height="23.993057250976562" width="107.44792175292969"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Plot Loss Curve</p></span></div></foreignObject></g></g><g transform="translate(241.65453720092773, 898.1302261352539)" id="flowchart-I-17" class="node default"><rect height="53.99305725097656" width="260.00001525878906" y="-26.99652862548828" x="-130.00000762939453" style="" class="basic label-container"></rect><g transform="translate(-100.00000762939453, -11.996528625488281)" style="" class="label"><rect></rect><foreignObject height="23.993057250976562" width="200.00001525878906"><div xmlns="http://www.w3.org/1999/xhtml" style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;"><span class="nodeLabel"><p>Compute Confusion Matrix &amp; Report</p></span></div></foreignObject></g></g></g></g></g></svg>]()


---

## **Quick Start Guide**

1. **Open the Colab notebook** (link above)
2. **Run all cells** (`Runtime > Run all`)
3. **Go to Tab 1: Collect**
   - Type action name: `wave`
   - Record 20 clips (5–10 seconds each)
4. **Go to Tab 2: Train**
   - Click **"Train LSTM"**
   - Wait ~30 seconds
5. **Go to Tab 3b: Live Test**
   - Click **"Load Latest Model"**
   - Wave at your webcam → see it recognised!

---

## **Custom Actions You Can Teach**

| Action | Use Case |
|-------|----------|
| `hello` | Greeting detection |
| `thanks` | Gratitude in sign language |
| `stop` | Safety gesture |

> **Teach *any* repeatable motion!**

---

## **Tips for Best Results**

- **Good lighting**, face the camera
- **Consistent background**
- **Same distance** from camera
- **10+ clips per action** (more = better)
- **Short clips** (3–10 seconds)

---

## **Workflow for Non-Technical Users**
![](screenshots/workflow.png) 

## **Your Data Stays Private**

- All videos processed locally in your browser/Colab
- Nothing uploaded to servers
- You own the model and data

## **Contribute**
We welcome:

- New UI translations
- Pre-trained models (sign language)
- Mobile export (TensorFlow Lite)
- More action templates

Just open an issue or PR!

## **Made With for Accessible Computer Vision**

> **"Computer Vision shouldn't require a PhD. It should require curiosity."**

Let’s bring computer vision to everyone.


