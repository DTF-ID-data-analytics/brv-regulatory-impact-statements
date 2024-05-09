# brv-regulatory-impact-statements
GitHub repository hosting of Better Regulation Victoria (BRV) public [Regulatory Impact Statements](https://www.vic.gov.au/regulatory-impact-statements) (RIS's) for AI access

Regulatory Impact Statements range from **2011** to date.
File formats supported:

`.pdf`

`.docx`

`.doc`


AI models using GitHub repositories:

1️⃣ [UseAdrenaline](https://useadrenaline.com/)


Test Results, 09/05/2024:

1️⃣ :x: TEST FAILED :x: [UseAdrenaline](https://useadrenaline.com/)

✔️ Uses GPT 4.0 with fine tuned language-learning models for technical responses.<br/>
:x: Slow performance with 5-non-boosted questions taking up to 60 seconds to answer.<br/>
:x: Fails to properly read large GitHub repositories. Max changes before warning at 50 MiB. GitHub block files should be smaller than 100MiB each.<br/>
:x::no_entry: Does not support reading .pdf, .docx and .doc files in respositories. This is a key failure.<br/>
:poop: Record outcome and move to a different AI/LM model.<br/>
