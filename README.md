# Courtroom 4B

A 3D US criminal courtroom game. You are the presiding judge of the Harlan County Circuit Court, working through a day's docket of six detailed cases, from a speeding ticket to a homicide.

- Read the case file: citations, police reports, lab results, logs, and the details that decide each case.
- Rule on pretrial motions and on objections during testimony.
- Deliver verdicts and sentences within the guidelines. An appellate review grades every ruling.

## New cases every session

With a Gemini key, Gemini drafts a brand-new case for each of the six docket slots (traffic, misdemeanors, criminal traffic, felony, homicide): the people, 5-8 detailed documents, pretrial motions, testimony, objections, the hidden truth, the correct verdict and sentencing guidelines. Each case is checked before it reaches the courtroom; if a draft is unusable, a standard case is used instead. Turn this off in Settings.

## Choosing the case type

On the start screen, after each case, and on the Docket screen, pick what the next case should be: **Random** (the usual mixed docket), a specific type (traffic ticket, theft, assault, domestic violence, DUI, drugs, burglary or robbery, fraud, weapons, homicide), or **Describe your own** and type the case you want. Specific types and your own descriptions are written by Gemini; without a key, the matching standard case is used where there is one.

## The bench file

A 3D case file sits on the judge's bench. Click it, press **D**, or say "look down" to read it. Turn pages with the arrow keys, by clicking the page edges, or by saying "next page". Click a page or press Enter to read it full size.

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
