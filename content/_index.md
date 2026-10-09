---
title: "Academic & Professional Portfolio"
layout: "index"
tags: []
---

<!-- LOAD LIGHTWEIGHT STABLE REACT ENGINE UTILITIES DIRECTLY -->
<script src="https://unpkg.com" crossorigin></script>
<script src="https://unpkg.com" crossorigin></script>

<div style="width: 100%; text-align: left; line-height: 1.8; font-family: inherit;">
  
  <!-- INTERACTIVE NATIVE REACT TARGET ROOT DOM -->
  <div id="react-interactive-root" style="width: 100%; margin-bottom: 25px;"></div>

  <p style="font-size: 1.05rem; margin-bottom: 25px;">I am an M.Sc. student in Computer Science and Engineering (Major: Data Science) at Daffodil International University where I also completed my B.Sc. in Computing and Information Systems (Major: Artificial Intelligence in IoT) with a CGPA of 3.89/4.00. My core research spans advanced machine learning architecture, deep learning frameworks, and deep graph neural networks for security.</p>
  
  <!-- Publications Block -->
  <div style="margin-top: 35px; margin-bottom: 25px;">
    <h3 style="border-bottom: 2px solid #0d9488; padding-bottom: 6px; color: #0d9488; font-size: 1.4rem; font-weight: 700;">📚 Publications</h3>
    <div style="margin-top: 12px; padding: 5px 0;">
      <p style="margin-bottom: 4px; font-size: 1.1rem; font-weight: 600;">Enhanced Linux Malware Detection Using Control Flow Graphs with Graph2Vec Embedding and Graph Attention Networks</p>
      <p style="font-size: 0.95rem; margin-bottom: 4px; opacity: 0.85;"><em>Sorifa Alam, Francis Rudra D Cruze, Rakibul Hasan Nirob, & Md. Ruhul Kuddus</em></p>
      <p style="font-size: 0.9rem; color: #0d9488; font-weight: 500;">Presented at the 11th IEEE International Women in Engineering (WIE) Conference on Electrical and Computer Engineering (WIECON-ECE 2025).</p>
    </div>
  </div>

  <!-- Education Block -->
  <div style="margin-top: 35px; margin-bottom: 25px;">
    <h3 style="border-bottom: 2px solid #0d9488; padding-bottom: 6px; color: #0d9488; font-size: 1.4rem; font-weight: 700;">🎓 Education</h3>
    <div style="margin-top: 15px; margin-bottom: 18px;">
      <p style="margin-bottom: 3px; font-weight: 600; font-size: 1.05rem;">M.Sc. in Computer Science and Engineering (Data Science)</p>
      <p style="font-size: 0.95rem; opacity: 0.8;">Daffodil International University | May 2026 - Present</p>
    </div>
    <div style="margin-top: 10px;">
      <p style="margin-bottom: 3px; font-weight: 600; font-size: 1.05rem;">B.Sc. in Computing and Information Systems (AI in IoT)</p>
      <p style="font-size: 0.95rem; opacity: 0.8;">Daffodil International University | Graduated: January 2026 — <strong style="color: #0d9488;">CGPA: 3.89 / 4.00</strong></p>
    </div>
  </div>

  <!-- Experiences & Leadership Block -->
  <div style="margin-top: 35px; margin-bottom: 25px;">
    <h3 style="border-bottom: 2px solid #0d9488; padding-bottom: 6px; color: #0d9488; font-size: 1.4rem; font-weight: 700;">💼 Experiences & Leadership</h3>
    <div style="margin-top: 15px; margin-bottom: 18px;">
      <p style="margin-bottom: 4px; font-weight: 600; font-size: 1.05rem;">Women Secretary — DIU Robotics Club <span style="font-size: 0.9rem; opacity: 0.7; font-weight: 400;">(2024 - 2025)</span></p>
      <p style="font-size: 0.95rem; opacity: 0.85;">Led strategic initiatives to increase female student enrollment and active participation in robotics engineering, programming, and hardware design workshops. Co-managed inter-university robotics competitions.</p>
    </div>
    <div style="margin-top: 10px;">
      <p style="margin-bottom: 4px; font-weight: 600; font-size: 1.05rem;">Education Abroad Ambassador — Graduate Consultancy <span style="font-size: 0.9rem; opacity: 0.7; font-weight: 400;">(2024 - 2025)</span></p>
      <p style="font-size: 0.95rem; opacity: 0.85;">Guided prospective students through global university selection processes, entry criteria analysis, visa application protocols, and documentation preparation.</p>
    </div>
  </div>

  <!-- Key Projects Block -->
  <div style="margin-top: 35px; margin-bottom: 25px;">
    <h3 style="border-bottom: 2px solid #0d9488; padding-bottom: 6px; color: #0d9488; font-size: 1.4rem; font-weight: 700;">🧠 Key Projects</h3>
    <div style="margin-top: 15px; margin-bottom: 18px;">
      <p style="margin-bottom: 3px; font-weight: 600; font-size: 1.05rem;">LeadGenius AI</p>
      <p style="font-size: 0.95rem; opacity: 0.85;">All-in-One Sales & Marketing Assistant deploying 9 autonomous, collaborative AI agents running cleanly with zero execution latency.</p>
    </div>
    <div style="margin-top: 10px;">
      <p style="margin-bottom: 3px; font-weight: 600; font-size: 1.05rem;">Disease & Diagnostics ML Systems</p>
      <p style="font-size: 0.95rem; opacity: 0.85;">Developed custom classification and prediction frameworks for Parkinson's Tracking, Autism Prediction, and Diabetes Risk Modeling.</p>
    </div>
  </div>
</div>

<script>
  window.addEventListener("load", function() {
    if (window.React && window.ReactDOM) {
      const e = React.createElement;

      function ReactBadge() {
        const [likes, setLikes] = React.useState(0);

        return e("div", {
          style: {
            padding: "16px",
            backgroundColor: "rgba(13, 148, 136, 0.1)",
            border: "1px dashed #0d9488",
            borderRadius: "8px",
            display: "flex",
            justifyContent: "space-between",
            alignItems: "center",
            flexWrap: "wrap",
            gap: "12px",
            width: "100%",
            boxSizing: "border-box"
          }
        }, 
        e("div", { style: { textAlign: "left" } },
          e("span", { style: { fontSize: "0.95rem", color: "#34d399", fontWeight: "bold", display: "block" } }, "✓ React.js UI Engine Loaded"),
          e("p", { style: { margin: "4px 0 0 0", fontSize: "0.85rem", opacity: 0.85, color: "#ffffff" } }, "This live component manages UI state functionality via React hooks embedded inside Hugo.")
        ),
        e("button", {
          onClick: function() { setLikes(likes + 1); },
          style: {
            backgroundColor: "#0d9488",
            color: "#ffffff",
            border: "none",
            padding: "8px 16px",
            borderRadius: "4px",
            cursor: "pointer",
            fontSize: "0.85rem",
            fontWeight: "600"
          }
        }, "👍 Endorse Profile (" + likes + ")")
        );
      }

      const rootElement = document.getElementById("react-interactive-root");
      if (rootElement) {
        const root = ReactDOM.createRoot(rootElement);
        root.render(e(ReactBadge));
      }
    }
  });
</script>
