<pre class="mermaid">
  graph LR
      Start --> Stop
</pre>

<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@11/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>


flowchart TD
    VG["Veritris Group<br/>Corporate & Investment"]
    VTT["VTT<br/>Voice, Talk & Text<br/>Veritris Transport & Telecom Services"]
    VT["Veritris Technologies<br/>Intellectual Property"]

    VG --- VTT
    VTT --- VT

    VTT --> OPS["Operating Business Lines"]
    VT --> IP["IP Portfolio"]

    OPS --> O1["Voice • Fiber • Wireless • Mobility"]
    OPS --> O2["Hosting • Cloud • Managed Services"]
    OPS --> O3["Consulting • Contracting"]

    IP --> P1["Trademarks • Patents • Software"]
    IP --> P2["Platforms • Designs • Acquired Technology"]
