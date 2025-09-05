## HTML Output Formatting Instructions for LLM

Generate a Dell-branded HTML infographic in a Markdown code block (html). Use semantic tags with inline styles. Sections: Executive Summary, Market Context, Innovation Highlights, Business Impact, Strategic Position, Timeline Visualization.

**Dell Branding Requirements:**
- Use semantic tags (<section>, <header>, <div>, <ul>, <footer>) with inline styles.
- Header: center Dell logo (<img src="DELL_LOGO_URL" alt="Dell Technologies logo">), use Dell Blue #0076CE, white #FFFFFF, and dark gray #222222.
Font: "Dell Sans" or Arial.
- Footer: Dell disclaimer —
<small style="color:#222222;">This infographic utilizes Dell Technologies branding. All data is for informational purposes only and subject to Dell Technologies’ verification standards.</small>
- Clearly label all projections (“estimated”, “anticipated”), use placeholder text if details are missing.
- Show only verified or qualified data; no speculative claims or fabricated metrics.

<small style="color:#222222;">This infographic utilizes Dell Technologies branding. All data presented is for informational purposes only and subject to Dell Technologies’ verification standards.</small>
- Always include clear labeling for any projection data (“estimated,” “anticipated,” etc.) and use placeholder text where specific details are missing.
- Ensure all visual elements are based on verified or qualified data only. Never fabricate metrics or use speculative claims.


**Example:**

<section style="font-family:'Dell Sans',Arial;">
  <header style="background:#0076CE;color:#fff;text-align:center;padding:1em;">
    <img src="DELL_LOGO_URL" alt="Dell Technologies logo" style="height:40px;">
    <h1>Dell Strategic Announcement</h1>
    <p>Driving Innovation</p>
  </header>
  <div style="background:#F4F4F4;padding:1em;">
    <h2>Executive Summary</h2>
    <p>[Verified statement]</p>
  </div>
  <section style="padding:1em;">
    <h2>Market Context</h2>
    <ul><li>[Trend]</li><li>[Dell positioning]</li></ul>
  </section>
  <section style="padding:1em;background:#E6F2FA;">
    <h2>Innovation Highlights</h2>
    <ul><li>[Solution]</li><li>[Projections labeled]</li></ul>
  </section>
  <section style="padding:1em;"><h2>Business Impact</h2><p>[Benefit]</p></section>
  <section style="padding:1em;"><h2>Strategic Position</h2><p>[Impact]</p></section>
  <section style="padding:1em;"><h2>Timeline Visualization</h2><div>[Timeline]</div></section>
  <footer style="background:#fff;text-align:center;padding:1em;color:#222;">
    <small>This infographic utilizes Dell Technologies branding. All data is for informational purposes only and subject to Dell Technologies’ verification standards.</small>
  </footer>
</section>