# Courtroom 4B

A 3D US criminal courtroom game. You are the presiding judge of the Harlan County Circuit Court, working through a day's docket of six detailed cases, from a speeding ticket to a homicide.

- Read the case file: citations, police reports, lab results, logs, and the details that decide each case.
- Rule on pretrial motions and on objections during testimony.
- Deliver verdicts and sentences within the guidelines. An appellate review grades every ruling.

## Talking to the court

Hold **Space** (or the mic button) and speak. The game asks for microphone permission when it loads. Try:

- "Sustained" / "Overruled" / "Motion granted" / "Denied"
- "Proceed", "Let's hear closing arguments", "Order in the court"
- "Officer Pike, did you pace the van?" (start with a name or role to address someone)
- "Not guilty" / "Guilty"
- "Twelve months probation, a fine of 250 dollars ... impose sentence"

With a Gemini API key (from Google AI Studio, entered on the start screen), every character improvises in character, argues and objects, and speaks with Gemini voices. Without one, the trial runs from its script with browser voices.

## Running it

Open `index.html` in Chrome or Edge, or serve it over HTTPS (for example GitHub Pages). Speech recognition needs a secure page, so `https://` or `localhost` works best.
